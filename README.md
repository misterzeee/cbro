# CBRO Rage Menu

Ping @_misterzeee in the severe discord for any issues or suggestions.

[![Youtube Video](https://private-user-images.githubusercontent.com/234246187/514819127-c9d23a9f-c1d8-40a9-950d-4d30a97b447d.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NjMyNTY1NjUsIm5iZiI6MTc2MzI1NjI2NSwicGF0aCI6Ii8yMzQyNDYxODcvNTE0ODE5MTI3LWM5ZDIzYTlmLWMxZDgtNDBhOS05NTBkLTRkMzBhOTdiNDQ3ZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUxMTE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MTExNlQwMTI0MjVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01NTZhNTU4MTM1OTgwOWM3MTY4YWVmMjZkMmU0NWYzNmNmODBmMjM0YWQ5OGQyOTA5MzlhMjRiM2EzNTU4MzJiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.XHF4J3MHbxL8T4vMzkGn0EOgRElcOfYZIUeJyN9MM2k)](https://youtu.be/SuCaD22eaRE)

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
