File created on
Sun  5 Nov 17:58:58 AEDT 2017

Licenced under Creative commons non commercial share alike v4.0  
https://creativecommons.org/licenses/by-nc-sa/4.0/  
  
publish.sh script requires linux with pandoc and wkhtmltopdf installed.
This script will take the chapter files, combine them into a single html file, and convert into PDF.

~~~~
# Install prerequisites on Ubuntu
$ sudo apt install pandoc wkhtmltopdf
~~~~

# Mighty Kingdoms
Campaign rules for Kings of War for use with the the Mighty Empires tiles by GW, or any other hex based map.



##Index

1. Setup
2. The Year
3. Summer season
4. Winter season
5. Glossary
6. Advanced rules  

-------

##1. Setup

###Initial kingdom
A) Players are assigned a random play order. This will change at the end of each month in the Reform phase.
B) In play order each player takes turns choosing a starting tile (denoted with a white circle) by placing a city on it.
C) In play order each player places all of 1 additional city, 1 fortress, and 2 villages on any of the 6 tiles surrounding the capital. They also place control markers on the other 2 tiles not occupied by settlements.
D) Each player places 1 army in 1 tile they control that contains a settlement.
E) Army list. Each player writes up a 500 pt list to represent the army. The list may not contain any living legends, magic items, war machines, or monsters (including hero monsters). Once written, the list for that army is static and may not change except as per the medal and scar rules, below. Mark the army token with a unique symbol or number, and mark the list with the same symbol or number so you can keep track of it.

##2. The Year

Play proceeds through the summer season and winter season. The summer season is further broken down into months, during each of which players move armies, explore tiles and engage in battles. During the winter season players build settlements and new armies.


##3. Summer season

Summer has six turns, known as months.

Each month is split into 4 phases:

A) Orders  
B) Resolution  
C) Battle  
D) Reform  

###A) Orders
In player order, each player chooses one army and gives it an order. This is one order cycle. Repeat the order cycle until at least one player has given an order to all of their armies, then finish that order cycle and stop giving orders. That is, the maximum number of orders that can be given per player is the number of armies controlled by the player with the least armies.

Players may choose from the following orders:
Move  
Put the army you are ordering half into an adjacent tile to show which tile it plans to move into. The adjacent tile can be unexplored or controlled, and it does not matter who controls the tile. The army is still considered to be in the start tile until its order is resolved.  
Defend   
The army wishes to set up a defensive position and does not intend to move. Place a defensive marker on the army.  
Raze   
Only choosable if the army is on a settlement. The army intends to burn down the settlement. Turn the settlement upside down to mark this order.  

###B) Resolution
Resolve orders in player order, with each player choosing one army, resolving its order, and then the next player chooses 1 army, and so on until all armies have been resolved.  

|Order|Chosen tile|Effect|
|:--------|:------------|:----------------------------------------------------------|
|Move|Unexplored|Put the army in the indicated tile. Roll on the Exploration table and place the appropriate marker or settlement there under the control of the resolving player.|
||||
|Move|Controlled|Put the army in the indicated tile. If no enemy army is in the tile, the tile becomes controlled by the kingdom the army belongs to (or remains controlled by them if already the same).|
||||
|Raze|Settlement|If there is no enemy army in the tile remove the settlement. If there is an enemy army, the Raze fails with no effect.|
||||
|Defend|Controlled|The army stays where it is.|

The status of the tile may change during the resolution phase. Use the table entry appropriate at the time of order resolution. 
  
####Exploration table
|2D6|Tile contents|
|:--------|:--------------|
|2-7   |Empty|
|8-9   |Village|
|10    |City|
|11-12 |Fortress|

###C) Battle
After resolution, in player order each player chooses a tile in which they and an enemy have armies. They then choose an enemy in that tile and have a battle. When a battle occurs, all armies in the tile from one kingdom fight all the armies in the tile from the other kingdom in a game of Kings of War. The exception is armies on their side do not participate. They are not brought to the table for Kings of War, but they are affected by the results. You must choose an opponent with upright armies if possible. If all enemies only have armies on their side, remove one of those armies instead of playing a game of Kings of War; the battle is a slaughter of disordered troops instead. Continue choosing battles in player order until there are no more tiles with armies from more than one kingdom on them.

During a battle, any unit that damages and routs an enemy (shooting or melee) is given a medal, and any unit that is routed is given a scar. Mark these in pencil on the army list. A unit may only gain one of each per battle, but may earn more than one of each over the course of the month. If multiple units caused damage that turn to an enemy that is routed, choose only 1 unit to receive the medal. 
Kingdom's battle results
Loss
Each army on the losing side must be moved into an adjacent tile they control. Lay all such army tokens on their side. If there are no adjacent controlled tiles, they are destroyed.
Draw
All armies remain in the tile if their kingdom controls it. Otherwise they must move into an adjacent tile they control. If they need to move to an adjacent controlled tile and there are no adjacent controlled tiles, they are destroyed.
Win
Control of the tile is given to the winning kingdom. In addition 1 army may be moved to an adjacent tile they control.

###D) Reform
Stand up any armies that are on their side, and turn any settlements back the right way up that were upside down. Any tiles with only one kingdom's army on them become owned by that kingdom.

Every scar on a unit is cancelled out by a medal on that unit.

For any leftover medals or scars, consult the following tables.  

####Medals  
D6 + # of medals	Result  
2			Choose whether the unit gains Brutal or Headstrong.  
3			Improve the unit's nerve by +1/+1 (or -/+1 if fearless).  
4			Choose whether the unit gains Elite or Vicious.  
5			Choose whether the unit gains or improves crushing strength or piercing by 1, to a maximum of (3) each.  
6			Choose whether the unit increases its Me or Ra by 1, to no better than 2+.  
7+			Improve the unit's Def by 1, up to a maximum of 6.  

If the unit cannot benefit from the roll it gets, then they get a nice ceremony but no further lasting effect.

After rolling remove all medals from the unit.

####Scars  
D6 - # of scars	Result  
-1 or less	Worsen the unit's Def by 1. If this goes below 2, the unit is destroyed.  
0		Choose whether the unit lowers its Me or Ra by 1. You cannot choose a stat the unit does not have. If this goes above 6, the unit is destroyed.  
1		Worsen the unit's nerve by -1/-1 (or -/-1 if fearless). If their rout value goes below 6, the unit is destroyed.  
2		The unit gains Yellow Bellied.  
3+		If the unit was Very Inspiring, it becomes Inspiring. If the unit was Inspiring, it loses Inspiring. If it had neither, there is no effect.  

List building army composition rules only apply during the initial creation of an army. If a scar roll destroys a unit that would leave the number of other unit choices invalid (such as destorying a regiment meaning you have too many heroes), this is ok.

After rolling remove all scars from the unit.

If a destroyed unit was the last unit in an army, remove the army.

**Player order is redetermined at the end of each _Reform_ phase. Player order is now set by number of armies, descending. _That is, the player with the greatest number of armies is now the first player._ Randomly determine player order if there are ties in any slots.**  
  

----------  
##4. Winter season

Winter has 3 phases

A) Gather resources  
B) Spend resources  
C) Deploy armies  

###A) Gather resources
There are two resources - food and gold. Each player gathers resources simultaneously based on the settlements in their kingdom.
For every village you control, gain 1 food. For every city you control, gain 1 gold. Your capital city produces an additional gold for you if you control it (but not for you or the enemy if an enemy has taken it over). If your capital city has been Razed but you rebuild it from a village into a city again, it will again count as a capital city.

###B) Spend resources
In player order, each player may make one purchase. A purchase may be a settlement, an army, or a tithe. Repeat the purchase cycle until no more players wish to spend resources.
Settlements
You may build settlements in tiles you control. Each tile may only contain one settlement. Consult the following table for the cost of building settlements in various target tiles you control. If you build a settlement in a tile that already contains a settlement, the old settlement is replaced with the new one. An greyed out entry means that type of settlement may not be built on that type of tile.

1g = 1 Gold
1f = 1 Food
Target tile contents






Settlement to build
Empty
Village
City
Fortress
Swamp
All mountains
Sea
Village
1g






City

1g 1f

1g



Fortress
1g 1f
1g






If to want to make radical changes to your kingdom's demographics, you may want to Raze the settlements during the summer. You cannot voluntarily destroy settlements during the winter.
Armies
At each fortress you may recruit 1 army each winter. You may use a fortress you built this winter to recruit an army. An army costs 1 food to recruit. Place an army token in the fortress as per Setup 5) above.

However, some of the army restrictions are loosened if the player has the correct terrain in their kingdom as follows:
    • If the fortress is in or adjacent to a tile you control with mountains or a swamp you may include monsters in that army.
    • If the Fortress is in or adjacent to a tile you control with forest on it you may include war machines in that army.

You may only have a maximum of 6 armies. If you wish to build a new army when you already have 6, you may disband an existing army to do so.
Tithe
Give 1 other player up to 1 gold and up to 1 food. These gifts may not be refused, but may be given away by the receiver in a later tithe action of their own. A player may only tithe to each enemy once each winter. A tithe may or may not be attached to deals, promises or threats, none of which are enforcable. Backstabbing is encouraged!
Wizard’s quests
If you control one or more tiles adjacent to a Wizard’s Tower, you may send one Hero on one quest per adjacent tower. The same Hero may not go on two or more quests, they must be different Heroes. Choose a Hero unit from any of your armies, and roll on the below table. You may add or subtract up to 1 to your roll to determine your quest. Regardless of how your Hero fares in their quest, they always return back to their army unharmed thanks to the wizard’s magic. 
Quest table
D6 +/- up to 1
Quest type
Effect
Reward
0-1
Chance
Roll 2D6. Gain the reward on any total other than 7.
1 random magical artefact worth 5-15 points
2
Speed
Roll 2D6 and add the Hero’s Sp. If the total is 13 or more, gain the reward.
1 random magical artefact worth 20 points
3
Agility
Roll 2D6 and modify by +1 for fly, +2 for nimble, +2 for individual, +1 for (Inf), +1 for pathfinder, -1 for Strider, -1 for (Cav), -2 for (Lge Cav), -3 for (Mon), -1 per Def over 4 (all cumulative). If the total is 10 or more, gain the reward.
1 random magical artefact worth 25 points
4
Courage
Roll 6 attacks against the Hero’s front facing as if shooting, hitting on 4+ with Blast D3 and piercing (1). Then roll a nerve check. If the Hero does not rout, gain the reward.
1 random magical artefact worth 30 points
5
Endurance
Roll 6 attacks hitting on 4+ with Blast D3 and crushing strength (2) as if in melee against the Hero’s front facing. Then roll a nerve check. If the Hero does not waver or rout, gain the reward.
1 random magical artefact worth 35 points
6-7
Combat
Roll 6 attacks hitting on 4+ with Blast D3 and crushing strength (2) as if in melee against the Hero’s front facing. Then roll a nerve check. If the Hero does not waver or rout, have the Hero make a normal melee or shooting attack against a foe with Def 5+, nerve -/9, and a nerve check. If the foe is routed, gain the reward.
1 random magical artefact worth 40-50 points

Magical Artefacts
Magical artefacts are unique across the entire game, not per army. There should only be one deck of magical artefacts card (or one list), and anytime someone gains one, no other player or army may have that same item. During the deploy armies phase, allocate your items to specific units in your armies. You may not change this allocation until next Winter (losing and recapturing an item is an exception to this). If a unit with an item is routed in a battle in which their army loses, give the item to the winning player to allocate to an appropriate unit in that winning army. They may not change this allocation until next winter. If there are no appropriate units in that army (eg: Scarletmaw’s Fenulian Amulet and the army has no Lightning Bolt), the item is considered held by the player’s Capital City instead, to be allocated next Winter. If the player does not hold their Capital city, the item is lost on the field, and returned to the available pool of items for Wizard’s Quests. An item held by a Capital City that is taken over by an enemy is given to a unit in an enemy army that was part of the takeover.

Magical Artefacts are bonus items and do not count towards the points value of the unit or army for any purpose.

###C) Deploy armies
Place each of your armies in any settlement you control. Settlements may only have a limited number of armies deployed to each of them as seen in the following table.
Deployment limits
Settlement
Maximum number of armies
Village
1
City
2
Fortress
3
Glossary

Unexplored tile: Tiles that no players' armies have visited yet.
Controlled tile: A tile that has been explored by an army visiting it. Once explored, a tile will always be controlled by someone. Control is only lost to a player by having it be taken by another player.
Kingdom: All the tiles owned by a player. These need not be contiguous.
Control marker: A small token representing a player's kingdom, used to mark explored tiles.
Settlement: A city, village, fortress. A tile may contain a maximum of 1 settlement.
Summer month: A turn in which a player moves their armies to explore and engage in battles.
Enemy: Any army, settlement or tile controlled by another player.
Capital city: City marker on your starting tile. It only counts as your capital city if it was your starting tile, and if razed and rebuilt will again count as your capital city. If another player controls it it will count as a regular city for them.  
##6. Advanced rules

Add in advanced rules here, eg: Wizard tower, Mines, bridges, magic artefacts unique globally, etc