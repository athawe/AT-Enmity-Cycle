---
title: "Imentesh"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pathfinder-bestiary-2.Actor.hvKRgNiQtQJhHk9u" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/monitor
  - pf2e/creature/type/protean
  - pf2e/creature/level/10
statblock: inline
name: "Imentesh"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Imentesh"
level: "Creature 10"

alignment: ""
size: "Large"
trait_01: "chaotic"
trait_02: "monitor"
trait_03: "protean"
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Chthonian, Empyrean, Protean; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +19, Deception: +21, Diplomacy: +19, Performance: +21, Stealth: +21, Thievery: +17"
abilityMods: [7, 5, 5, 7, 3, 5]
speed: 25 feet,  fly 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +21, __Ref__ +19, __Will__ +17; +1 status to all saves vs. magic"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Resistances__ precision 10, protean anatomy 15"
abilities_top:
  - name: ""

  - name: "Entropy Sense"
    desc: " (divine,prediction) An imentesh can anticipate the most likely location of a creature through their supernatural insight into the forces of chaotic probabilities and chance. This grants the imentesh the ability to sense creatures within the listed range. A creature under the effects of [[Spells/Veil of Privacy|Veil of Privacy]] or that is otherwise shielded from divination and prediction cannot be noticed via entropy sense."

abilities_mid:
  - name: ""
  - name: "Protean Anatomy 15"
    desc: " (divine,polymorph) An imentesh's vital organs shift and change shape and position constantly. Immediately after the imentesh takes acid, electricity, or sonic damage, it gains the listed amount of resistance to that damage type. This lasts for 1 hour or until the next time the protean takes damage of one of the other types (in which case its resistance changes to match that type), whichever comes first.\n\nThe imentesh is immune to polymorph effects unless it is a willing target. If [[Conditions/Blinded|Blinded]] or [[Conditions/Deafened|Deafened]], the imentesh automatically recovers at the end of its next turn as new sensory organs grow to replace the compromised ones."

attacks:
  - name: ""

  - name: "Melee"
    desc: "`pf2:1` Jaws +23 (magical, reach 10 feet)\n__Damage__  2d10 + 11 piercing plus warpwave-strike 1d6 spirit plus warpwave-strike"

  - name: "Melee"
    desc: "`pf2:1` Claw +23 (agile, magical, reach 10 feet)\n__Damage__  2d6 + 11 slashing 1d6 spirit"

  - name: "Melee"
    desc: "`pf2:1` Tail +23 (magical, reach 15 feet)\n__Damage__  2d10 + 11 bludgeoning plus grab 1d6 spirit plus grab"

  - name: "Divine Innate Spells"
    desc: "DC 29, attack +19; __5th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Sending|Sending]]_; __4th __  _[[Spells/Creation|Creation]]_, _[[Spells/Translocate|Dimension Door (At will)]]_, _[[Spells/Shatter|Shatter]]_; __3rd __  _[[Spells/Haste|Haste]]_, _[[Spells/Mending|Mending]]_, _[[Spells/Shrink Item|Shrink Item]]_, _[[Spells/Slow|Slow]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At will) (Lawful only)]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_ __(4th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The imentesh takes the appearance of any Large or smaller creature. This doesn't change its Speed or its attack and damage bonuses with its Strikes, but might change the damage type its Strikes deal.\n\n* * *\n"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d10 + 11 bludgeoning damage, DC 29 Fortitude check\n\n* * *\n"

  - name: "Inflict Warpwave"
    desc: "`pf2:1` (divine) An imentesh inflicts a warpwave on a creature within 100 feet (DC 29 Fortitude check save to resist)."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  An imentesh's Strikes deal an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] targets."

  - name: "Warpwave Strike"
    desc: " (divine) Any creature struck and damaged by an imentesh's jaws Strike must succeed at a DC 29 Fortitude check save or be subject to a warpwave."

  - name: "Warpwaves"
    desc: "  Many proteans can subject their foes to disorienting alterations perceived in time and space by creating ripples of unstable reality in the environment called warpwaves.\n\nWhen a creature fails its saving throw and is affected by a warpwave, roll 1d8 and consult the table below for the specific effect on that creature.\n\nUnless indicated otherwise, a warpwave effect lasts for 1d4 rounds, and a new warpwave effect negates any previous warpwave effect already affecting a creature.\n* * *\n\n  \n\n| d8 | Warpwave Effect |\n| --- | --- |\n| 1 | [[Conditions/Clumsy 1\\|Clumsy 2]] ([[Conditions/Clumsy 1\\|Clumsy 3]] on a critical failure) |\n| 2 | [[Conditions/Confused\\|Confused]] and gains 4d6 temporary Hit Points |\n| 3 | [[Conditions/Dazzled\\|Dazzled]] (permanent on a critical failure) |\n| 4 | [[Conditions/Enfeebled 1\\|Enfeebled 2]] ([[Conditions/Enfeebled 1\\|Enfeebled 3]] on a critical failure) |\n| 5 | [[Conditions/Immobilized\\|Immobilized]] by filaments of energy |\n| 6 | [[Conditions/Quickened\\|Quickened]] (Stride, Strike, or Step only) |\n| 7 | [[Conditions/Slowed 1\\|Slowed 1]] |\n| 8 | [[Conditions/Stupefied 1\\|Stupefied 2]] ([[Conditions/Stupefied 1\\|Stupefied 3]] on a critical failure) |"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  "
 
```

```encounter-table
name: Imentesh
creatures:
  - 1: Imentesh
```



The loquacious proteans known as imenteshes serve as missionaries, spies, and heralds of chaos to further the protean goal of reality's dissolution. Imenteshes are cunning, curiously diplomatic, and profoundly whimsical. They travel beyond the Maelstrom for their work, frequently adopting extravagant personal attire and decorations that often border upon the garish, all to curry favor with less chaotic beings.
