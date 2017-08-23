<p align="center">
  <img src="https://raw.github.com/krexus/manifest/o/krexus-logo.png" width="650">
</p>


*Stock Android, as it should be!*
---------------------------------

Manifest
--------

**Android 8.0.x** (latest is 8.0.0_r4)

1. Initialize the manifest repo		
`repo init -u https://github.com/krexus/manifest.git -b o`

  1. If you want to exclude specific devices, just use the -g option with their device name:  
  `repo init -u https://github.com/krexus/manifest.git -g all,-hammerhead -b o`

2. Sync		
`repo sync`
 
3. Lunch		
`lunch`

4. Build!		
`mka otapackage`
