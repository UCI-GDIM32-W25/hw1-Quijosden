[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity

Put your notes from the W1L2 (Thurs, Jan 9) in-class activity here.

PROJECT BREAKDOWN:

Text UI: 
	-Text element to keep track of score
		-increases count when a player plants a plant
		-should never exceed the players starting amount of seeds
	-Text element to keep track of how many seeds the player has left
		-decreases when the player plants a plant
		-should never be less than 0
Player:
	-Movement:
		-WASD to move in the respective direction 
	-Planting:
		-Press SPACE and as long as the player has seeds left, they plant a plant, instantiating a plant prefab there
		-Decreases current seed count 
		-Increases score 
Plant: 
	-Has a sprite renderer but is otherwise empty 
	-Has no action, just displays on screen

## Devlog
Prompt: Include the HW1 break-down exercise you wrote during the Week 1 - Lecture 2 (Jan 9) in-class activity (above). If you did not attend and perform this activity, review the lecture slides and write your own plan for how you believe HW1 should be built. If your initially proposed plan turned out significantly different than the activity answers given by Prof Reid, you may want to note what was different. Then, write about how the plan you wrote in the break-down connects to the code you wrote. Cite specific class names and method names in the code and GameObjects in your Unity Scene.


Write your Devlog here!

The project was pretty simple the first thing I did was make the plant prefab and get the player movement done. I upped the speed a bit to make it feel better as well. Then I just added in a GetKeyDown check in the update function to check when the player pressed space and then instantiated a plant in that location. Then I just implemented the UpdateSeeds() method in the UI script and the project was pretty much done. I liked the plant sprite with the fruit hanging off of it a bit more than the one used in the example personally so I used that one but other than that it should be mostly the same as the example. 


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
