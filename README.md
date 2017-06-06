# RPG-game
Made by Elijah Gray, Jake Dempsey, and Jeremy Robb

Story: You are a critter, one that you customize yourself kind of like warband (it'll help make you feel you have a personality to your critter) and the world is dominated by other small guys in a semi struggle, semi cooperative way (think like the middle ages), there was a great extinction who knows how long ago, and that's where the humans, and MOST other big animals got wiped out, and now the world is dominated by both real critters (like rats and bunnies) and fantasy critters (like murlocs and unicorns, they are a lot smaller now we need to find a way to say that they used to be big they say, but had to shrink to survive the great extinction)
 
Name: come up with ideas, we also are going to need lots of small mythical creatures
 
Exploring: (new idea) ‘exploring’ will be the bread and butter of this project, it will also really help make the game more random (so far the only real random factor has been elijah's idea of enemies are a bit different each time), so there's no fight option, there's rather an option to ‘explore’ doing this will trigger lets say like a math.random * 20 (so numbers 1-20) i want maybe 30% of the numbers to be ones that will just be an enemy finding and fighting you, make like 1-4 a weaker enemy, 5-6 a stronger enemy and 7 a fairly formidable foe, and from there have the other 70% (the % can be changed) be events that can include fighting, but also stuff like gambling or trading an armor piece for a random wand 
Locations: each location will have some distinctive events, perhaps a shopkeeper as well, and in each shop, maybe they sell stuff at different prices
	The way the shop will work is well have arrays, array 1 may be like iceland's, and array 2 firelands, when shopping an ice potion would normally cost 30 say but if you are at array 1 it'll cost 20, if you're at array 2 it'll cost 40; that way we can basically file the lands into an array rather than making tons of different methods of lands
 
Fighting: 
	Enemies will probably (Figure out if this works) be chosen by an array, so if array = 1 (iceland's remember) then math.random * 2, if 1 is chosen then its an ice golem, if it's 2 then its a evil snowman for example; however in array 2 when you math.random the monsters will be lava golem and a mama magma, since its firelands
	At the beginning perhaps there is a weather effect, normal will be chosen the most, but other stuff can happen, like mist would make bow -30% damage
I want there to be a couple of different ways to do stuff, the fight begins with one bowshot each (since you start the fight a bit far away) then you can continue to shoot, however maybe after the second turn there will be a penalty since people are close.
	Secondly i want there to be spells, these do spell damage and are blocked by arcane armor or something, this will allow for there to be a mage spec
	Third i want there to be just strong go in sword or hammer waving power moves, these do physical damage and will be blocked by armor
	I want to find a way to make all this in a gui, here's a basic idea, for the battle YOU have a drop down section, 2 of them, one is for magical and one is for physical, and from there on the drop down thing you have a choice of moves you can do, each will cost mana (or energy maybe if you want to do physical stuff) and the damage you do will probably be mainly based on how much mana it costs, maybe if you have like a hammer though it would multiply the crush ability persay, and a sword might enhance a slash ability etc.
	Enemy will always strike after you probably, and do a random amount  of physical or magical damage (i plan to do this by like math.random * 10 which means it can do between 1 and 10 damage, if i want it to be like 4-14 dmg i can do math.random * 10 + 4), depending on what it is, the damage will be minimized by armor if its physical, and arcane will be minimized by your armor.
	So you can recruit companions, they will damage the enemy on their own, or heal you, maybe empower you. On that though later in the game enemies will group up together, so there will be two, the way that they'll go is that one will do their damage move, and then choose either you or your ally (it'll be random)
 
Leveling: some sort of leveling, when you level up I want there to be a way you choose some stats you want to upgrade, maybe you can choose like mana, power, or HP, leveling will be what determines when you can move on to the next area, that way you don't rush way ahead of yourself, and it will make leveling a bit more manageable, like zone 3 enemies will drop 10 xp rather than 3xp (which is what they drop in zone 1 say) and so that way we can make leveling take longer (by saying like ‘playerXPreq *1.3 = playerXPreq)’ and that way you can't just farm zone 1 to get super powerful super fast
 
Food (talk about this one it's not for certain): food will be a resource the player uses each move, running out of it can do one of two things, divide your stats by 2 (since you're starving) or it can hurt you each turn that you don't have it. The point of the food is that it can help balance a light - medium - and heavy loadout, a heavy person (speed < 3 for example) will consume 3 food a day maybe, medium (speed > 3 && speed < 7) will consume 2 food and a light loadout (speed > 7) will consume 1 food (these numbers can be changed).
 
Replayability: maybe the loot you find after battle is random, you have to build your loadout around it
	Each enemy will be constructed so its a bit different but not super different
	Each zone will have random events chosen using a math.random
 
Win condition: this still needs to be decided, and probably won't be added till the end but elijah and i were thinking that it could be 2 enemies, one does physical damage and the other does magical (so that way either a physical or magical loadout is viable) 
