---
aliases: [Swarm of Bats]
created: 
description: 
image: 
level: 1
publish: 
role: spoiler
strength: normal
tags: ["13A/Bestiary/beast", "13A/Monsters/Type/spoiler"]
type: beast
updated: 
---
```statblock
layout: Basic 13th Age Monster Layout
columns: 1
name: "Swarm of Bats"
size: "normal"
level: "1"
levelOrdinal: "1st"
role: "spoiler"
type: "beast"
initiative: "5"
vulnerability: "thunder"
actions:
    - name: "C: Swarming bites +7 vs. PD (1d3 nearby enemies)"
      desc: "2 damage, and after the attack, the swarm of bats engages one of the targets"
      traits:
          - name: "Natural even hit"
            desc: "The target is hampered until the end of its next turn. It can end the effect by attacking the swarm, or if the swarm drops to 0 hp."
traits:
    - name: "No opportunities"
      desc: "The swarm of bats can’t make opportunity attacks, and enemies can’t make opportunity attacks against it."
    - name: "Swarming resistance"
      desc: "Each turn, the swarm of bats gains resist damage 18+ to all damage from attacks by enemies that the swarm did NOT attack that turn."
ac: "16"
pd: "16"
md: "11"
hp: "30"
```
