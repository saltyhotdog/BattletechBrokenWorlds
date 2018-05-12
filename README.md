# Battletech Broken Worlds

A mod aimed at increasing the overall grittiness and Battletech "feel" in the world. This will significantly increase the difficulty of the game.

### Dependencies

#### Battlech Mod Loader

https://github.com/Mpstark/BattleTechModLoader/releases

#### Modtek

https://github.com/Mpstark/ModTek/releases

#### Installation

Install the two above dependencies by following their instructions.

Unzip the "BrokenWorlds" folder to your /BATTLETECH/Mods/ folder.

Your final installation path should be **/BATTLETECH/Mods/BrokenWorlds**

### Recommended Mods

### Credits

This mod would not have been possible without the excellent work of the following people:

**Mpstark** (https://github.com/Mpstark/)
* Battletech Mod Loader
* ModTek
* Building the basis of the modding community

**Morphyum** (https://github.com/Morphyum/)
* All sorts of mods that will be listed here soon!

## Design Document

This document is intended as an explanation of changes the mod implements and the status of each change. Specific numbers for each change will be filled in as the features are tested and completed.

Every commit to the repository will carry the numbers of the roadmap features addressed by the commit as well as the relevant status update to this document. You can see the current status of the mod by checking the statuses of every subheader.

## I. A Hard Start

The game before the game. Starting with only one light mech and yourself as a pilot, you must build up your mercenary company from scratch. Imagine you're playing part of the three year interlude before the game even starts.  

This will not be an easy or forgiving part of your career, every mistake could cost you weeks of revenue in downtime. You will have to manage your resources very carefully to even make it to the first mission of the main campaign.

### 101 [Done] Start with only 1 mech and 1 pilot

Begin the game with only the mech from your background and yourself as a pilot.

### 102 [Planned] Background choice determines starting mech

 | Faction                | Mech       |
 |------------------------|------------|
 | Draconis Combine       | **PNT-9R** |
 | Free Worlds League     | **CDA-3C** |
 | Federated Suns         | **FS9-H**  |
 | Lyran Commonwealth     | **COM-2D** |
 | Cappelan Confederation | **UM-R60** |
 | Magistry of Canopus    | **SDR-5V** |
 | Taurian Concordat      | **JR7-D**  | 
 | Rimward Periphery      | **LCT-1M** | 
 | Deep Periphery         | **LCT-1V** |

### 103 [Planned] Initial incident choice determines starting equipment

 | Incident                        | Bonus                              |
 |---------------------------------|------------------------------------|
 | You were exiled                 | **LRM 5, 1 Ton LRM Ammo**          |
 | You struck out on your own      | **1 Small Laser**                  |
 | Your family went bankrupt       | **-10,000 Cbills, 2 Small Lasers** |
 | Your family died in an accident | **2 Jump Jets (S)**                |
 | Your family was betrayed        | **1 MG, 1 Ton MG Ammo**            |
  
### 104 [Planned] Life choice determines starting equipment

 | Life Choice               | Bonus                                    |
 |---------------------------|------------------------------------------|
 | Aurigan Coalition Soldier | **1 Medium Laser 1 Small Laser**         |
 | Frontier Pirate           | **2 Medium Lasers**                      |
 | Solaris Gladiator         | **1 AC/5, 1 Ton AC/5 Ammo, 1 Melee Mod** |
 | Inner Sphere Mercenary    | **10,000 Cbills, 1 Medium Laser**        |
 | Frontier Freelancer       | **1 SRM 4**                              |
 | Merchant Guard            | **25,000 Cbills**                        |

### 105 [Planned] Adjust starting funds, expenses, and equipment

Start the game with less than one months worth of cbills in the bank. Probably around two thirds of whatever one months cost is.

Starting equipment will be your choices plus:

* 1 Medium Laser  
* 1 SRM 2  
* 1 Ton SRM Ammo  

### 106 [Done] Skip the tutorial

You shouldn't play this mod until you do the main campaign at least once.

### 107 [Planned] Expand starting area

Add a few extra planets to the start area so it has more than 4 planets.

## II. Economy

The economic rebalances are intended to introduce complexity and meaningful decision making into how you manage your finances. Costs of most actions will be raised but rewards will be raised accordingly in some areas. Over extending your company should come with considerable financial risk.

### 201 [Planned] Mech specific maintenance costs

Adjust monthly maintenance costs of all mechs to reflect their chassis, their relative maintainability according to lore, and their general usefulness in the game.

### 202 [Planned] Drop costs based on drop weight and possibly mech cost

Add cost to mech drops based on weight to encourage bringing the appropriate amount of force on missions.

### 203 [Planned] Slightly increase mission payouts to offset some of the new costs

Since everything is getting more expensive, increase mission payouts a small amount. The struggle to be profitable should be present, but not artifically difficult. Probably around 10% will be sufficient.

### 204 [Planned] Higher repair and refit costs

Make armor addition and removal cost cbills. Make removing components take time if possible. Increase armor repair costs on heavier mechs.

### 205 [Planned] Lower contract payments on campaign missions

The main campaign missions pay a little too much based on their difficulty. The cbill payments for these missions will probably be lowered slightly.

### 206 [Planned] More economic affects from events

Add more events to the game that can have economic impacts based on player choices

### 207 [Planned] More scarcity in stores and higher prices in some systems

Add more variance to store pricing and availability. No more unlimited stocks if possible.

### 208 [Planned] Lower cost per mech part slightly and rebalance availability

Since salvage will require more mech parts, increase part availability slightly and decrease cost per part.

### 209 [Planned] Morale harder to maintain

Morale basically cannot go down. Each level of payment within the financial report should only be able to maintain morale at a certain level. In order to increase morale to a higher level new mechanics will be introduced.

## III. Salvage

Salvaging a new mech should be a more significant event in the game and give less free stuff. The changes here are intended to add complexity and some difficulty to obtaining salvage.

### 301 [Planned] Change the salvage rules to be more granular and less forgiving

Require 8 parts to complete a mech.

A dead mech starts with 8 parts
* -5 parts for a destroyed center torso
* -2 parts for each leg
* -1 part for head, arms, and side torsos

### 302 [Planned] Friendly mechs that lose their CT will be lost and must be salvaged

Mechs that lose their center torso will be lost. Ejecting will allow you to save your mech in its current state minus its head.

### 303 [Planned] Increase repair time for head internals

Increasing time to repair the head by a significant amount to simulate how difficult it is to fix a mech's cockpit.

### 304 [Planned] Salvaged Mechs and Mechs removed from storage start completely destroyed

A mech must be fully 'assembled' in order to use it. Possibly adjust repair costs if they're too much. The time cost should be sufficiently expensive on its own.

### 305 [Planned] Only drop exactly what the enemy had equipped

No ++ weapons, cockpit mods, gyros, or targetting computers unless the enemy has them equipped.

### 306 [Planned] Flatten tech point progression

Reduce the amount of potential tech points that can be gained throughout the game to keep repair and refit times signficant. Max tech points achievable without considering crew should be around 10.

### 307 [Planned] Slightly increase the amount of chooseable salvage in contracts

Due to greatly increasing the amount of mech parts needed, all salvage rates should probably be turned up 1 'notch.' In other words 4/18 would be turned into 5/22

## IV. Combat

The TTK in game is generally too low when using optimized builds. The goal is to increase TTK without adding artificial constraints so that fights can play out in a more tactical manner rather than just chaining called CT shots for instant wins.

### 401 [Planned] Increase base vision range

Make ranged weapons more viable by increasing the max vision range. The increase is probably 50 meters. It is currently too easy to get into AC/20 range without penalty.

### 402 [Planned] Less armor debuffed units

Progress to fighting fully armored units with more regularity. The base armor values are already very low, the player doesn't need a discount.

* No 25% armor units after 1 skull difficulty.
* No 50% armor units after 1.5 skull difficulty.
* No 75% armor units after 2 skull difficulty.

These values can be enforced with some variance so that they're not "set in stone" and you can still have a few surprises once in a while.

### 403 [Planned] Rebalance accuracy

Weapons are too accurate, which leads to lower time to kill.

* Base accuracy must be slightly lowered
* Medium range (+2 to hit) must be added to all weapons
* Called shot effectiveness needs to be reduced
* LRM's should not be able to make called shots (Implement by reducing their called shot deviation to their normal spread value)
* LRM accuracy general reduction +1-2 to hit.

### 404 [Planned] Reduce bulwark effectiveness

Bulwark is too strong, and reducing accuracy will only make it that much better. It will probably be reduced to 25% damage reduction to make it equal to cover.

### 405 [Planned] Rebalance evasion

Light mechs should have higher possible evasion, heavier mechs should have lower evasion. Possibly some amount of chassis dependent evasion if the game will allow it.

### 406 [Planned] Rebalance lostech

Make lostech weapons more appealing and also allow them to have special variants. 

### 407 [Research] Light mechs can fire after sprinting

This sounds like a really interesting idea, but needs to be researched. It would come with a heavy to hit penalty, probably at least +4.

### 408 [Research] Enemy pilots can eject

Enemy pilots may eject before their mech goes down if certain conditions are met.

## V. Map and Missions

### 501 [Planned] More mission types

Wait to see what we get from HBS for this in the first content update, then add even more!

### 502 [Planned] Equipment tables based on location

Have certain mechs and equipment be much more likely on certain worlds. This should offset the greatly increased variety of mechs and the harder to obtain salvage.

### 503 [Planned] Mini campaign deployments to encourage depth of roster

Longer missions where you must deploy on several missions back to back without a chance to repair. Have this clearly described in the contract.

### 503 [Planned] Events to modify planeteray tags and ownership

Have some contracts available that can modify the settings of a planet. For example you could either create or destroy a black market.

Missions that could flip the ownership to another faction and add/subtract many tags at once are appealing.

### 504 [Planned] More lostech content

More missions where lostech can be encountered and possibly salvaged as well as more presence in stores.

## VI. Other Content

Other content additions that don't need their own design section.

### 601 [Planned] More mech and vehicle variants

Anything from 3025 that can be put into the game will be in the game. Possibly some much rarer star league variants as well.

### 602 [Planned] Dynamically give some mechs better equipment

Enemy mechs may dynamically be assigned ++ weapons and other equipment. This may make them over tonned but this is okay as long as the game allows it.

### 603 [Planned] Named enemy mechs

Have a few special variants of much more meta mechs that can be increasingly dangerous. Ideally their parts will just count towards the chassis they're based on. Most likely no new hardpoints will be added to these.

### 604 [Planned] Add weight to gyro's and cockpit mods

Add a little more downside to taking cockpit mods and gyros. Probably not more than .5-2 tons. 

## VII. Expand ship crew options

Expand the leopard and argo to be able to hire crew to bring certain benefits to the unit. Crew will use up slots in the barracks so that you will actually have a reason to have 24 crew!

### 701 [Planned] Crew Management Screen

Either add crew to the barracks screen or potentially make an entirely new screen. This one will take some solutioning!

### 702 [Planned] Add Technicians

Technicians will generally add more tech points.

### 703 [Planned] Add Doctors

Doctors will generally add more medbay points.

### 704 [Research] Perks system

Add perks to characters that modify their abilities in certain positive and negative ways.

### 705 [Research] Accountants

Accountants could reduce expenses. They would have a diminishing return so having more than one or two would not be worth it.

### 706 [Research] Scientists

Scientists could potentially upgrade weapons or fix 'broken' lostech items that could be made available cheaper?

### 707 [Research] Chef / Entertainment

Crew that could make maintaining or gaining morale easier

## VIII. Retirement

### 801 [Planned] Build a retirement home / base

Before you can retire you must build the place you will retire to. This will most likely be accomplished with tags on planets. Once you have completed certain prerequisities you can then retire.

### 802 [Planned] Retirement

Once you have met all the prerequisities for retirement, you can then retire. After retiring you can choose to end your game or start a new campaign as your offspring.

The decisions you made and the retirement you built will have some affect on the next campaign.

## IX. A New Campaign

### 901 [Research] Play the game on a new map

Start a new campaign on a map of the entire inner sphere in a large sandbox universe with the things you gained from retirement. You will start with much less than you retired with and may have to rebuild the argo and get all new mechs. Star league tech will be much more widely available.

This campaign could eventually contain clan assets or possibly be an interlude to clan DLC.