
# Simulation of an AI

## 2019
The goal of the project was to create an AI capable of fighting against a player in a turn-based fight.
I start the project in 2019 when i learn Java and processing, at this time it was a small concept with two basic screen and no AI only a big list of random behavior. 

The first goal was to select the correct Swords and Shields based on winning rate. So two AI was playing against each other and the winner go to the next generation. 

On each turn they can, 
- Attack 
- Dodge 
- Block
- Do nothing

Agility is calculated with this formula : 100 - {Sword's cost} - {Shield's cost}

You have more chance to dodge an attack if your agility is grater than your opponent.

 <img src="https://github.com/velkyos/velkyos/blob/master/images/IA_FIGHT_SCREEN_V1.PNG"/>

 <img src="https://github.com/velkyos/velkyos/blob/master/images/IA_GENERATION_V1.PNG"/>

 The project stop here due to my lack of motivation and my poor knowledge of AI.

## 2021

During lockdown, i took time after school to learn more about AI in general. I learn about Agent, Neurons Network and how they can learn.

So I start working again on the project but this time in C# with the help of the Unity Engine.

<img src="https://github.com/velkyos/velkyos/blob/master/images/IA_FIGHT_SCREEN.PNG"/>

 I start the project from scratch based on new rules.


 The goal was that each Agent will fight all the other ones during a generation. 
 My plan was to have an AI that learn quicker because of diversity.

The agility was pretty much the same concept, the weight of the armor and the sword reduce the agility of the Agent.
Stamina and Mana decrease based on : 
- the weight of the sword for the Stamina
- Cost of the spell for the Mana

Now they can do 5 things instead of 4 with the addition of potion.

At this stage the Ai is learning and we can see an improvement generation after generation, my only problem is the game balance and the cost function of agents.

It's a big struggle to find the right number so that my agents develop a good behavior, i don't find exploit in my game.
