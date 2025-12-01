# CBRO Rage Menu

Ping @_misterzeee in the severe discord for any issues or suggestions.

[![Youtube Video](https://github.com/user-attachments/assets/677637c8-93ff-452c-9391-0f5e249d75db)](https://www.youtube.com/watch?v=SuCaD22eaRE)

## Overview

**Load Script For Full**
```luau
bytecode = game:HttpGet("https://github.com/misterzeee/cbro/raw/refs/heads/main/cbroByteCode1.lua")
local func = luau.load(bytecode)
func()
```

**Load Script For Recoil/Spread ONLY (no ui)**
```luau
bytecode = game:HttpGet("https://github.com/misterzeee/cbro/raw/refs/heads/main/nospread.lua")
local func = luau.load(bytecode)
func()
```

**Theme**: Emerald

## Tabs

### 1. Gun Mods Tab

#### Fire Rate Slider
- **Range**: 1-100
- **Default**: 1
- **Description**: Adjusts weapon firing speed (lower values = faster firing)

#### Reload Time Slider
- **Range**: 0-100
- **Default**: 0
- **Description**: Adjusts weapon reload speed (lower values = faster reload)

#### Ammo Slider
- **Range**: 0-9,999
- **Default**: 9,999
- **Description**: Sets current ammunition count

#### Stored Ammo Slider
- **Range**: 0-5,000
- **Default**: 5,000
- **Description**: Sets reserve ammunition

#### Spread Slider
- **Range**: 0-200
- **Default**: 0
- **Description**: Adjusts weapon accuracy/spread (lower values = better accuracy)

#### Automatic Checkbox
- **Default**: Enabled
- **Description**: Toggles automatic firing mode

### 2. Visuals Tab

- **Status**: Coming Soon

### 3. Player Tab

- **Status**: Temporarily Removed

### 4. Misc Tab

#### Reset Guns Button
- **Description**: Restores all weapons to their original values

## TODO
- **Skin Chnager**: Changes the skins in a user's inverntory/hand
- **Fix Anti Aim**: Spin bot, character angle etc
