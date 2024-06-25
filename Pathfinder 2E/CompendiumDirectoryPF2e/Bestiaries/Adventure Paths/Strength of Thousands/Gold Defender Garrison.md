---
title: "Gold Defender Garrison"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.strength-of-thousands-bestiary.Actor.1kr9leAaxUEsE69J" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2e/creature/type/troop
  - pf2e/creature/level/13
statblock: inline
name: "Gold Defender Garrison"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Gold Defender Garrison"
level: "Creature 13"
rare_03: "Rare"
alignment: ""
size: "grg"
trait_01: "construct"
trait_02: "mindless"
trait_03: "troop"
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +30"
abilityMods: [7, 2, 6, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +26, __Ref__ +22, __Will__ +22"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, 16 squares (160 &#x3D; 12 squares, 80 &#x3D; 8 squares); __Immunities__  fire,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ area damage 15, bludgeoning 10, splash damage 8; __Resistances__ physical 15 (except adamantine or bludgeoning)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  "

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|(Golem) Golem Antimagic]]"
    desc: "  harmed by _cold_(2d8 damage from areas or persistent damage); healed by _fire_ (area 2d8 Hit Points); slowed by _acid_\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as “cold and water”), either type of spell can affect the golem.\n\n*   **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n*   **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n*   **Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed 1|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n*   **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Death Throes"
    desc: "  As the garrison's numbers dwindle, gold defenders melt away into worthless slag. Every time that the garrison is reduced to a threshold, it leaves behind a 10-foot radius cloud of fumes and a 10-foot radius puddle of molten metal. Creatures that breathe fumes are exposed to gold defender poison. Creatures that move through the puddle take 10d6 fire damage. The fumes dissipate after 1 round and the puddle completely evaporates after 1 minute."

attacks:
  - name: ""

  - name: "Gold Defender Poison"
    desc: " (poison) Any [[Conditions/Drained 1|Drained]] value from this poison is reduced by 1 every hour\n\n**Saving Throw** DC 33 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 2d6 poison and [[Conditions/Drained 1|Drained 1]] (1 round)\n\n**Stage 2** 4d6 poison and [[Conditions/Drained 1|Drained 2]] (1 round)\n\n**Stage 3** 8d6 poison and [[Conditions/Drained 1|Drained 3]] (1 round)."

  - name: "Golden Strike"
    desc: "`pf2:1`  `pf2:1` to `pf2:3` actions\n\n**Frequency** once per round\n* * *\n\n**Effect** The garrison makes a melee attack against each enemy within 5 feet (DC 30 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 2d8 + 2 bludgeoning damage\n\n`pf2:2` 3d8 + 12 bludgeoning damage\n\n`pf2:3` 4d8 + 15 bludgeoning damage"

  - name: "Light Reflection"
    desc: "`pf2:2` (primal) **Requirements** The gold defender garrison is not in darkness\n* * *\n\n**Effect** The gold defender garrison reshapes its skin into a reflective surface that magnifies ambient light into a precise beam that burns all creatures in a 30-foot cone, dealing 14d6 fire damage (DC 31 Reflex check save if the gold defender is in dim light, DC 33 Reflex check save if it's in bright light). The size of the cone reduces to a 15-foot cone when the garrison is reduced to 8 or fewer squares. It can't use Light Reflection again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature takes no damage.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and catches fire, taking 1d6 persistent fire damage.\n\n**Critical Failure** As failure, but the persistent fire damage is 5d6 persistent fire."

  - name: "Troop Movement"
    desc: "  Whenever the garrison Strides, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square enters difficult terrain, the extra movement cost applies to the whole troop."
 
```

```encounter-table
name: Gold Defender Garrison
creatures:
  - 1: Gold Defender Garrison
```




