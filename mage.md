# Mage macros
Most of my mage macros are optimised for my PVP style.

## Main Action Bar
I like to keep my UI minimal, so I cram as much as possible into the main action bar, that means every slot has to do multiple things.

#### Highest rank Frostbolt with R1 Frostbolt and Fireball
```
#showtooltip frostbolt
/cast [mod:alt] frostbotl (rank 1); [mod:shift] fireball (rank 1); frostbolt
```

#### Conjure and consume everything in two buttons
```
#showtooltip
/cast [mod:alt] conjure food; [mod:shift] conjure mana ruby; conjure water
```

```
#showtooltip
/cast [mod:alt] conjured cinnamon roll; [mod:shift] mana ruby; conjured crystal water
```

#### Buffs
```
#showtooltip Dampen Magic
/cast [mod:alt] arcane brilliance; [mod:shift] dampen magic; ice armor
```

#### Shields
```
#showtooltip mana shield
/cast [mod:alt] frost ward; [mod:shift] fire ward; mana shield
```

#### Utility
```
#showtooltip remove lesser curse
/cast [mod:alt] amplify magic; [mod:shift] mage armor; [target=mouseover] remove curse
```

#### Reflectors
```
#showtooltip
/use [mod:alt] Hyper-Radiant Flame Reflector; [mod:shift] Gyrofreeze Ice Reflector; Ultra-Flash Shadow Reflector
```

#### Racials & PVP trinket
```
#showtooltip will of the forsaken
/cast [mod:alt] insignia of the Horde; [mod:shift] cannibalize; will of the forsaken
```

#### Ice block & cold snap
```
#showtooltip ice block
/stopcasting
/cancelaura Ice Block
/cast [mod:alt] cold snap; ice block
```

#### Arcane Missiles
```
#showtooltip arcane missiles
/cast [mod:alt]; [mod:shift]; [nochanneling:Arcane Missiles] Arcane Missiles

```

#### Get the rogues
```
#showtooltip
/cast [combat] arcane explosion; arcane explosion (rank 1)
```

#### Polymorph
```
#showtooltip
/cast [mod:alt] polymorph; [target=mouseover] Polymorph (rank 1)
```

#### POM/Pyro
```
#showtooltip Arcane Power
/use 13
/use 10
/cast Arcane Power
/cast Presence of Mind
/cast Pyroblast
```

#### Fire blast & R1 Fire Blast, useful for totems
```
#showtooltip fire blast
/cast [mod:alt] fire blast (rank 1); fire blast
```

#### Unstuck
```
/click HelpFrameCharacterStuckStuck
/run RepopMe()
```
