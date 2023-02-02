# Klipper_Sidewinder_X2_BIQU_H2_V2S_REVO
Klipper configuration for Artillery Sidewinder X2 and BIQU H2 V2S REVO

## Installation
Clone git

Link folder SWX2 in klipper instance configuration

    ln -s ~/Klipper_Sidewinder_X2_BIQU_H2_V2S_REVO/SWX2/ folderinstanceklipper/config/SWX2

Add to printer.cfg

    [include SWX2/*.cfg]

Add to  Moonraker.conf

    [update_manager SWX2]
    type: git_repo
    path: ~/Klipper_Sidewinder_X2_BIQU_H2_V2S_REVO
    origin: https://github.com/P-tite-tete/Klipper_Sidewinder_X2_BIQU_H2_V2S_REVO.git
    is_system_service: False
   
