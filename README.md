# Lab08ColorsAndTexts
Functions Review Warmup Lab

# Attached is some code
Review the code provided. Answer the following questions by adding comments to your code! You are free to talk with other students, and seek better understanding to these questions. See below for reminders on types, variables, and input

# Step One
1. Look at green(str). Why is there a +1 next to the str.index(',')? Why is there NOT a -1 next to the str.index('.')?
2. Look at blue(str) and red(str). Note that there is no end value for blue and no start value for red. What does this do?
3. Find the comment in main. What happens if we replace these three if statements with if, elif, and else? How does this change what the code does?
4. For the for-loop, what path must that first if statement follow and what functions does it reach?
5. How does textToSpeech(txtlst) know what to translate the texts to?

# Step Two: Coding: tritanopiaSee(color)
Find the function tritanopiaSee(color). As a reminder, a function is a way to break up code into repeatable bits to be reused.

Write the code for tritanopiaSee(color) so that if the blue for the color is greater than 0, the red for the color is greater than 230, and the green for the color is greater than 230, it returns true. Otherwise, it should return false.

Ex: for
tritanopiaSee("231,240.2") the function would return true
tritanopiaSee("3,240.2") the function would return false

# Step 3: Test tritanopiaSee(color)
How do you test code? You simply add the lines to your python file (in the future, you will have test lines in separate files).

As such, we would recommend adding the following just above def main().

print("TESTING", tritanopiaSee("231,240.2"))

print("TESTING", tritanopiaSee("3,240.2"))

Also add your own tests!

# Submitting the Assignment
Make sure to submit the assignment for grading! If you haven't clicked through the canvas link in a while, we would suggest clicking through it again before submitting.

# Reminder on Substrings
Substrings are a way to cut apart strings or extract specific parts of them. We can do this with hardset numbers or with indexes.
# Harset Numbers
    These work best when working with something of a set size
      Ex: str = "Howdy, y'all" str[0:5] = "Howdy"
# Indexes
    These work best if you don't know how long a section might be
      Ex: str = "Howdy, y'all" str[0:str.index(",")] = "Howdy"
Remember that for both of these, you want your end value to be one more than where you want the end value to actually land because it is not right hand inclusive,
like ranges.

# Reminder on Dictionaries
Dictionaries work like real dictionaries. They have words (keys) and definitions (values). When reading a dictionary, you will see these two separated by a :. To access a value using the key, you use dictionaryName\[key]. This works the same way as finding a word in the dicitonary and using that to get the definition. Like a dictionary, it is also a lot more complicated to use your definition (or value) to find the word (or key).

