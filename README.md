# HBMenu Forwarder
 This is a stub application, to make it launch hbmenu you have to configure Atmosphère to override 05A4999443B90000.

 To configure title override, copy `override_config.ini` from `sdmc:/atmosphere/config_templates` to
 `sdmc:/atmosphere/config`, then add the following lines under `[hbl_config]`

    program_id_1=05A4999443B90000
    override_key_1=!LR
 
# Why title override?
 In short, using title override means Atmosphère knows you're running the homebrew menu, and you always get the latest
 version of hbloader (sdmc:/atmosphere/hbl.nsp) without having to update the forwarder

# Why not override a game like a normal person?
 I'm already banned and I want an hbmenu icon. Also if you use sys-clk it still applies clocks when you override games.

# Thanks
 The-4n for [hacBrewPack](https://github.com/The-4n/hacBrewPack)  
 Switchbrew for [LibNX Examples](https://github.com/switchbrew/switch-examples)
 