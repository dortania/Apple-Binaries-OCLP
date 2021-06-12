# Apple Binaries for OpenCore Legacy Patcher

Dedicated repo for hosting all patched binaries used with OpenCore Legacy Patcher

## Sources:

* [ASentientBot](https://github.com/ASentientBot):
  * Graphics Acceleration Patches
* [dosdude1](https://github.com/dosdude1):
  * Brightness Control for El Capitan
* [Ausdauersportler](https://github.com/Ausdauersportler):
  * Linking fixes for AppleIntelSNBGraphicsFB and AMDRadeonX3000.kext
* [Jackluke](https://github.com/jacklukem)
  * Determining patch set for Intel HD 4000
  
## Extra Arguments

Fix Screen Recording on TeraScale 2:
```sh
defaults write com.apple.cmio CMIO_Unit_Input_ASC.DoNotUseOpenCL -bool true
```