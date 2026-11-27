# Contributing to DPS Enhanced

Thanks for helping. This guide is short on purpose. Read it once before your first pull request.

## The rules

1. **No paid or escrowed dependencies.** A DPS resource may depend only on open-source resources
   and on other DPS resources. If you need something that only exists as a paid script, write it,
   or find an open-source resource that does the job.
2. **Open source before writing from scratch.** If another project already does the job well, use
   it. If it needs a fix, send the fix to that project as a pull request.
3. **One job per resource.** Do not add small one-off fix scripts. A fix goes into the resource it
   belongs to. Shared helpers go into `dps_core`.
4. **Built on Qbox.** Use `qbx_core` and Overextended (`ox_lib`, `oxmysql`, `ox_target`,
   `ox_inventory`). Do not add bridges for ESX or QBCore.
5. **Every change goes through a pull request.** Nobody pushes straight to `main`.

## FiveM for GTAV Enhanced: what to watch for

Enhanced changed some behaviour that Legacy scripts relied on. Check each of these.

| Area | What changed | What to do |
|---|---|---|
| Game build checks | Enhanced runs only its latest build. Legacy build numbers (2189, 3258 and so on) do not apply. | Do not use `/gameBuild:` in `fxmanifest.lua`. Do not compare `GetGameBuildNumber()` to Legacy numbers. |
| NUI callbacks | Strict mode is on by default. A page may only call callbacks of the resource that owns it. | Call `https://${GetParentResourceName()}/name`. Never hard-code a resource name in the URL. |
| State bags | Change handlers fire only if the entity exists. Values replicate only when you ask. | Set replicated values with `:set(key, value, true)`. Do not rely on a handler for an entity that has not streamed in. |
| Player IDs | A server ID is reused after a player leaves. | Never use the server ID as a stored key. Use the citizen ID or the licence. |
| Key-value storage | Legacy KVP files must be migrated with Cfx's `kvdb-migrator`. | Prefer the database for anything that must last. |
| Voice | Mumble is deprecated. | Do not call Mumble natives directly. |
| C# | Mono was replaced by .NET. | C# resources must target .NET. |
| Streamed assets | Enhanced reads Gen9 assets from `stream_enhanced/`. `stream/` is deprecated. | Convert models and textures with Cfx's Alchemist and put the output in `stream_enhanced/`. |
| Resource builders | Resources can no longer be builders. | Ship built web files. Do not build on the server. |

The full list is on the Cfx page
[What's Changed in FiveM for GTAV Enhanced](https://docs.fivem.net/docs/developers/legacy-vs-enhanced/).

## Resource layout

```
dps_name/
  fxmanifest.lua     fx_version 'cerulean', game 'gta5', lua54 'yes'
  config.lua         everything a server owner may change, with a comment on each line
  client/            client scripts
  server/            server scripts
  shared/            code used on both sides
  locales/           text shown to players
  stream_enhanced/   converted models and textures, if any
  sql/               install SQL, if any
  tests/             tests that run without a server
  README.md          see below
```

Every README has these sections: **What it is for**, **What it does**, **Requirements**,
**Install**, **Configuration**, **Recent changes**.

## Before you open a pull request

- [ ] The resource starts with no errors on a FiveM for GTAV Enhanced server.
- [ ] You tested the change in game, not only by reading the code.
- [ ] No new dependency on a paid or escrowed script.
- [ ] No secrets in the code: no licence keys, passwords, tokens, webhooks or server addresses.
- [ ] The README describes the change under **Recent changes**.
- [ ] The tests in `tests/` pass, if the resource has them.

## Licence

By sending a pull request you agree that your work is licensed under the
[GNU General Public License v3.0](LICENSE), the same as the rest of this organisation.
