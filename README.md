[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Oscar Townes
### Student number: 4739 5281 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

I designed the first section (everything before the hub room) to only have one mechanic introduced per encounter, helping the player slowly learn mechanics and not overwhelm them. After this a introduce enemies in the grassy cave (section 2), and finally puzzle mechanics, switches and boxes in the puzzle chamber (section 3). I also broke up the introduction of the staff and the gun to give the player time to get used to combat and enemies before giving them another weapon as well as to keep a level of difficulty in the grassy cave.

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

I intentionally seperated the three sections with either one way drops, the hub or long hallways as spots of rest for the player and giving them time to slow down and recover. In the first section the difficulty of encounters slowly increases then the player gets dropped into the hub room revealing the main goal. They then enter the grassy cave and the difficulty in platforming and enemies slowly increases. there is a short one way drop halfway through this section, before giving them a more intense platforming and emeny encounter, as well as introducing the gun to again give them a moment of rest before introducing a large mechanic. the final section is more of a puzzle room with a scavenger hunt, so I gave a few spots where there are no enemies as well spaces for the player to see what they are looking for to give them time to think. I also loop the first section back to the hub to remind the player of their main goal.

//image of the whole map highlighting the corridors

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

I have made the first section not challenging and very linear to clearly guide the player first and get them into a flow. After dropping them into the hub I have designed each section to ensure the player can always be doing something, and keeping them engaged by throwing varied mechanics at them as well as balancing the rooms to not have too many enemies that player feels overwhelmed. The puzzle room has two different puzzles, a scaveneger hunt and a box moving puzzle. I used the single use switches to give a visual indicator that the player is progressing as they stay on when they are hit. The box moving puzzle I designed to show the player when things happen, e.g. the box drops in view when the switch is hit and shows the door opening that the player needs to open to drop the box further down the map.

//Images of the box dropping and opening

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

Section 1 is not designed for exploration but for teaching, whereas sections 2 and 3 are designed for exploration. In section 2, I used a door to lock the progession until the player searches around and finds the switch, I added a hidden cove and an upper platform out of view from the player to give areas for the player to explore and find, as well as making the section very apone allowing the player to easily move around and search. In section 3 I added a scavenger hunt with switches hidden across the area that they have to shoot to again give a sense of exploration for the player.

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Moving Platforms

![Moving platforms storyboard](DocImages/2.1.MovingPlatforms.jpg)

### 2.2. Spikes

![Spikes storyboard](DocImages/2.2.Spikes.jpg)

### 2.3. Health Pickups

![Health pickup storyboard](DocImages/2.3.HealthPickups.jpg)

### 2.4. Weapon Pickup (Staff)

![Weapon pickup (staff) storyboard](DocImages/2.4.WeaponPickup(Staff).jpg)

### 2.5. Checkpoints and Acid

![Checkpoints and acid storyboard](DocImages/2.5.Checkpoints+Acid.jpg)

### 2.6. Passthrough Platforms

![Passthrough platforms storyboard](DocImages/2.6.PassthroughPlatforms.jpg)

### 2.7. Keys

![Keys storyboard](DocImages/2.7.Keys.jpg)

### 2.8. Chompers

![Chompers storyboard](DocImages/2.8.Chompers.jpg)

### 2.9. Spitters

![Spitters storyboard](DocImages/2.9.Spitters.jpg)

### 2.10. Weapon Pickup (Gun)

![Weapon pickup (gun) storyboard](DocImages/2.10.WeaponPickup(Gun).jpg)

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


