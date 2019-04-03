# Repository for rockchip yocto SDK

Yocto SDK for the Rockchip SOC boards  
  - wiki <http://opensource.rock-chips.com/wiki_Main_Page>.

## Quick Start

1. Get the code using the Manifest and Repo tool:  
     <https://source.android.com/setup/develop/repo>  
2. Config your local config file (build/conf/local.conf)
   * You can create a local.conf manually, follow:  
   *   <https://git.yoctoproject.org/cgit.cgi/poky/plain/meta-poky/conf/local.conf.sample>  
   * Or use the existing config files for demoing e.g.: rockchip-rk3326-evb.conf
3. Run "source ./oe-init-build-env" to setup bitbake environment
4. Run "bitbake core-image-minimal" to build the images
5. Flash the generated "build/tmp/deploy/\<MACHINE\>/update.img" to your device
6. Boot your device and enjoy it

## Maintainers

* Jeffy Chen `<jeffy.chen@rock-chips.com>`
