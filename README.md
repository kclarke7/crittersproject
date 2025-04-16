# Critters Project 
A Python simulation of simple AI-driven creatures called Critters, each with unique behaviors and interactions.
This project features a GUI interface using tkinter, where different critter subclasses(like cheetahs)
move, eat, and battle according to their own rules.

🛠️ Built as part of a university project to demonstrate object-oriented programming, inheritance, and basic AI logic.

## Features
   - 🧠 Custom AI Logic for each critter type
   - 🐻 Bear Critter that moves in a zigzag pattern and always eats
   - 🐆 Cheetah Critter that moves three steps in one (random) direction, then repeats
   and that pounces when it has eaten or scratches otherwise
   - 🦁 Lion Critter that changes direction every 5 steps, roars at bears or pounces
   at the other critters, and eats after it has fought
   - 🕺 Torero Critter follows a patterned path using a predefined list tor_move,
   only eats if there are no neighbors and uses different attack strategies based
   on opponent type.
   - 🎨 Color-coded critters (e.g., grizzly vs. polar bear)
   - 💥 Fight mechanics and behavior customization
   - 🖼️ Graphical user interface using tkinter
   - 🔁 Easily extendable for new critter types

## Photo of the Critters in Action!

<img width="1440" alt="Screen Shot 2025-04-16 at 12 58 12 PM" src="https://github.com/user-attachments/assets/5b2808b5-d9c2-4115-8abc-34b615b7073c" />


## Tech Stack
- Python 3
- tkinter (for GUI)
- enum (for defining directions, attacks, etc.)
- OOP principles: inheritance, polymorphism, and encapsulation

## How to Run
1. Clone the repository:
   git clone https://github.com/kclarke7/crittersproject.git
   cd critters

2. Run the simulation:

python main.py
⚠️ Make sure you have Python 3 installed.

## Author(s)
Kyla Clarke — kylaclarke0405@gmail.com

## Future Improvements
- Add more critter types (e.g., Turtle, Snake)
- Introduce obstacle-based maps
- Allow user-defined critters via GUI
- Update Torero critter strategy to improve survival rate
  and increase opportuity to win.

## License
This project was built as an academic assignment. Please contact the authors if you'd like to reuse or extend it.

## Contact
Feel free to connect with me on LinkedIn or email me if you'd like to chat more about this project or OOP in Python.
Let me know if you want this in a .md file format or pushed to a GitHub repo!
