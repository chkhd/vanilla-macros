# Mage macros
Most of my mage macros are optimised for my PVP style.

## Rationale

I only use two action bars, there is a spell or two that does not make it there, but everything that is in regular use
is on my action bar through macros. Stuff like First Aid and Engineering does not need to be there as I can live with
pressing P once in a month or so when I need to craft items.

I mostly run with Undead and 21/0/30 spec, so these macros reflect that. I don't have that many macros for other specs.

## Keymap

There are a few unbound slots, I don't really need them at the moment, so I put potions and things like that just to
see the count. My keymap is as such:

```
Bar 1: q  e  r f g 1 2 c v ~ MS⬆ MS⬇
Bar 2: M4 M5 c v t 3 4 5 6
```

## Macros

I set some tooltips in seemingly illogical way, there is Cold Snap in the tooltip but not in the macro. Again, I do not
need to look to check where my spells are, the only reason I might look at my bars is to check if I have mana, or for
cooldowns. Besides, I have cases where multiple spells which have long cooldowns are on the same macro, so I need to put
their icons on other slots, where less important spells are.

### Spam out of combat to break stealth, dps in combat
```
#showtooltip
/cast [combat] arcane explosion; Arcane Explosion(Rank 1)
```

### Spam AM without the risk of interrupting a cast, use head slot item if usable, Bandage, or Shoot
```
#showtooltip arcane missiles
/stopattack
/use [mod:ctrl] 1; [mod:alt] Heavy Runecloth Bandage; [mod:shift] shoot; [nochanneling:Arcane Missiles] Arcane Missiles
```

### Blink, Ice Barrier, or Mana Shield
```
#showtooltip blink
/stopcasting
/cast [mod:alt] ice barrier; [mod:ctrl] mana shield; blink
#/cast [mod:alt] mana shield; [mod:ctrl] mana shield; blink
```

### Buffs, conveniently in the same place
```
#showtooltip cold snap
/cast [mod:alt] ice armor; [mod:shift] arcane intellect; [mod:ctrl] mage armor; dampen magic
```

### CoC, Sapper or Blast Wave. I usually bind this to MUP and Nova to MDown for quick combos
```
#showtooltip cone of cold
/use [mod:ctrl] Goblin Sapper Charge; [mod:alt] Blast Wave; cone of cold
```

### Create consumables, all in the same place
```
#showtooltip Conjured Crystal Water
/cast [mod:alt] conjure food; [mod:shift] Conjure Mana Ruby; conjure water
```

### Consume whatever
```
#showtooltip Mana Ruby
/use [mod:alt] Conjured Sweet Roll; [mod:shift] Mana Ruby; Conjured Crystal Water
```

### Counterspell, use top trinket, max rank Blizzard, or Flamestrike
```
#showtooltip counterspell
/use [mod:ctrl] 13; [mod:shift] blizzard; [mod:alt] flamestrike; counterspell
```

### Evocation, use bottom trinket, Remove Curse, or Slow Fall
```
#showtooltip evocation
/use [mod:ctrl] 14; [mod:alt] remove lesser curse; [mod:shift] slow fall; evocation
```

### Scorch, Engineering granade, max rank Fireball, or rank 1 Fireball for rogues
```
#showtooltip scorch
/cleartarget [dead][help]
/targetenemy [noexists]
/cast [mod:alt] fireball; [mod:shift] Fireball(Rank 1); [mod:ctrl] Iron Grenade; Scorch
```

### Fire Blast, rank 1 Fire Blast, Mount up, or max rank Fireball
```
#showtooltip fire blast
/cast [mod:shift] Fireball; [mod:ctrl] Horn of the Frostwolf Howler; [mod:alt] fire blast (rank 1); fire blast
```

### Frostbolt, rank 1 Frostbolt, rank 1 Blizzard, or Cold Snap
```
#showtooltip frostbolt
/cleartarget [dead][help]
/targetenemy [noexists]
/cast [mod:alt] Frostbolt(Rank 1); [mod:shift] Blizzard(Rank 1); [mod:ctrl] cold snap; frostbolt
```

### Ice Block, clear Ice Block, Will of the Forsaken, Insignia, or cannibalize
```
#showtooltip ice block
/stopcasting
/cancelaura Ice Block
/cast [mod:ctrl] insignia of the Horde; [mod:shift] cannibalize; [mod:alt] will of the forsaken; ice block
```

### Nova, does not have anything else on purpose
```
#showtooltip
/cast frost nova
```

### Quick PoM Frostbolt, if you for some reason cannot cast Frostbolt, f.e. if facing the wrong way or out of range,
### then serves also as PoM button.
```
#showtooltip presence of mind
/cast Presence of Mind
/cast frostbolt
```

### POM/Pyro
```
#showtooltip Arcane Power
/use 13
/use 10
/cast Arcane Power
/cast Presence of Mind
/cast Pyroblast
```

### Regular Polymorph, PVP Polymorph, mouse over poly or use belt
```
#showtooltip polymorph
/use [mod:ctrl] 8; [mod:shift] Polymorph(Rank 1); [mod:alt][@mouseover] Polymorph(Rank 1); polymorph
```

### Fire or frost ward
```
#showtooltip fire ward
/cast [mod:alt] frost ward; fire ward
```

### One button teleport
```
#showtooltip teleport: orgrimmar
/cast [mod:ctrl] Hearthstone; [mod:alt] teleport: undercity; [mod:shift] teleport: thunder bluff; teleport: orgrimmar
```

### One button protal
```
#showtooltip portal: orgrimmar
/cast [mod:alt] portal: undercity; [mod:shift] portal: thunder bluff; portal: orgrimmar
```

### Unstuck
```
/click HelpFrameCharacterStuckStuck
/run RepopMe()
```
