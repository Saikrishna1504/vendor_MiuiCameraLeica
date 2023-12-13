# Repo has been moved into bitbucket

https://bitbucket.org/saikrishna1504/vendor_miuicameraleica

### Cloning :
- Clone this repo in vendor_MiuiCameraLeica in your working directory by :
```
git clone https://github.com/Saikrishna1504/vendor_MiuiCameraLeica vendor/MiuiCameraLeica
```
Make these changes in **aosp_begonia.mk**
```
# MiuiCamera
$(call inherit-product-if-exists, vendor/MiuiCameraLeica/config.mk)
```
## Credits
### Original mod - https://github.com/a406010503/Miui_Camera
### https://t.me/itzdfplayer_stash for base and helping with device configuration 
