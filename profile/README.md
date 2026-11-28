<div align="center">

<!-- Header: the DelPerroSands kit B look (navy, white edge, brand orange #ff7a45), same kit as github.com/DaemonAlex -->
<img width="100%" src="assets/banner.svg" alt="DPS Enhanced: free, open-source roleplay resources for FiveM for GTAV Enhanced. Built on Qbox."/>

<br/>

[![DelPerroSands](https://img.shields.io/badge/delperrosands.com-141a28?style=for-the-badge&logo=rockstargames&logoColor=ff7a45)](https://delperrosands.com)
[![DaemonScripts](https://img.shields.io/badge/daemonscripts.com-141a28?style=for-the-badge&logo=google-chrome&logoColor=ff7a45)](https://daemonscripts.com)
[![Licence](https://img.shields.io/badge/licence-GPL--3.0-141a28?style=for-the-badge&labelColor=141a28&color=ff7a45)](https://github.com/DPS-Enhanced/.github/blob/main/LICENSE)

<br/>

**Free, open-source resources for [Qbox](https://github.com/Qbox-project) servers on FiveM for GTAV Enhanced.**

Each resource is its own repository. Pick the ones you want.

<br/>

<img width="100%" src="assets/h-resources.svg" alt="Resources"/>

</div>

| Resource | What it does | Status |
|---|---|---|
| [**dps_welcome**](https://github.com/DPS-Enhanced/dps_welcome) | Loading screen with video or pictures, and a spawn screen with a camera over each spawn point | Tested in game |
| [**dps_police**](https://github.com/DPS-Enhanced/dps_police) | Police for every law enforcement job: duty, cuffs, evidence, fines, impound, jail | Starts clean |
| [**dps_medical**](https://github.com/DPS-Enhanced/dps_medical) | Health, injuries, bleeding, last stand and death | Starts clean |
| [**dps_voice**](https://github.com/DPS-Enhanced/dps_voice) | Voice chat on the new Enhanced voice system: talking distance, radio, phone calls | Starts clean |
| [**dps_jobs**](https://github.com/DPS-Enhanced/dps_jobs) | The DPS job list: police, medical, fire and justice, with ranks and pay | Starts clean |
| [**dps_lib**](https://github.com/DPS-Enhanced/dps_lib) | The DPS look and a few helpers the other resources share | Starts clean |

**Status.** *Tested in game* means it has been played on an Enhanced server. *Starts clean* means it
loads on an Enhanced server with no errors, and has not been played yet.

**More are on the way.** We are moving the Del Perro Sands scripts to Enhanced one at a time:
inventory with wearable bags, vehicle workshop, trains on a timetable, parking, fuel drive-offs,
shop clerks and owned shops, room building, pro racing, city worker, tow job and talking NPCs.

<div align="center">

<br/>

<img width="100%" src="assets/h-what-you-need.svg" alt="What you need"/>

</div>

| Requirement | Notes |
|---|---|
| FiveM for GTAV Enhanced server | Windows or Linux. Get it from the [Cfx server download page](https://docs.fivem.net/docs/server-download/) with Platform set to *FiveM for GTAV Enhanced*. |
| [qbx_core](https://github.com/Qbox-project/qbx_core) | The framework. |
| [ox_lib](https://github.com/overextended/ox_lib), [oxmysql](https://github.com/overextended/oxmysql), [ox_target](https://github.com/overextended/ox_target), [ox_inventory](https://github.com/overextended/ox_inventory) | Overextended libraries. |
| MariaDB or MySQL | Any recent version. |

Each resource lists anything extra it needs in its own README.

**To install one:** download the repository, put the folder in your server's `resources`, and add
`ensure` and its name to `server.cfg`. Each README has the exact steps.

<div align="center">

<br/>

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

**BUILT ON QBOX**

It is a set of resources, not a framework. The core stays [Qbox](https://github.com/Qbox-project), with the [Overextended](https://github.com/overextended) libraries.

</td>
<td align="center" width="50%">

**NO PAID DEPENDENCIES**

If a resource needs something, it is either open source or we write it. You never need to buy another script to run ours.

</td>
</tr>
</table>

<br/>

<img width="100%" src="assets/h-how-we-build.svg" alt="How we build"/>

</div>

1. **No paid or escrowed dependencies.**
2. **Open source before writing from scratch.** Where a resource is a port of someone else's work,
   its README says so and credits them.
3. **One job per resource.** No small one-off fix scripts.
4. **Tested on Enhanced.** Each resource's status says how far it has been tested.
5. **Every change goes through a pull request.**

**Names.** These resources use an underscore, `dps_police`, to match the Qbox style. The older
`dps-` repositories (with a hyphen) under [DaemonAlex](https://github.com/DaemonAlex) were written
for FiveM Legacy. They are the source these are converted from.

**Contributing.** Pull requests are welcome. Read the
[contributing guide](https://github.com/DPS-Enhanced/.github/blob/main/CONTRIBUTING.md) first.

**Thanks** to [Qbox](https://github.com/Qbox-project) for the framework and the resources ours are
ported from, [Overextended](https://github.com/overextended) for ox_lib, oxmysql, ox_target and
ox_inventory, [BebikDEV](https://github.com/Bebicek/bd_loadingscreen) for the loading screen ours is
ported from, and [Cfx.re](https://cfx.re) for FiveM and the Alchemist asset converter.

**Licence.** Everything here is licensed under the
[GNU General Public License v3.0](https://github.com/DPS-Enhanced/.github/blob/main/LICENSE).
You can use, change and share it. If you share a changed version, you must share its source code
under the same licence.

<br/>

<img width="100%" src="assets/footer.svg" alt="DPS Enhanced, by DaemonScripts and Del Perro Sands. Free under GPL-3.0."/>
