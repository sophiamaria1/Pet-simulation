Pet Simulation 🐾

This project is a simple JavaScript program that simulates a day in the life of a virtual pet.


#Overview

The program tracks a pet’s basic stats and simulates actions that change its state throughout the day. 🐾

Pet Stats

The pet has four main attributes:

Name – the pet’s name

Energy – how energetic the pet is

Hunger – how hungry the pet is (higher number = more hungry)

Happiness – how happy the pet is



#Actions

The program includes several functions that simulate daily activities:

feed() – Decreases hunger and increases energy. If the pet isn’t hungry, it may refuse to eat.

play() – Increases happiness but decreases energy and increases hunger. The pet cannot play if it is too tired.

sleep() – Greatly increases energy and slightly increases hunger.

checkStatus() – Displays the pet’s current stats in the console.




How to Run

Open the project in your terminal.

Run the JavaScript file:

node index.js

The pet’s activities and updated stats will be displayed in the console.
