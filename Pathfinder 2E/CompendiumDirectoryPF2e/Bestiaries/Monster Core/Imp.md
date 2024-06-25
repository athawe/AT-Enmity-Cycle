---
title: "Imp"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pathfinder-monster-core.Actor.yPYQC2bfOYmqcfIB" 
tags:
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Imp"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Imp"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: "fiend"
trait_02: "unholy"
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Common, Diabolic, Chthonian, Daemonic; Telepathy (Touch)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Arcana: +6, Deception: +7, Religion: +5"
abilityMods: [-1, 4, 0, 1, 2, 2]
speed: 20 feet,  fly 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +5, __Ref__ +9, __Will__ +7"
hp: 15
health:
  - name: ""
  - name: HP
    desc: "15; __Weaknesses__ holy 3; __Resistances__ poison 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "Melee"
    desc: "`pf2:1` Stinger +9 (agile, finesse, magical, reach 0 feet, unholy)\n__Damage__  1d4 - 1 piercing plus imp-venom 1d4 spirit plus imp-venom"

  - name: "Divine Innate Spells"
    desc: "DC 17, attack +9; __4th __  _[[Spells/Read Omens|Read Omens]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will, Self Only)]]_; __1st __  _[[Spells/Charm|Charm]]_\n__Cantrips__  __(1st)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph) The imp takes on the appearance of a Medium or smaller animal. While transformed, the imp loses their normal senses, innate spells, and special actions, but doesn't otherwise change their statistics and can still speak and use telepathy. The imp also gains any special senses of the animal and any Speeds the animal has.\n\nThis doesn't change the attack and damage modifiers of their Strikes but might change the damage type their Strikes deal (depending on what kinds of attacks the animal has) and prevents them from exposing creatures to imp venom.\n\n* * *\n"

  - name: "Fiendish Healing"
    desc: "`pf2:1` (concentrate,divine,healing,vitality) **Frequency** once per round.\n* * *\n\n**Effect** The imp regains 1d6 Hit Points."

  - name: "Fiendish Temptation"
    desc: "`pf2:1` (concentrate,divine,fortune,unholy) **Frequency** once per day\n* * *\n\n**Effect** The imp offers a nonfiend within 15 feet a bargain, granting a boon of good luck if the creature accepts voluntarily. The boon lasts for 1 hour once accepted.\n\nOnce during the hour, the creature can roll an attack roll or saving throw twice and use the higher result. If the creature dies while the boon is in place, the imp decides where the creature's soul travels. This typically makes the soul bound for eternity in the imp's home plane, and the creature unable to be raised or resurrected except by the [[Spells/Wish|Wish]] ritual or similar magic."

  - name: "Imp Venom"
    desc: " (poison) **Saving Throw** DC 16 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Clumsy 1|Clumsy 1]] (1 round)\n\n**Stage 2** 1d6 poison damage, clumsy 1, and [[Conditions/Slowed 1|Slowed 1]] (1 round)"
 
```

```encounter-table
name: Imp
creatures:
  - 1: Imp
```



Imps are fiendish infiltrators and corrupters who, despite their diminutive stature, are more than capable of subtly influencing a weak-willed individual into performing increasingly evil acts over time. An imp will often agree to serve a mortal and act docile and loyal in a long-term plot to eventually get their master killed or damn their soul. Imps are born directly from the Outer Planes themselves, rather than from mortal souls, and thus they serve outside any fiendish hierarchies, granting them leeway to pursue their specialties. Despite standing a mere 2 feet tall, imps can be vicious combatants, flying out of reach and turning invisible to escape should the odds turn against them.
