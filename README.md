# Gone-Rouge
In a land far far away in distance and time, four honor-boun ninjas vowed to defend the sleepy village of Mell Town from brutal invaders. Uza, Kuro, Aka, and Midori all ensured the people of Mell Town they and their precious silver coins would be protected. Without these coins, the village would collapse. 

Uzai, the strongest in power, but weakest in will, fell victim to his own greed and ecided to take all of the silver coins for himself! It is up to Kuro, Aka, and Midori to stop their fallen brother who has _Gone Rouge_!

All three ninjas possess a unique ability. Master them and use it in battle to defeat Azai before he collects all of the gold and silver coins. The black ninja, Kuro, through a lifetime of training has the unique ability to throw a shuriken with perfect form. A hit from Kuro's shuriken cuases damage and slows Uzai down. The red ninja, Aka, possesses the most finely crafted sword the land has ever known! One hit from Aka's blade cuases greate damage to Uzai and slows him down. The blade is the strongest weapon, but be careful as you have to get close to use it. The greeen ninja is an expert tactician who has the unique ability to set up a trap anywhere in teh village. The trap causes damage to Uzai, and can be used to lock him in place before the trap deteriorates. Each ability has a cool-down period in which the ninjas need to recuperate their stamina. So, it is important to choose your shots wisely!

To help defeat Uzai in battle, the people of Mell Town cooked sushi for the ninjas. Consuming sushi increases their speed for a short period of time and recharges their ability. 

Uzai has mastered the art of hand-to-hand combat, but can only use this ability after collecting a gold coin. One hit from Uzai a short time after he has picked up a gold coin will leave each ninja unconcious for a breif period. Be careful around Uzai and good luck!

**Technical Notes: </br>**
The player can toggle between the three good ninjas, Kuro, Aka, and Midori. When the ninjas are in autonomous mode, that is when the player isn't currently controlling them, they wander the map. They do so by randomly selecting a waypoint on the map as target and sending out a [raycast](https://docs.unity3d.com/ScriptReference/Physics.Raycast.html) from their position to the target position. If the raycast returns true, the ninja repeats the process again. Otherwise, the ninja makes it's way to the waypoint and repeats the proces over and over again so long as it is in autonomous mode. 

Uzai, however, uses [A* path finding](https://en.wikipedia.org/wiki/A*_search_algorithm) to navigate the map more intelligently. 
</br>**Language:** C#
</br>**Software:** Unity, Visual Studio Code, Windows OS

**Link to download installer:** https://drive.google.com/file/d/1NkhRzG5-MIkEc-zz5hHi-uPTPnsDX7TE/view?usp=sharing
