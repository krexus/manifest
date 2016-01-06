<p align="center">
  <img src="https://raw.github.com/krexus/manifest/mm/krexus-logo.png" width="600">
</p>


*Stock nexus, as it should be*
------------------------------

Manifest
========

**Android 6.0.x** (latest is 6.0.1_r10)

1. Initialize the marshmallow repo	
`repo init -u https://github.com/krexus/manifest.git -b mr1`

2. Sync		
`repo sync`

3. Load the environment		
`ln -s vendor/krexus/utils/krebuild.sh krebuild.sh`		
`. krebuild.sh`

4. lunch and build!		
`lunch ****** && mka otapackage`

Credits
------------
Huge thanks to:  
[CallMeAldy](https://github.com/CallMeAldy)		
[Sykopompos](https://github.com/Sykopompos)		
[rascarlo](https://plus.google.com/+CarloDiNuccio/)		
[bgill55](https://github.com/bgill55)		
[BeansTown106](https://github.com/BeansTown106)		
[ZephiK](https://github.com/zephiK)		
[Cyanogenmod](https://github.com/CyanogenMod)  
Google	
AOSP
