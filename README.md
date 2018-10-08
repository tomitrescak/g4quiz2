# Introduction

Welcome to quiz 4! This time you will recreate iconic:

```
                         (_)                   | |              
 ___ _ __   __ _  ___ ___ _ _ ____   ____ _  __| | ___ _ __ ___ 
/ __| '_ \ / _` |/ __/ _ \ | '_ \ \ / / _` |/ _` |/ _ \ '__/ __|
\__ \ |_) | (_| | (_|  __/ | | | \ V / (_| | (_| |  __/ |  \__ \
|___/ .__/ \__,_|\___\___|_|_| |_|\_/ \__,_|\__,_|\___|_|  |___/
    | |                                                         
    |_|                                                         
```

The finished version will look a bit like following (the framerate is lower due to use of animated gif):

![https://user-images.githubusercontent.com/2682705/46639123-f9796d00-cbaf-11e8-9f8c-e2de7653a867.gif](Image 1)



# Instructions

1. Download zip from the following url: [https://github.com/tomitrescak/g4quiz2/archive/master.zip](https://github.com/tomitrescak/g4quiz2/archive/master.zip)

1. Unzip the file and open in Unity. 
1. Unity will possibly ask you to switch target to Windows. please do so.
1. Let the project compile, make sure there are no errors.
1. Open `Scenes/Quiz 2/Quiz` scene

# Tasks

We have already prepared quite a lot of functionality for you. You will only need to fill the gaps. Following is a set of five exercises that you need to complete:

1. Create full rows of invaders. Make sure the spacing is not random. Make it look nice.

2. Make the player move left and right. You do not need to use physics to move the player. You can rely on translate.

3. Make the player shoot lasers. We have already prepared a prefab for a laser for you. You can find it in Prefabs folder (Player Laser). Create laser at the location of the "Player Laser Spawn Point" gameobject (it is a child of the "Player" gameobject)

4. Make the enemy move. Enemy should move left and right and once it reaches the side of the screen you should move it down one row. You can achieve this behaviour moving right certain amount of time, left certain amount of time and then down. Be smart where you put the Playmaker FSM. Do you really need to control each enemy separately?

5. Make the enemy shoot lasers. We have already prepared a prefab for a laser for you. You can find it in Prefabs folder (Enemy Laser). Create laser at the location of the enemy. **Make sure you shoot only one laser at a time!**. Otherwise it would be a mayhem! You can use the functionality of **"Get Random Child"**. 

6. Player laser currently does not destroy enemies. Check out the implementation of the player laser and fill in the missing functionality.

7. Increase the score when you hit the enemy. We already prepared global variables for you. As a BONUS, the score should be nicely formatted as: 00005.

 