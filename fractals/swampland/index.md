---
title: 'Swampland'
date: '2020-03-27'
image: './images/bloomhunger_spirit_onslaught.jpg'
group: 'T4'
api: 2892
bosses: 1
difficulties: [{ level: 77, ar: 109 }, { level: 89, ar: 130 }]
record:
  {
    time: '5:09',
    by: { name: 'Lucky Noobs', tag: 'LN' },
    youtube:
      [
        {
          id: '2NeDItrX44I',
          name: 'Nightmare',
          specialization: 'Chronomancer',
        },
        { id: 'XTynF47Ekz4', name: 'Flaschor', specialization: 'Tempest' },
        { id: 'W3shEwUN0hU', name: 'Roca', specialization: 'Druid' },
      ],
  }
cycle: 'Night'
sigils: [{ id: 36053 }, { id: 24868 }]
consumables: [78978]
---

## Running the wisps

<Grid>
<GridItem sm="8">
Trigger the start event by walking to the three *Wisp Clefts* in the South. Wait for three players to be ready at each of the randomly spawned Wisps, usually indicated by typing `ready` in chat. Count down to go and deliver the Wisps to the Clefts within 30 seconds while avoiding <Condition name="stun"/>, <Condition name="immobile"/> and <Condition name="crippled"/> from the spike, wire and hunting traps on the ground.

Learn and practice to jump over the emerging walls, for nearly every wall there is an easy spot to skip over it.

The remaining two players can take the _Invigorator Rifle Prototypes_ from the ground and use `Skill 3` to grant <Boon name="stability"/> to the Wisp runners. Note that it is possible to carry the Wisp from the farthest point without using any movement skills.
</GridItem>

<GridItem sm="4">
<Image src="./images/the_three_wisp_clefts.jpg" caption="The three wisp clefts"/>
</GridItem>
</Grid>

<Tabs>
<Tab specialization="revenant">
Use <Skill name="Impossible Odds"/> (<Skill name="Legendary Assassin Stance" disableText/>) for better mobility.
</Tab>

<Tab specialization="warrior">
Use <Skill id="14516"/> for better mobility.
</Tab>

<Tab specialization="elementalist">
Equip <Skill id="5536"/> for mobility and <Skill id="5507"/> for a condition cleanse.
</Tab>

<Tab specialization="thief">
Use <Skill id="13038"/> or <Skill id="13002"/> for fast delivery.
</Tab>
</Tabs>

---

## The Mossman

<Grid>
<GridItem sm="8">
In the passage, the Mossman is waiting to fight you. You can break his defiance bar while he is in <Effect name="stealth"/> to force a reveal and make him <Effect name="Exposed"/>. Walk to the _Mistlock Singularity_ insite the Bloomhunger's lair to reset your cooldown and pre-stack some boons.
<Message>  
**Beware, there is a wisp that is <Effect name="invulnerability"/> and can attack you putting you in combat during pre-stack**!
</Message>
</GridItem>

<GridItem sm="4">
<Image src="./images/the_mossman.jpg" caption="The Mossman"/>
</GridItem>
</Grid>

---

## Bloomhunger

<Grid>
<GridItem sm="8">
Activate the encounter by placing the nearby Wisp into an empty Wisp Cleft. Bloomhunger (and all trash mobs) are only vulnerable inside the active Wisp Cleft area, additionally all players gain 100% increased endurance regeneration from it. The active area switches clockwise, move to the next position as soon as it decreases in size.

When Bloomhunger casts _Poison Rain_, immediately break his defiance bar (especially at the start of the fight) and nuke him to 75%/50%/25% life. Avoid his _Leap_ and _Charge_ attacks to prevent being <Control name="knockdown"/>ed.

### Spirit Onslaught <Label>75%, 50%</Label>

At 75% and 50% health, Bloomhunger will teleport to the middle and become <Effect name="invulnerability"/>. You will have to kill trash mobs inside the active Wisp Cleft to make him vulnerable again. Keep your pets and spirits close to yourself to prevent mobs from getting stuck. Kill the freshly spawned _Oakheart_ when you are out of mobs. Do not waste your time on Oakhearts while Bloomhunger is vulnerable.

Make sure to position yourself close to Bloomhunger before the phase ends to maximize the chance of him immediately jumping on you (and casting _Poison Rain_) instead of charging around.

### Running the wisps <Label>25%</Label>

Try to position yourself before Bloomhunger reaches 25% health. Again, he will teleport to the middle and become immune, but this time you have to carry four Wisps from northwest, northeast, southeast and southwest to their associated empty Wisp Cleft in the center area within 30 seconds. If you are near a Wisp before the phase begins, you can easily carry two Wisps before the time expires.

As soon as all four Wisp Clefts are activated, Bloomhunger gets vulnerable again and you can finish him off to complete the fractal.

<Image src="./images/bloomhunger_spirit_onslaught.jpg" caption="Bloomhunger during Spirit Onslaught"/>
</GridItem>

<GridItem sm="4">
<Image src="./images/bloomhunger.jpg" caption="Bloomhunger"/>
<Tabs>
<Tab specialization="revenant">
Take <Skill name="Legendary Demon Stance"/> / <Skill name="Legendary Renegade Stance"/> for this fight. Remove <Boon name="Protection"/> from Bloomhunger when he steps into the poison AoE.
</Tab>
</Tabs>
 
<Tabs> 
<Tab specialization="Tempest">
Use <Specialization name="Tempest"/> for this fight and <Skill id="22572"/> for better cleave during the Spirit Onslaught phases.
</Tab>
</Tabs>

<Tabs>
<Tab specialization="ranger">
Take <Skill id="12489"/> traited with <Trait id="1075"/> against the <Instability name="Afflicted"/> instability.
</Tab>
</Tabs>
</GridItem>
</Grid>


