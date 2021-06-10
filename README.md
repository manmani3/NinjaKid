# NinjaKid
This repository is for recreating the NinjaKid game

**1. Where the NinjaKid is came from**

It was one of the web game in the Yahoo korea.

![image](https://user-images.githubusercontent.com/20471600/121534792-839ec100-ca3c-11eb-8c5a-0da53fccf0d1.png)


<<Game Rule>>
  
  0. It's a turn-based game and victory condition is making oppnent's HP 0.
  
  <Before starting>
  
  1. Join two players into room and game is started when both of the players set 'Ready'
  
  2. The given map is 5*5 doors and each player should select the one of the doors before starting the game (Players don't know other players choice and can select a same door)
  
  3. The player's character is showed behind the chosen door. Each player can't see over the door and only can see the beyond the own character's door, but, they can see other player's character if two characters are behind same door.
  
  <In playing>
  
  4. In player A turn, A can choose one of the two actions('Move' or 'Attack'). All actions will be conducted and it's just for order. However, the each action's timeout is 30 sec.
 
  5. 'Attack' : player can choose the attack spot from the all map. The attacked door is destroyed and the place is not invisible anymore because there is no door. If the attack hits character, then the characters HP is reduced, and the attack hits an item, then the player get the item. 
    
  6. 'Move' : character can move to one of the 9 directions(including current door). After every 'Move', the two players get a notification saying "Other player is nearby" when the two characters are within 9 directions(including current door, of course). If character moves to the place where the door is destroyed, the character is exposed. If there is an item where the character moved, then the player get the item.
    
  7. 'Item' : The item is dropped to random place in a random turn. 
    

**2. How can revive it**

Creating it as mobile application game




**3. Basic architecture(V0.1, Demo)**

![image](https://user-images.githubusercontent.com/20471600/121534178-f2c7e580-ca3b-11eb-9a93-b3663f9b9e5c.png)




**4. The project planning**

v0.1(Demo) : recover the all functions of old NinjaKid as mobile app with server. We can play the basic game (don't consider the UI resource or design).

v0.5 : find/add the UI resources so that the app can be looked like a real game.

v1.0 : release to Goolgle store after fixing some bugs and testing for reliable service.

v2.0 : customizing the old features. For example, adding a new map(7*7, 9*9, or unblanced size map), adding a new items, and team play.


**It's for funny. Just contribute everybody who want to join this project (Please email me)**
