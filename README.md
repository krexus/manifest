<p align="center">
  <img src="https://raw.github.com/krexus/manifest/n+/krexus-logo.png" width="650">
</p>


*Stock Android, as it should be!*
---------------------------------

Manifest
--------

**Android 7.1.x** (latest is 7.1.2_r10)

1. Initialize the manifest repo		
`repo init -u https://github.com/krexus/manifest.git -b n+`

  1. If you want to exclude specific devices, just use the -g option with their device name:  
  `repo init -u https://github.com/krexus/manifest.git -g all,-hammerhead -b n+`

2. Sync		
`repo sync`
 
3. Lunch		
`lunch`

4. Build!		
`mka otapackage`
