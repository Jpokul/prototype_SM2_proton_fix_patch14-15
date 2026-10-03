# prototype_SM2_proton_fix
A prototype fix created by jegglest (https://github.com/jegglest) using LLM that fixes constant crashing in Warhammer 40,000: Space Marine 2 that started around patch 14 and continues to be present in patch 15. 

Compiled by me to play comfortably until official fixes are available.

The base Proton version used is https://github.com/ValveSoftware/Proton

All rights belong to their respective owners.


The base used is 1790938299 proton-11.0-2c build from August 21, 2026. It's meant to be a temporary fix for those who want a quick way to play the game without affecting other Proton builds until a Wine developer writes a non-LLM fix or SM2 developers fix the issue on their side. 

## Usage
To use it, extract the folder containing all the files to a separate folder in <b>`~/.steam/root/compatibilitytools.d/`</b> that can be accessed by the `cd` command

Remember to use a separate folder for the files provided. If you view the contents of the aforementioned path, you will see other Proton versions Steam uses that will give you an idea of how the end structure should look.

The end path should look similar to this: <b>/home/(YourUsername)/.local/share/Steam/compatibilitytools.d/SM2_20261002_ntdll_and_abandon_mutexes_prototype_fix/</b>

After you put the directory there, restart Steam, access game properties, compatibility tab, check "Force the use of a specific Steam Play compatibility tool", and select SM2_20261002_ntdll_and_abandon_mutexes_prototype_fix

#### Download from: https://github.com/Jpokul/prototype_SM2_proton_fix_patch14-15/releases/tag/Zip

___

# How it works
I only compiled the solution, and there is nothing describing the issue or how the solution works.

As I saw this repo referenced, I must refer you to a collection of posts jegglest made that led to this repo:

https://github.com/ValveSoftware/Proton/issues/8072#issuecomment-5852529635

https://github.com/ValveSoftware/Proton/issues/8072#issuecomment-5858321198

https://github.com/ValveSoftware/Proton/issues/8072#issuecomment-5858593607

https://github.com/ValveSoftware/Proton/issues/8072#issuecomment-5858321198

https://github.com/ValveSoftware/Proton/issues/8072#issuecomment-5858593607

https://github.com/ValveSoftware/Proton/issues/8072#issuecomment-5903294489

https://github.com/ValveSoftware/Proton/issues/8072#issuecomment-5943056744

https://github.com/ValveSoftware/Proton/issues/8072#issuecomment-5943164082

https://github.com/ValveSoftware/Proton/issues/8072#issuecomment-5943989743
