PyBlocks - Block-Based Python Editor User Manual
🚀 Getting Started
Launching the Editor
Run the program - Double-click PyBlocks.exe or run python pyblocks.py

You'll see three main areas:

Left: Block Palette (categories of blocks)

Center: Workspace (where you build programs)

Right: Code Preview & Console

Creating Your First Program
Click "New Script" in the palette to create a workspace

Drag blocks from the palette to the workspace

Connect blocks by placing them top-to-bottom

Click "Run Script" to see your program run

📦 Block Categories
🎯 Events
When Started - Program begins here

🎮 Control
If - Conditional execution

Set condition to things like x > 5 or name == "Alice"

Else - Alternative path for If blocks

Elif - Additional conditions

While - Repeat while condition is true

For - Loop through sequences

var: Loop variable (e.g., i)

iterable: What to loop through (e.g., range(5))

🔢 Variables
Set Variable - Create or change variables

var: Variable name (e.g., score)

value: What to store (e.g., 10 or score + 1)

➕ Math
Add - result = a + b

Subtract - result = a - b

Multiply - result = a * b

Divide - result = a / b

📝 Text
Print - Display text in console

value: What to print (e.g., "Hello World" or name)

Input - Get user input

var: Where to store input (e.g., name)

prompt: Question to ask user (e.g., "Enter your name: ")

📋 Lists
Create List - Make a new list

var: List name (e.g., fruits)

items: Comma-separated values (e.g., "apple", "banana", "cherry")

Add to List - Append item to existing list

list: List name (e.g., fruits)

value: Item to add (e.g., "orange")

🖥️ GUI (Tkinter)
Create Window - Make a GUI window

title: Window title

width: Window width in pixels

height: Window height in pixels

Create Label - Add text to window

text: Label text

Create Button - Add clickable button

text: Button text

🔧 Functions
Define Function - Create reusable code

name: Function name (e.g., calculate_area)

params: Parameters (e.g., width, height)

Return - Send value back from function

value: What to return

📌 Other
Comment - Add notes to your code

text: Your comment

Import - Use external modules

module: Module name (e.g., math, random)

🛠️ How to Use Blocks
Adding Blocks
Click any block in the palette to add it to workspace

Blocks appear at random positions - drag to organize them

Organizing Blocks
Drag blocks to move them around

Top-to-bottom order determines execution order

Indentation matters - place blocks under If/While/For for proper structure

Editing Block Values
Click text fields in blocks to edit values

Use quotes for text: "Hello" not Hello

Use variables without quotes: score not "score"

Deleting Blocks
Right-click any block to delete it

Deleted blocks are removed immediately

💡 Example Projects
1. Simple Calculator
text
Print: "Enter first number: "
Input: num1, ''
Print: "Enter second number: "
Input: num2, ''
Set Variable: result = num1 + num2
Print: f"The sum is: {result}"
2. Number Guessing Game
text
Set Variable: secret = 7
Set Variable: guess = 0
While: guess != secret
    Print: "Guess a number: "
    Input: guess, ''
    If: guess < secret
        Print: "Too low!"
    Else If: guess > secret
        Print: "Too high!"
Print: "You got it!"
3. Simple GUI App
text
Create Window: 'My App', 300, 200
Create Label: 'Welcome to PyBlocks!'
Create Button: 'Click Me'
🎯 Tips & Best Practices
Programming Basics
Variables: Use descriptive names (player_score not x)

Conditions: Use comparisons (==, !=, >, <, >=, <=)

Strings: Always use quotes around text

Indentation: Keep related blocks aligned vertically

Block Organization
Start simple - test small programs first

Use comments to explain what your code does

Group related blocks together visually

Test frequently - run your program often

Common Patterns
Input → Process → Output: Get data, work with it, show results

Loops: Use While for unknown repetitions, For for known counts

Conditionals: Use If/Else for decision making

🔧 Advanced Features
Custom Blocks
Click "Add Custom Block"

Enter block name and Python code template

Custom blocks appear in palette after restart

Projects
Save Project: Save all your blocks to a .json file

Load Project: Open saved projects to continue working

Multiple Scripts: Use tabs to work on different programs

Running Programs
Run Script: Execute in console (good for learning)

Run GUI: Execute as Tkinter app (for GUI programs)

🐛 Troubleshooting
Common Issues
"NameError": Variable used before being created - add Set Variable block

"SyntaxError": Check quotes around text and proper comparisons

Blocks not connecting: Ensure proper vertical alignment

Program does nothing: Check if you have a Print block to see output

Debugging Tips
Add Print blocks to see what's happening

Check the Code Preview to see generated Python

Look at Console Output for error messages

Simplify - remove blocks until it works, then add back

🎓 Learning Path
Beginner (First Hour)
Create a program that prints "Hello World"

Make a program that asks for your name and says hello

Create a simple calculator that adds two numbers

Intermediate (First Day)
Build a number guessing game

Create a to-do list manager

Make a simple drawing app with Tkinter

Advanced (First Week)
Build a calculator with GUI

Create a text-based adventure game

Develop a simple database application

Happy Coding! 🚀 Start with simple programs and gradually build more complex ones. The visual blocks make it easy to understand programming concepts!
