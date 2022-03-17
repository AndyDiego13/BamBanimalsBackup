# **Bam! Banimal! Adventure**

## _Game Design Document_

---

##### **Copyright notice / Andrea Serrano Diego, Ariadne Alvarez Reyes and Andrea Yela González / boring legal stuff nobody likes**

##
## _Index_

---

- [**Bam! Banimal! Adventure**](#bam-banimal-adventure)
  - [_Game Design Document_](#game-design-document)
        - [**Copyright notice / Andrea Serrano Diego, Ariadne Alvarez Reyes and Andrea Yela González / boring legal stuff nobody likes**](#copyright-notice--andrea-serrano-diego-ariadne-alvarez-reyes-and-andrea-yela-gonzález--boring-legal-stuff-nobody-likes)
  - [_Index_](#index)
  - [_Game Design_](#game-design)
    - [**Summary**](#summary)
    - [**Storytelling**](#storytelling)
    - [**Gameplay**](#gameplay)
    - [**Mindset**](#mindset)
  - [_Technical_](#technical)
    - [**Screens**](#screens)
    - [**Controls**](#controls)
    - [**Mechanics**](#mechanics)
  - [_Level Design_](#level-design)
    - [**Themes**](#themes)
      - [Sketch of the island](#sketch-of-the-island)
    - [**Game Flow**](#game-flow)
  - [_Development_](#development)
    - [**Abstract Classes / Components**](#abstract-classes--components)
    - [**Derived Classes / Component Compositions**](#derived-classes--component-compositions)
  - [_Graphics_](#graphics)
    - [**Style Attributes**](#style-attributes)
    - [**Graphics Needed**](#graphics-needed)
  - [_Sounds/Music_](#soundsmusic)
    - [**Style Attributes**](#style-attributes-1)
    - [**Sounds Needed**](#sounds-needed)
    - [**Music Needed**](#music-needed)
  - [_Schedule_](#schedule)

## _Game Design_

---

### **Summary**

Sum up your game idea in 2 sentences. A kind of elevator pitch. Keep it simple!
Bam Banimal Adventure its a videogame where players will be able to learn different musical ensembles of percussion instruments through an adventurousness mission in an island which is affected by a virus that clashes/corrupts with certain Bam Banimals.

### **Storytelling**

The story begins on a tropical island where musical animals called Bam Banimals lived. Suddenly an unfortunate event happened, a virus arrived at the island and affected many Bam Banimals, causing their tuning to be out of tune. So now they were lost and scattered on the island without intonation.

Luhzio our main character is the only one who was not influenced, so the story starts with the player as Luhzio where through the island he will go through several levels that consist of re-singing his friends with the relevant percussion for each one. Each Bam Banimal it's different for each level and the player must past the levels completely to get to the other one because they are going to be blocked as well as the characters.

The reason why Luhzio was not affected is because he is only a purple tiger, he doesn't have any duality with other animal. The other animals got corrupted only by one half of them.

In the character description, we are going to show his skills as music theory and by learning the musical combinations you manage to beat the virus for each one of them till the final boss.

In an educational way, the objective for the player is to know and identify with musical theory the combinations with each sound that can be formed depending on the skills of each character.


### **Gameplay**

The development of the gameplay in each level begins with tempo tracking, interacting with buttons that will give the user the correct tempo guideline to get the right tempo for each musical note of a specific drum kit. In order to become familiar with the drums, the concept of the tempo and musical notes.

### **Mindset**

What kind of mindset do you want to provoke in the player? Do you want them to feel powerful, or weak? Adventurous, or nervous? Hurried, or calm? How do you intend to provoke those emotions?

## _Technical_

---

### **Screens**

1. Main Menu
    1. Title of Game
    2. Play game button
2. Level Select
    1. Map of the island
    2. The characters you are currently using
#### Inspiration ideas

<img src = "https://media.istockphoto.com/vectors/map-builder-illusrations-for-fantasy-and-medieval-cartography-and-vector-id1279356465">

<img src = "https://img.freepik.com/vector-gratis/encuentra-diferencias-juego-educativo-ninos-mapa-islas_255358-3185.jpg?size=338&ext=jpg">

<img src = "https://roleplus.app/img/usuarios/e95ef954d2b/UDEUP0034.jpg">

3. Game
    1. On the left you can see the characters you are playing as
    2. On the right you find the currupted bam banimal you need to fix
    3. Above the currupted character you see its currupted level.
    4. On the screen it will appear the keys you need to press to help the bam banimal.
4. Winning Level
    1. It will show the new character you saved and its powers/instrument they represent.
5. End Credits
    



### **Controls**

How will the player interact with the game? Will they be able to choose the controls? What kind of in-game events are they going to be able to trigger, and how? (e.g. pressing buttons, opening doors, etc.)

### **Mechanics**

Are there any interesting mechanics? If so, how are you going to accomplish them? Physics, algorithms, etc.

## _Level Design_

---

_(Note : These sections can safely be skipped if they&#39;re not relevant, or you&#39;d rather go about it another way. For most games, at least one of them should be useful. But I&#39;ll understand if you don&#39;t want to use them. It&#39;ll only hurt my feelings a little bit.)_

### **Themes**

1. Tropical Island
    1. Mood
        1. Calm, enduring, peaceful.
#### Sketch of the island

<img src = "https://github.com/AndyDiego13/BamBanimalsAdventure/blob/main/Documentation/PAS/Imagenes/SketchGame.png?raw=true" width = "685" height = "385">

<p>There are no collectibles, or objects that the player can interact with. </p>

### **Game Flow**

1. Player starts in forest
2. Pond to the left, must move right
3. To the right is a hill, player jumps to traverse it (&quot;jump&quot; taught)
4. Player encounters castle - door&#39;s shut and locked
5. There&#39;s a window within jump height, and a rock on the ground
6. Player picks up rock and throws at glass (&quot;throw&quot; taught)
7. … etc.

_(example)_

## _Development_

---

### **Abstract Classes / Components**

1. BasePhysics
    1. BasePlayer
    2. BaseEnemy
    3. BaseObject
2. BaseObstacle
3. BaseInteractable

_(example)_

### **Derived Classes / Component Compositions**

1. BasePlayer
    1. PlayerMain: Luhzio
    <p> This is the main character, the only Bam Banimal that isn't affected by the virus. It is a purple tiger. </p>  
2. Enemies
    1. Potatzio
    <p> This is a hybrid of a fox and a rabbit, you can collect it after you beat level 1 </p>
    2. Maparillo
    <p> This is a polar bear and a racoon hybrid, you can collect it after you beat level 2</p>
    3. Kiwano
    <p> A jellyfish and shark hybrid, you can collect it after you beat level 3 </p>
    4. Tutancamon
    <p> A toucan and monkey hybrid, , you can collect it after you beat level 4 </p>
    5. Akevia
    <p> The final boss and leader of the island, an axolotl and quetzal hybrid. </p>

3. BaseInteractable
    1. InteractableButton

_(example)_

## _Graphics_

---

### **Style Attributes**

The style of the game are pixel art, we are using procreate to make the sprites and their animation. The main color scheme is pastel colors, and each character has a "main" color, for example Luhzio is purple, Potatzio yellow and Maparillo grey and creme, so the player doesn't confuse the bam banimals. The characters will have an outline of a darker shade of their main color, and some shading.

#### Luhzio

<center><img  src = "https://github.com/AndyDiego13/BamBanimalsAdventure/blob/main/Documentation/PAS/Imagenes/Luhzio.png?raw=true"></center>

#### Potatzio
<center><img src = "https://github.com/AndyDiego13/BamBanimalsAdventure/blob/main/Documentation/PAS/Imagenes/Potatzio.png?raw=true" title = "Potatzio when you beat level 1" ></center>


#### Currupted Potatzio

<center><img src = "https://github.com/AndyDiego13/BamBanimalsAdventure/blob/main/Documentation/PAS/Imagenes/PotatzioVirus.png?raw=true" title = "Potatzio while infected" ></center>


Well-designed feedback, both good (e.g. leveling up) and bad (e.g. being hit), are great for teaching the player how to play through trial and error, instead of scripting a lengthy tutorial. What kind of visual feedback are you going to use to let the player know they&#39;re interacting with something? That they \*can\* interact with something?

### **Graphics Needed**

1. Characters
    1. Animal-like
        1. Luhzio (levitating)
        2. Potatzio (levitating) (glitched)
        3. Maparillo (levitating) (glitched)
        4. Kiwano (levitating) (glitched)
        5. Flabio (levitating) (glitched)
        6. Tutancamon (levitating) (glitched)
        7. Akevia (levitating) (glitched)
    
2. Ambient
    1. Island
    2. Tropical 
    3. Water (Underwater level)
    4. Sand
    5. Day/Night (From day to dawn)
    6. Contamined zone (island virus)

_(example)_


## _Sounds/Music_

---

### **Style Attributes**

Again, consistency is key. Define that consistency here. What kind of instruments do you want to use in your music? Any particular tempo, key? Influences, genre? Mood?

Stylistically, what kind of sound effects are you looking for? Do you want to exaggerate actions with lengthy, cartoony sounds (e.g. mario&#39;s jump), or use just enough to let the player know something happened (e.g. mega man&#39;s landing)? Going for realism? You can use the music style as a bit of a reference too.

 Remember, auditory feedback should stand out from the music and other sound effects so the player hears it well. Volume, panning, and frequency/pitch are all important aspects to consider in both music _and_ sounds - so plan accordingly!

### **Sounds Needed**

1. Effects
    1. Soft Footsteps (dirt floor)
    2. Sharper Footsteps (stone floor)
    3. Soft Landing (low vertical velocity)
    4. Hard Landing (high vertical velocity)
    5. Glass Breaking
    6. Chest Opening
    7. Door Opening
2. Feedback
    1. Relieved &quot;Ahhhh!&quot; (health)
    2. Shocked &quot;Ooomph!&quot; (attacked)
    3. Happy chime (extra life)
    4. Sad chime (died)

_(example)_

### **Music Needed**

1. Slow-paced, nerve-racking &quot;forest&quot; track
2. Exciting &quot;castle&quot; track
3. Creepy, slow &quot;dungeon&quot; track
4. Happy ending credits track
5. Rick Astley&#39;s hit #1 single &quot;Never Gonna Give You Up&quot;

_(example)_


## _Schedule_

---

_(define the main activities and the expected dates when they should be finished. This is only a reference, and can change as the project is developed)_

1. develop base classes
    1. base entity
        1. base player
        2. base enemy
        3. base block
  2. base app state
        1. game world
        2. menu world
2. develop player and basic block classes
    1. physics / collisions
3. find some smooth controls/physics
4. develop other derived classes
    1. blocks
        1. moving
        2. falling
        3. breaking
        4. cloud
    2. enemies
        1. soldier
        2. rat
        3. etc.
5. design levels
    1. introduce motion/jumping
    2. introduce throwing
    3. mind the pacing, let the player play between lessons
6. design sounds
7. design music

_(example)_
