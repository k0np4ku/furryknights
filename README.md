# FurryKnights
Something something something. The native library uses symbol hook specially made for il2cpp, so you don't need to update its offset. It's guaranteed to work unless some there are major changes or another layer of security being added into the game.

## Configuration
You can find the configuration file on /sdcard/koa/furryknights.ini

In case you fucked up, you can delete the existing furryknights.ini and then a new configuration will be generated, or you can copy the following text:
```
# Note
## Types
# - Boolean: Only accept true & false as its value, and true means enabled, while false means disabled
# - Float: Fractional value, e.g., 1.0, 10.0, 100.0
# - Int: Integrer, or in idiot's language, a number

[main]
# Boolean | Setting this to false will disables entire functionality
enabled=true

[player]
# Float | Set to 1.0 for no multiplier
attackMultiplier=1.0

# Float | Set to 1.0 for no multiplier
defenseMultiplier=1.0

# Boolean
noDeployCost=true

[enemy]
# Float | Set to 1.0 for no reducement
attackReducement=1.0

# Float | Set to 1.0 for no reducement
defenseReducement=1.0

# Float | Set to 1.0 for no reducement
moveSpeedReducement=1.0
```