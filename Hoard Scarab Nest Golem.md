a hulking creature that carries a whole nest of these within itself. The scarabs scurrying along its surface are always restoring it and building upon it

```statblock
layout: Basic 5e Layout
name: Hoard Scarab Nest Golem
size: Large
type: construct
alignment: neutral
ac: 17
hp: 101
speed: "20 ft, 40ft burrowing (in piles of coins)"
stats: [16,7,16,4,4,4]
saves:
  - constitution: 5
senses: "tremorsense 60ft"
languages: none
condition_immunities: charmed, frightened
traits:
  - name: Nest Regeneration
    desc: If any tile the Nest Golem is standing on is a pile of gold, it will regenerate 10 hit points. If the Nest Golem takes any Fire or Acid damage, this effect is disabled until the end of its next turn.
actions:
  - name: Multiattack
    desc: The Nest Golem Slams twice, or Slams once and uses Release Scarabs
  - name: Slam
    desc: "Melee Weapon Attack: +5 to hit, one target. Hit (2d6+3) bludgeoning damage"
  - name: Release Scarabs
    desc: The Nest Golem releases a Swarm of Scarabs as a minion. If Nest Regeneration is active, it will release 2.
```
