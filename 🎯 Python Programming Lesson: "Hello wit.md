🎯 Python Programming Lesson: "Hello with Emojis!" 

Target Audience: Beginners (Ages 10+, or anyone new to Python)
Duration: 45–60 minutes
Goal: Create an interactive emoji-based Python program using variables, functions, input, random numbers, and dates. 


📚 Lesson Overview 

In this fun and interactive project, students will: 

    Learn how to use print() and f-strings
    Work with variables and emojis
    Perform basic math
    Use the datetime and random modules
    Define and call functions
    Take user input
    Combine everything into a dice-rolling program with emoji effects!
     

All using a simple online Python editor like the Raspberry Pi Editor . 


Open the Hello World Starter Project:
🔗 https://editor.raspberrypi.org/en/projects/hello-world-starter 




📘 Step-by-Step Teaching Guide 
 
✅ Step 1: What You Will Make 

🎯 Objective: Introduce the goal of the lesson. 

🗣️ Say to students: 

    "Today, we’re going to make a fun, interactive program that says Hello, uses emojis, does math, shows the time, and even rolls a virtual dice! We’ll learn real Python skills along the way." 
     

💡 Teaching Tip: Show a quick demo of the final program if possible (run it once yourself first). 

✅ Step 2: Print 'Hello' with Emojis 

🎯 Objective: Use print() and f-strings to display text and emojis. 
📝 Concepts Covered: 

    print() function
    Variables
    f-strings (f'...')
    Using emojis stored in variables
     

The starter project already includes some emoji variables: 

``python
    world = '🌍🌎🌏'
    python = '🐍'
    fire = '🔥'
``

💻 Code Snippet 1: Print Hello + World Emoji 

👉 Ask students to type this under the comment: 

``python
# Put code to run under here.
print(f'Hello {world}')
``

💻 Code Snippet 2: Add a Second Line 

Add a welcome message with the Python snake emoji: 

print(f'Hello {world}')
print(f'Welcome to {python}')


💡 Teaching Tip: Explain that: 

    f'...' allows us to insert variables inside curly braces {}.
    Spaces inside the string matter — adding a space after Hello makes it look better.
     

 
 ✅ Step 3: Do Math and Show the Date 

🎯 Objective: Use Python for calculations and display the current date/time. 
📝 Concepts Covered: 

    Arithmetic operators (+, -, *, /, **)
    Using the datetime module
     

💻 Code Snippet 3: Add Math and Date 

Add these lines: 

print(f'{python} is good at maths!')
print(f'3 × 9 = {3 * 9}')
print(f'The date and time is {datetime.now()}')


💡 Teaching Tip: 

    Explain that * means multiplication in code.
    datetime.now() is a function from the datetime module — it's like borrowing a tool.
     

🔧 Note: The datetime module is already imported in the starter code. No need to add import datetime. 



✅ Step 4: Roll a Dice with a Function 

🎯 Objective: Learn how to define and use functions. 
📝 Concepts Covered: 

    Functions (def)
    Indentation (4 spaces)
    Calling functions
    Using the random module
     

💻 Code Snippet 4: Define a Function (Start Simple) 

👉 Under the comment # Function definitions, write: 

def roll_dice():
    print(f'You rolled a 4')

    Then, call the function at the bottom of the code:

    roll_dice()


 Teaching Tip: 

    Explain that a function is a reusable block of code.
    The code inside must be indented (pushed in by 4 spaces).
    You call it by typing its name and ().
     

💻 Code Snippet 5: Use Random Numbers 

Now make the dice roll random using randint() from the random module. 

🔧 random is already imported, so we can use randint(1, 6). 

Update the function: 

def roll_dice():
    print(f'You rolled a {randint(1, 6)}')



💻 Code Snippet 6: Store Roll in a Variable + Show Emojis 

Now store the roll in a variable and print that many fire emojis! 

def roll_dice():
    roll = randint(1, 6)
    print(f'You rolled a {roll} {fire * roll}')


    💡 Teaching Tip: 

    fire * roll means: repeat the 🔥 emoji roll times!
    This only works because fire is a string and roll is a number.
     


profile
Qwen3-235B-A22B-2507 9:29 pm

Absolutely! Based on the content of your uploaded "Hello 🌍🌎🌏.pdf", I’ve created a complete, beginner-friendly Python lesson plan that you can use to teach learners who are partially new to Python. The lesson is structured step-by-step, includes clear explanations, teaching tips, and all necessary code snippets. 
 
🎯 Python Programming Lesson: "Hello with Emojis!" 

Target Audience: Beginners (Ages 10+, or anyone new to Python)
Duration: 45–60 minutes
Goal: Create an interactive emoji-based Python program using variables, functions, input, random numbers, and dates. 
 
📚 Lesson Overview 

In this fun and interactive project, students will: 

    Learn how to use print() and f-strings
    Work with variables and emojis
    Perform basic math
    Use the datetime and random modules
    Define and call functions
    Take user input
    Combine everything into a dice-rolling program with emoji effects!
     

All using a simple online Python editor like the Raspberry Pi Editor . 
 
🧰 Tools Needed 

    A computer with internet access
    Browser (Chrome, Firefox, etc.)
    Open the Hello World Starter Project:
    🔗 https://editor.raspberrypi.org/en/projects/hello-world-starter 
    No installation needed — everything runs in the browser!
     

 
📘 Step-by-Step Teaching Guide 
 
✅ Step 1: What You Will Make 

🎯 Objective: Introduce the goal of the lesson. 

🗣️ Say to students: 

    "Today, we’re going to make a fun, interactive program that says Hello, uses emojis, does math, shows the time, and even rolls a virtual dice! We’ll learn real Python skills along the way." 
     

💡 Teaching Tip: Show a quick demo of the final program if possible (run it once yourself first). 
 
✅ Step 2: Print 'Hello' with Emojis 

🎯 Objective: Use print() and f-strings to display text and emojis. 
📝 Concepts Covered: 

    print() function
    Variables
    f-strings (f'...')
    Using emojis stored in variables
     

The starter project already includes some emoji variables: 
python
 
 
1
2
3
world = '🌍🌎🌏'
python = '🐍'
fire = '🔥'
 
 
💻 Code Snippet 1: Print Hello + World Emoji 

👉 Ask students to type this under the comment: 
python
 
 
1
2
# Put code to run under here.
print(f'Hello {world}')
 
 

✅ Check: When they click Run, it should output: 
 
 
1
Hello 🌍🌎🌏
 
 
💻 Code Snippet 2: Add a Second Line 

Add a welcome message with the Python snake emoji: 
python
 
 
1
2
print(f'Hello {world}')
print(f'Welcome to {python}')
 
 

✅ Output: 
 
 
1
2
Hello 🌍🌎🌏
Welcome to 🐍
 
 

💡 Teaching Tip: Explain that: 

    f'...' allows us to insert variables inside curly braces {}.
    Spaces inside the string matter — adding a space after Hello makes it look better.
     

 
✅ Step 3: Do Math and Show the Date 

🎯 Objective: Use Python for calculations and display the current date/time. 
📝 Concepts Covered: 

    Arithmetic operators (+, -, *, /, **)
    Using the datetime module
     

💻 Code Snippet 3: Add Math and Date 

Add these lines: 
python
 
 
1
2
3
print(f'{python} is good at maths!')
print(f'3 × 9 = {3 * 9}')
print(f'The date and time is {datetime.now()}')
 
 

✅ Output example: 
 
 
1
2
3
🐍 is good at maths!
3 × 9 = 27
The date and time is 2025-04-05 10:30:15.123456
 
 

💡 Teaching Tip: 

    Explain that * means multiplication in code.
    datetime.now() is a function from the datetime module — it's like borrowing a tool.
     

🔧 Note: The datetime module is already imported in the starter code. No need to add import datetime. 
 
✅ Step 4: Roll a Dice with a Function 

🎯 Objective: Learn how to define and use functions. 
📝 Concepts Covered: 

    Functions (def)
    Indentation (4 spaces)
    Calling functions
    Using the random module
     

💻 Code Snippet 4: Define a Function (Start Simple) 

👉 Under the comment # Function definitions, write: 
python
 
 
1
2
⌄
def roll_dice():
    print(f'You rolled a 4')
 
 

Then, call the function at the bottom of the code: 
python
 
 
1
roll_dice()
 
 

✅ Output: 
 
 
1
You rolled a 4
 
 

💡 Teaching Tip: 

    Explain that a function is a reusable block of code.
    The code inside must be indented (pushed in by 4 spaces).
    You call it by typing its name and ().
     

💻 Code Snippet 5: Use Random Numbers 

Now make the dice roll random using randint() from the random module. 

🔧 random is already imported, so we can use randint(1, 6). 

Update the function: 
python
 
 
1
2
⌄
def roll_dice():
    print(f'You rolled a {randint(1, 6)}')
 
 

✅ Test: Run multiple times — the number should change! 
💻 Code Snippet 6: Store Roll in a Variable + Show Emojis 

Now store the roll in a variable and print that many fire emojis! 
python
 
 
1
2
3
⌄
def roll_dice():
    roll = randint(1, 6)
    print(f'You rolled a {roll} {fire * roll}')
 
 

✅ Example Output: 
 
 
1
You rolled a 5 🔥🔥🔥🔥🔥
 
 

💡 Teaching Tip: 

    fire * roll means: repeat the 🔥 emoji roll times!
    This only works because fire is a string and roll is a number.
     

 
✅ Step 5: Get User Input 

🎯 Objective: Make the program interactive by asking the user a question. 
📝 Concepts Covered: 

    input() function
    Converting strings to integers (int())
     

💻 Code Snippet 7: Ask for Dice Sides 

Update the roll_dice() function: 

def roll_dice():
    max = input('How many sides on your dice?: ')
    print(f'That is a D{max}')
    roll = randint(1, int(max))
    print(f'You rolled a {roll} {fire * roll}')

    💡 Teaching Tip: 

    input() always returns a string, even if you type a number.
    We use int(max) to convert the string "20" into the number 20.
    If the user types letters, the program will crash — that’s okay for now (advanced error handling can come later!).
     

 ✅ Challenge Activity: Add Your Own Lines! 

🎯 Objective: Encourage creativity and reinforce learning. 

🗣️ Say to students: 

    "Now it’s your turn to make the program your own! Add some fun lines using print, emojis, and variables." 
     

💬 Suggested Prompts:     

print(f'I love coding! {python} 🎉')
print(f'Python makes me happy 😊')
print(f'I would like to make a game with {python} 🎮')
print(f'Today is a great day! {world}')



Here is the full code students should end up with:

# Import statements (already in starter code)
from datetime import datetime
from random import randint

# Emoji variables (already defined)
world = '🌍🌎🌏'
python = '🐍'
fire = '🔥'

# Function definitions
def roll_dice():
    max = input('How many sides on your dice?: ')
    print(f'That is a D{max}')
    roll = randint(1, int(max))
    print(f'You rolled a {roll} {fire * roll}')

# Put code to run under here
print(f'Hello {world}')
print(f'Welcome to {python}')
print(f'{python} is good at maths!')
print(f'3 × 9 = {3 * 9}')
print(f'The date and time is {datetime.now()}')

roll_dice()

# Challenge: Add your own lines!
print(f'I love coding! {python} 🎉')
print(f'Python makes me happy 😊')



🧠 Key Concepts Summary (Whiteboard Notes)


🧪 Testing & Debugging Tips for Students 

🔧 Common Errors & Fixes: 

    ❌ SyntaxError: invalid syntax → Check quotes, parentheses, colons
    ❌ NameError: name 'fire' is not defined → Make sure emoji variables are not deleted
    ❌ invalid literal for int() → User typed letters instead of a number
    ❌ Nothing happens → Did you call the function? (e.g., roll_dice())
     

✅ Best Practice: Run the code after every change to catch errors early! 