**A no-cost press-fit interface for the [Picoprobe Candybar][URL-Candybar]** 🍫
===============================================================================


[![](../../../gitlab-redirect/raw/main/redirect.png)][URL-Repository]



***How do I use this library?***
================================

*These instructions assume a library directory of `./pcb/project-libraries/`*

- Ensure you are running KiCad 8.0 or later
- Download the latest [release][URL-Releases]
  > <details> <summary> To instead import as a git submodule... </summary>
  >
  > ```bash
  > mkdir -p pcb/project-libraries/ && cd $_
  > git submodule add ../../recursivenomad/picoprobe-candybar-interface.git
  > cd ../..
  > ```
  >
  > *If hosting/mirroring on GitHub, the relative URL redirects links appropriately and "shouldn't" break forking.*  
  > *For absolute portability, use: `https://gitlab.com/recursivenomad/picoprobe-candybar-interface.git`*
  >
  > </details>
- In your KiCad project, open `Preferences` > `Manage Footprint Libraries...`
- Select the **Project Specific Libraries** tab and click the folder icon to *Add Existing*
- Navigate to and select `.../picoprobe-candybar-interface/Connector_PicoprobeCandybar.pretty/`
- Then open `Preferences` > `Manage Symbol Libraries...`
- Select the **Project Specific Libraries** tab and cick the folder icon to *Add existing library to table*
- Navigate to and select `.../picoprobe-candybar-interface/Connector_PicoprobeCandybar.kicad_sym/`

To use, simply add the `Connector_PicoprobeCandybar` symbol to your schematic as you would any other.

### Happy hacking! 🎉

&nbsp;



***License / Access***
======================

This work is made freely available under your choice of the [*MIT-0*](./LICENSE.txt) license or [*CC0-1.0*][URL-CC0] public domain dedication.  
Although attribution is not required, sharing when you've made something with my work is really cool 💖

*No additional/conflicting permissions were present in this repository at the time of release.*

----------------------

*Repository: <https://gitlab.com/recursivenomad/picoprobe-candybar-interface/>*  
*Releases: <https://gitlab.com/recursivenomad/picoprobe-candybar-interface/-/releases/>*  
*Contact: <recursivenomad@protonmail.com>*

----------------------






[URL-MIT-0]: <https://opensource.org/license/mit-0/>
[URL-CC0]: <https://creativecommons.org/publicdomain/zero/1.0/>

[URL-Repository]: <https://gitlab.com/recursivenomad/picoprobe-candybar-interface/>
[URL-Releases]: <https://gitlab.com/recursivenomad/picoprobe-candybar-interface/-/releases/>

[URL-Candybar]: <https://gitlab.com/recursivenomad/picoprobe-candybar/>
