# AOE Mining

Extends every hit with a pickaxe on an area of a rock/copper/pile to its nearby areas, allowing for a limited area of effect.

For those few who find mining a bit tedious.



# Manual Installation

1. Install BepInEx.
2. Extract the mod into _Valheim_\BepInEx\plugins folder.
3. Start the game normally.
4. (optional) Configure using _Valheim_\BepInEx\config\ChaseMods.AoeMining.cfg.



# Configuration

## MinSkillRadius

AOE radius at pickaxes skill 0.

## MaxSkillRadius

AOE radius at pickaxes skill 100.

## AoeKeyCode

AOE key KeyCode (can be set to None).

## InvertAoeKey

Invert AOE key action.
- false: hold AOE key for AOE mining (None key means there's only AOE mode)
- true: hold AOE key for normal mining (None key means AOE is always off))



# Changelog

#### 0.1.0
- added InvertAoeKey option

#### 0.0.1
- initial version
