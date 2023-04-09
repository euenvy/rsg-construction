Original Creator : https://github.com/xThrasherrr/xt-construction/

# rsg-construction
I couldnt find a consruction job for rsg-core so i converted this one considering nobody did it yet and it was really simple!

- Converted to rsg-core
- Added Target!

### Preview: 

# General Info:
- Pickup Wood from marked location
- Place Wood at marked location

# Config:
- Add locations
- Set pay per drop and max drop count before task is completed
- Set rsg-lock options
- Set progressbar time
- Includes Debug setting

# Extras:
- Includes stuck prop command - Enable / Disable from Config
- Disable run & jump while carrying plank from Config

# Install:

Go to rsg-target > config.lua and att this code at line 53

    ["targetmodel1"] = {
        models = {
            "A_M_M_ValFarmer_01",
        },
        options = {
            {
                type = "client",
                event = "rsg-construction:OpenJobMenu",
                icon = "fas fa-hands",
                style = "", --fa-primary-color: brown; --fa-secondary-color: tan; --fa-secondary-opacity: 1.0;
                label = "Start/Stop Construction!",
            },
        },
        distance = 2.5,
    },

# Dependencies:
- rsg-core : https://github.com/Rexshack-RedM/rsg-core
- rsg-lock : https://github.com/euenvy/rsg-lock


