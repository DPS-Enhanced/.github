<div align="center">

<!-- Header: the DelPerroSands kit B look (navy, white edge, brand orange #ff7a45), same kit as github.com/DaemonAlex -->
<img width="100%" src="assets/banner.svg" alt="DPS Enhanced: free, open-source roleplay resources for FiveM for GTAV Enhanced. Built on Qbox."/>

<br/>

<!-- The one action in orange; the rest calm navy -->
[![Resources](https://img.shields.io/badge/browse_resources-ff7a45?style=for-the-badge&logo=github&logoColor=white&labelColor=ff7a45)](https://github.com/orgs/DPS-Enhanced/repositories)
[![DelPerroSands](https://img.shields.io/badge/delperrosands.com-141a28?style=for-the-badge&logo=rockstargames&logoColor=ff7a45)](https://delperrosands.com)
[![DaemonScripts](https://img.shields.io/badge/daemonscripts.com-141a28?style=for-the-badge&logo=google-chrome&logoColor=ff7a45)](https://daemonscripts.com)
[![Licence](https://img.shields.io/badge/licence-GPL--3.0-141a28?style=for-the-badge&labelColor=141a28&color=ff7a45)](https://github.com/DPS-Enhanced/.github/blob/main/LICENSE)

<br/><br/>

<img width="100%" src="assets/h-what-this-is.svg" alt="What this is"/>

<table>
<tr>
<td align="center" width="50%">

**BUILT FOR ENHANCED**

Every resource is written and tested on **FiveM for GTAV Enhanced**, the version of FiveM that runs on the new PC edition of GTA V.

</td>
<td align="center" width="50%">

**FREE AND OPEN**

No store, no keymaster, no licence key. Nothing is escrowed. Every line is yours to read, change and share.

</td>
</tr>
<tr>
<td align="center" width="50%">

**ONE FRAMEWORK**

Built on [Qbox](https://github.com/Qbox-project) and [Overextended](https://github.com/overextended). No bridges to ESX or QBCore.

</td>
<td align="center" width="50%">

**NO PAID DEPENDENCIES**

If a resource needs something, it is either open source or we write it. You never need to buy another script to run ours.

</td>
</tr>
</table>

<br/>

<img width="100%" src="assets/h-resources.svg" alt="Resources"/>

<br/>

<a href="https://delperrosands.com"><img src="dps-logo.svg" height="64" alt="DPS: Del Perro Sands"/></a>

<br/>

**Early days.** We are moving the Del Perro Sands scripts to Enhanced one at a time.
A resource is marked **Ready** only after it has started cleanly and been played on our Enhanced test server.

</div>

| Resource | What it does | Status |
|---|---|---|
| `dps_core` | Shared base every DPS resource uses: Qbox calls, notices, theme, database helpers | Planned |
| `dps_fleet` | Vehicle browser and workshop on one panel, with self-service repair when no mechanic is on | Planned |
| `dps_inventory` | ox_inventory with the DPS look, wearable bags and item rules | Planned |
| `dps_trains` | Trains on a timetable, with boarding, seats and arrival boards | Planned |
| `dps_parking` | Parking with valet, impound, tickets and reserved spots | Planned |
| `dps_fuel` | Pay after you fill, fuel theft and drive-offs | Planned |
| `dps_shops` | Shop clerks who greet and react to robberies, and shops players can own | Planned |
| `dps_studio` | Build the rooms players use every day from one admin panel | Planned |
| `dps_proracing` | Race lobbies, pit crews and a live leaderboard | Planned |
| `dps_cityworker` | City worker career: repairs, contracts and crews | Planned |
| `dps_towjob` | Queue-based tow job | Planned |
| `dps_vehiclepersistence` | Vehicles stay where they were parked | Planned |
| `dps_ainpcs` | NPCs you can talk to, with trust, quests and intel | Planned |

More resources follow as they are converted.

<div align="center">

<br/>

<img width="100%" src="assets/h-what-you-need.svg" alt="What you need"/>

</div>

| Requirement | Notes |
|---|---|
| FiveM for GTAV Enhanced server (Cfx Server) | Windows or Linux. Download it from the [Cfx server download page](https://docs.fivem.net/docs/server-download/) with Platform set to *FiveM for GTAV Enhanced*. |
| [qbx_core](https://github.com/Qbox-project/qbx_core) | The framework. |
| [ox_lib](https://github.com/overextended/ox_lib), [oxmysql](https://github.com/overextended/oxmysql), [ox_target](https://github.com/overextended/ox_target), [ox_inventory](https://github.com/overextended/ox_inventory) | Overextended libraries. |
| MariaDB or MySQL | Any recent version. |

Each resource lists anything extra it needs in its own README.

<div align="center">

<br/>

<img width="100%" src="assets/h-how-we-build.svg" alt="How we build"/>

</div>

1. **No paid or escrowed dependencies.** If a resource needs something we do not have, we write it,
   or we use an open-source resource that does the job.
2. **Open source before writing from scratch.** If another project already does it well, we use it
   and send our fixes back to that project as pull requests.
3. **One job per resource.** No small one-off fix scripts. A fix goes into the resource it belongs to.
4. **Tested on Enhanced before release.** Nothing is marked Ready until it has started cleanly and
   been played on an Enhanced server.
5. **Every change goes through a pull request.** Nothing is pushed straight to `main`.

**Names.** New resources use an underscore, `dps_fleet`, to match the Qbox style and mark them as the
Enhanced versions. The older `dps-` repositories (with a hyphen) under
[DaemonAlex](https://github.com/DaemonAlex) were written for FiveM Legacy. They are kept for their
history and are not maintained.

**Contributing.** Pull requests are welcome. Read the
[contributing guide](https://github.com/DPS-Enhanced/.github/blob/main/CONTRIBUTING.md) first.

**Thanks** to [Qbox](https://github.com/Qbox-project) for the framework,
[Overextended](https://github.com/overextended) for ox_lib, oxmysql, ox_target and ox_inventory,
and [Cfx.re](https://cfx.re) for FiveM and the Alchemist asset converter.

**Licence.** Everything here is licensed under the
[GNU General Public License v3.0](https://github.com/DPS-Enhanced/.github/blob/main/LICENSE).
You can use, change and share it. If you share a changed version, you must share its source code
under the same licence.

<br/>

<img width="100%" src="assets/footer.svg" alt="DPS Enhanced, by DaemonScripts and Del Perro Sands. Free under GPL-3.0."/>
