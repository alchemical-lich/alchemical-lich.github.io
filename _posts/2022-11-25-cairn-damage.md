---
title: 'Cairn Damage Analysis'
date: 2022-11-25
permalink: /posts/2022/11/cairn-damage/
tags:
  - BX
  - Cairn
  - DCC
  - 5e
---

# Introduction
I recently got to run Cairn for the first time and it was a blast. I really enjoyed the auto-hit mechanic, inventory management, and generally simple rules. Bonus points for not using Vancian casting (we used the GLoG magic option).

Cairn has a reputation for very fast and deadly combat, which matched the experience of our one-shot. It got me thinking though how a Fighter in Cairn stacks up against similar PCs in other systems. Cairn doesn't have classes, but I wanted to see how a martially-focused Cairn character performs against some standard monsters in comparison to games I have played a fair bit: BX, 5e, DCC.




# Assumptions
I tried to keep the comparison across systems fair, i.e., I relied on a simple fighter and two canonical monsters that appear across systems. 

Here are a few things I ignore: magic items, "combat as war" considerations, and morale. All of these things are available, at least as optional rules, in all four systems and would complicate the comparison of mechanical damage. 

In each case I calculate the expected damage per round against the creature (including crit damage if it is part of the system). I then compare the expected PC damage per round to the monster HP to determine the expected number of rounds until death. 

I then do the same for the monster vs. PC and calculate the net difference in expected rounds until death. Positive numbers indicate the PC killing the monster before being killed (in terms of rounds before the monster wins). Negative numbers indicate the monster winning.

## BX
I use a standard Fighter from level 1-10 with STR 13 and CON 12. The Fighter uses a longsword and uses chain mail + shield from level 1-4 and full plate + shield from level 5-10. 

The Fighter faces a canonical goblin and an owlbear. The owlbear uses its two claw attacks.

## DCC
I use a standard DCC Warrior with STR 13 and STA 12. The Warrior steps up the Mighty Deed die according to the progression table and increases their crit range (I assumed a simple +1d6 extra damage on a crit--probably conservative). The DCC Warrior also gains extra Action Dice (=extra attacks) at various levels. 

The Warrior uses longsword+shield and wears chain mail until level 5, then full plate. Armor scales slightly differently in DCC than BX.

Because the DCC goblin is especially puny, I used the BX goblin. I used the DCC Owlbear (with two claw attacks) for the second comparison.

## 5e

I assumed a Champion Fighter with STR 16 and CON 16. I used ASIs to first increase STR to max, then CON. I picked the dueling fighting style. The Fighter also uses a longsword+shield and wears chain mail until level 5, then full plate. I account for the Extra Attack feature at level 5, but ignore Action Surge and Second Wind.

I use the standard 5e goblin and owlbear.

## Cairn

To mimic a standard Fighter, I assume a STR 15 and give the character a longsword+shield and additional armor (for a total armor of 3 throughout). There is no mechanical advancement in Cairn, so I keep the stats the same throughout.

I also include a comparison for a version of Cairn based on Spellburn & Battlescars that includes some advancement. HP increases by 1 "per level" (I assume 1 level in the other systems is equal to one instance of advancement in Cairn/SB) and I increase STR by 3 points total (to 16) over the course of 10 levels. This only affects the defensive capabilities of the character.

# Results

## Goblin
In terms of pure offense, both DCC and Cairn allow Fighters right from the start to put a lot of hurt on a single goblin. Fighters in DCC and Cairn can expect to kill a goblin within the first round. BX and 5e Fighters will need two rounds to get the job done. 

As the Fighter increases the level, we see fairly linear progression in offense in BX, DCC, and 5e. Cairn remains expectedly flat in its damage output. Notably, BX and 5e track fairly closely with each other. DCC Warrior became true killing machines at level 5 and outpace the deadliness of Cairn Fighters when facing a goblin.


![Expected Rounds To Kill A Goblin](theophrastus-b0mbastus.github.io/images/goblin_rounds.pdf)

Considering the damage output of a Fighter relative to the damage output of the goblin, we see an even stronger advantage of the DCC warrior. This is largely because the DCC Warrior scales in terms of damage like a 5e Fighter, but has more HP and AC than a BX warrior and faces BX-like golbins (whereas as 5e Fighter has to deal with a stronger goblin). 

![Expected Net Rounds To Kill A Goblin](theophrastus-b0mbastus.github.io/images/goblin_net.pdf)



Cairn with SB advancement sees a bit of improvement over levels, because the slightly higher HP and STR increase the survivability in this variant.

Again, it is striking how closely a 5e Fighter tracks the classic BX Fighter.




## Owlbear
Looking at the owlbear, we see a similar pattern in terms of PC damage output. 


![Expected Rounds To Kill A Goblin](theophrastus-b0mbastus.github.io/images/owlbear_rounds.pdf)



In terms of net outcomes, owlbears are likely to kill a single Fighter until about level 5 in BX, 5e, and Cairn. DCC Warrior can expect to best an owlbear in single combat at around level 2 (a DCC owlbear has very few HP compared to the other systems).

![Expected Net Rounds To Kill A Goblin](theophrastus-b0mbastus.github.io/images/owlbear_net.pdf)



# Conclusion

- BX and 5e are remarkably similar in terms of offensive and net damage scaling. 5e has a bad reputation for slow combat and HP bloat. I am not sure of that is warranted, at least in terms of the HP-damage balance. In terms of mechanically hacking down a monster, 5e is very comparable to BX (to which you might say: yes! BX can be super whiffy and sluggish when facing high HP monsters).

- The DCC Warrior is an absolute killing machine! No wonder I like this class so much.

- Fighters in Cairn can end fights very quickly, especially at low levels, but receive to automatic scaling. That is by design. I think this just underscores that GMs really have to think about diegetic improvements. This also suggests possible challenges in converting adventures from BX or 5e for level 5+ or when using high HD monsters--Cairn PCs have little mechanical ability to confront them, even less than in other OSR systems. 
