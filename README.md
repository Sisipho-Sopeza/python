# python
# How computer works
Computers store files and data in memory like a grid. Each file has a name and info about it. To find and use files, computers use addresses called pointers.
When we write a computer program, we're using the computer's memory. Programs create variables, which are like mini files with names and addresses in memory. For example, if we have a program like A = 2, B = 3, C = A + B, the computer stores these values in memory and calculates C.
If we have a list of numbers in Python, like [1, 2, 3, 4, 5], and we assign it to another variable B, both A and B point to the same memory location. So, if we change A, it also changes B.
Understanding how computers manage memory is important when writing programs and working with data. When we assign one variable to another, we're not making a copy; we're just pointing them to the same place in memory. So, changing one changes the other.
# Zen of python
Python is a popular programming language known for its elegance and simplicity. Unlike some other languages like JavaScript, Python is consistent and easy to use. It's not just for beginners; it's used in building complex systems too. 
There's a special message in Python called "import this" that highlights its philosophy. To see it, you can open Python in a terminal and type "import this". It prints out a set of principles like "Beautiful is better than ugly" and "Simple is better than complex." It's a neat way to understand Python's approach to coding.

# Writting a python program
To write your first Python program, you'll need a text editor like Visual Studio Code or Notepad++. Start by creating a new file called hello.py. In that file, type a single line of code: print('Hello, World!'). This line will display "Hello, World!" when run.
You can also add comments using the # symbol to explain what the code does. Comments are ignored by the computer when running the program.
Once you've added the code and comments, save the file. Then, open a terminal or command prompt and navigate to the directory where the file is saved using the cd command.
To run the program, type python hello.py in the terminal and hit Enter. You'll see "Hello, World!" printed on the screen.

# Jupyter notebooks
Jupyter Notebooks are an essential tool we'll use a lot in this course. They're part of Project Jupyter, which creates Python tools for programming and data science. When you start a Jupyter Notebook from the command line, you're essentially launching a web application server on your computer. It's super quick and opens in your web browser.
Once you're in, you'll see a list of files. The ones ending in .ipynb are Jupyter notebooks. These are great for sharing code, findings, and creating charts and graphs.
To create or open a notebook, click "new" and select "Python 3." Notebooks are handy for experimenting, making reports with code, or teaching Python effectively. Plus, you can export them in different formats.
In a notebook, you can create new cells by pressing shift + enter. To delete a cell, press dd. Enter Python code by clicking inside a cell, type, and then press shift + enter to run it. You can add Markdown cells for text and titles by pressing M. These notebooks are widely used and supported.
If you prefer, you can also edit notebooks in an IDE like Visual Studio Code. You'll have the same features and shortcuts there. If you have trouble installing Jupyter from the command line, try using Visual Studio.
There are lots of shortcuts and features to learn, so take it step by step. Start with shift + enter and go from there!

# Vriables and types
In Python, the basic building block of a program is a variable, which holds a value. We use the equal sign (=) to assign values to variables. In Jupyter Notebooks, you can run cells with Shift + Enter and add new cells by clicking outside and typing 'a'. 
Variables in Python can have names consisting of letters, numbers, and underscores, but they can't start with a number. It's common to start variable names with lowercase letters.
Python has different types of variables:
- Integers: whole numbers
- Floats: decimal numbers
- Complex numbers: for complex math
- Strings: sequences of characters
- Booleans: true or false values
You can combine strings with the plus sign (+) to concatenate them, but you can't mix strings and numbers with it. Error messages in Python can give helpful hints when something goes wrong.

# Data stracture
In Python, data structures help organize multiple values in one variable. The first one we'll cover is a list, which can hold any data type, including lists within lists. You can find a list's length using the length function. 
Another structure is a set, similar to a list but with only unique elements, and it's declared with curly braces. Sets don't care about the order of elements.
Then, there are tuples, much like lists but unchangeable once created. They're handy for storing data efficiently, like XY coordinates.
Lastly, there's a dictionary, which stores key-value pairs, like words and their meanings. Dictionaries are declared with curly braces and accessed using keys.

# operators
Operators in Python are like instructions that work on variables and values. They help manipulate and do things with data. The most common ones are arithmetic operators, which do math stuff.
For example, the addition operator adds numbers, the multiplication one multiplies them, and the exponent one raises a number to a power. Division uses the forward slash and gives a floating-point number, even if the answer is whole.
Then, there's the modulus operator, which finds the remainder after division. It's handy in programming for various tasks.
You can also use operators with strings. Plus sign joins strings together, and asterisk repeats a string.
Python has more operators like comparison, logical, identity, and membership ones. Comparison operators check if values are equal, greater than, or less than each other. Logical ones work with true or false values, and membership ones check if something's in a sequence.
These operators let you do lots of things in Python.

# Control flow
In programming, control flow helps decide what code to run based on conditions. The "if" statement is a key part of this. If a condition is true, the code inside it runs. You write it like this in Python: "if a: print('It is true')." If the condition isn't true, you can add an "else" statement with code that runs instead.
Indentation, or spacing, is crucial in Python. It shows which code belongs to which part of the program. 
For loops are handy for going through lists or other collections. You write them like this: "for item in my_list: print(item)." The "item" variable represents each thing in the list.
While loops are similar, but they keep running until a condition is false. You write them like this: "a = 0, while a < 5: print(a), a = a + 1." Just be careful to make sure the condition eventually becomes false, or the loop won't stop.

# Functions
Functions in Python are like machines that take inputs and give outputs, just like a toaster turning bread into toast. They can work even if the input isn't exactly what they're designed for.
To define a function in Python, you use the "def" keyword followed by the function name and any inputs in parentheses. The code inside the function, indented, does the job, and "return" specifies the output. Functions can take one or more inputs and may or may not give back a result.
For example, a function might change a variable without giving anything back. The print function is one that doesn't return anything but just shows output on the screen. If a function doesn't explicitly return anything, Python uses the special keyword "None" to show that.

# Classes and objects
Imagine you're setting up a kitchen. Instead of just focusing on one appliance like a toaster, you want to have a fully equipped kitchen with a toaster, microwave, dishwasher, and coffee maker. Each appliance has its own settings and functions.
For example, the toaster might have a knob, the microwave a power setting, and the dishwasher different modes. If you're planning to create multiple kitchens with different sets of appliances, or even whole houses with various rooms, writing lots of separate functions and variables could get messy.
To manage this complexity, programmers use a tool called a class in Python. It helps organize related functions and attributes. 
Let's say we want to create a class for a Dog. We'd use an uppercase letter for the class name and define all its functions and attributes inside. 
We typically start by creating a special function called "init", which is called every time we create a new dog. It takes in a variable called "self" that refers to the specific dog instance.
Then, we can define attributes like legs and name, and functions like "speak" which makes the dog bark. We access these attributes and functions using the "self" variable.
To use the class, we create a new dog instance by calling the class name, passing any needed variables like the dog's name. We can make multiple dogs with different names, and each one gets all the functions and attributes of the Dog class.
These instances of the class are called objects, and the variables inside them are attributes, while the functions are methods. It's like having a blueprint for creating objects with specific behaviors and properties.
This is just an overview of object-oriented programming, which is a powerful and useful concept.

# Ints and Floats
Let's talk about ints and floats, the basic number types in Python. We'll see how they work together, how to switch between them, and some things to watch out for.
When we divide an int, like 20, by another int, like 4, we get a float, like 5.0. Python does this automatically to handle non-whole numbers. Mixing a float with an int, or using math operations with both, also gives us a float.
If we have a float, like 256.0, and want to turn it back into an int, we use the int class, not a function. This is called casting. Casting is simple, but it's important to remember that Python doesn't round when converting floats to ints; it just chops off the decimal part. If we want to round to the nearest int, we can use the round function. We can also specify how many decimal places to round to, like turning 4.67 into 5.
One thing to be careful about with floats is that they can have rounding errors. For example, 1.2 minus 1.0 should be 0.2, but in Python, it might be a tiny bit off. This happens because floats are stored as ones and zeros in memory, and Python sometimes makes approximations due to limited memory. Using the round function can help with this issue.
It's especially important to be cautious with floats when dealing with money, where exact decimal places matter. We'll talk more about handling money in the next section.

# Altenative number types
First, let's talk about the int class in Python. If you give it a number as a string, like "100", it turns it into an integer, like 100. But here's the cool part: if you give it a second argument as a number, it'll convert the first argument from that base to base 10. For example, "100" in base 2 is 4 in base 10.
However, the first argument always has to be a string, even if you're converting it from a different base. This is because there might be non-numeric characters in the string that are valid in some bases, like "1ab" in base 16. But "1ab" isn't an integer, of course.
Next, Python has another number class called decimal. This helps deal with some of the issues we saw with floats in the previous section. Floats are great, but they can have errors, especially with money. To use the decimal module, you import the decimal class and the getcontext function at the top of your code. The getcontext function gets a context object that holds settings for using the decimal class. You can change these settings, like the precision.
With the decimal class, you can make a decimal object with a number value. For example, dividing decimal 1 by decimal 3 gives 0.3333 with four decimal places. You can also give it a float, but be careful: it'll try to exactly copy the float, which might lead to errors. In those cases, it's better to give the float as a string.
There are lots of ways to represent numbers with the decimal class, so check the docs for more info.
Do you always have to use the decimal class instead of floats? Not necessarily. Always round properly before showing values to users, and watch out for very small or very large numbers. For most situations, floats work fine. So instead of showing a result like 1.2 minus 1.0, it's better to round it and then show it.

# Booleans
We've touched on Booleans before, but there's more to them than just true and false. As programmers, we use them a lot, and sometimes it's tricky to get them right. Let's break it down.
First, let's talk about casting. In Python, it's easy: 1 becomes true, and 0 becomes false. Basically, anything except 0 is true. So -1 and even imaginary numbers like 1 are true, but 0 and imaginary 0 are false.
What about strings? Well, "true" is true, naturally, and any non-empty string is also true. Even the string "false" is true. The only false string is an empty one, but watch out for accidental spaces.
We can also cast data structures like lists and dictionaries. An empty one is false, but if there's anything inside, it's true. When Python gets a non-value from a function, it's cast to false.
Understanding boolean casting is important because we often use booleans in if statements or loops. For instance, we might cast a list to boolean to check if it has any values.
When writing boolean statements, be careful about the logic. Python evaluates them from left to right. So if we're deciding whether to go for a walk based on the weather and whether we have an umbrella, we might write "if not have an umbrella or weather is nice, go for a walk; else, stay inside." But we need to use parentheses or "and" to make sure Python evaluates it correctly.
So even though Booleans might seem simple, it's vital to be cautious when writing boolean statements. Always think about how Python is evaluating each part and check your logic carefully.

# Strings
Python does a lot with strings, whether it's parsing them for data or displaying information to users. Fortunately, Python offers many tools for working with strings, and one of the most useful is slicing.
Slicing means taking part of a string and returning it. For example, if we have the string "My name is Iron-Man," we can get the first character with name[0] (remember, programmers start counting from zero). To get the first seven characters, we use name[0:7], or simply name[:7]. To get everything from the 11th character to the end, it's name[11:].
The slicing syntax works the same for lists as it does for strings. So if we have a list like [1, 2, 3, 4, 5], we can slice it with my_list[2:4].
Python offers a few ways to create strings, including concatenation and f-strings. F-strings are great because they let us insert variables or expressions directly into a string. We can also do rounding and number formatting with f-strings. Before f-strings, the format function was used.
Python also allows for multi-line strings using triple quotes. If we need to include literal triple quotes in the string, we can escape them with a backslash.
There are many more string functions and methods in Python.

# Bytes
The Python byte object isn't something you'll use every day, but it's essential behind the scenes in programs. It's raw data passed around, rarely modified directly. Computers store data as ones and zeros, and Python knows what type it is when it loads that data—string, int, class, etc. But sometimes, you just want raw data, like a sequence of ones and zeros. That's where the bytes object comes in. It's just data, and Python doesn't need to know anything else about it. Bytes are commonly used for streaming files or transmitting text without knowing the encoding.
To recognize a bytes object, look for a 'b' in front of it when printed out. Creating an empty bytes object is done with /x followed by two hexadecimal numbers. Each byte has eight bits. To create a bytes object with data, like an emoji, you need to specify the type, like utf-8. Then Python can represent the data correctly. You can use the decode function to turn a bytes object back into a string.
Bytes objects are immutable, like tuples. But if you need to modify the data, you can use a byte array. You can treat a byte array like a string and change specific byte values using slice notation. The int library helps convert hexadecimal values back to bytes. And that's the basics of finding, using, and modifying bytes in Python.

# Lists
Lists in Python work similarly to strings and share the same slicing syntax. Slicing helps extract specific portions of a list or string, and you can control the step size as well. The `range` function generates longer lists, which can also be sliced. Negative values can be used to step backward through the list. These operations allow you to extract data from lists or strings one value at a time.
To modify lists, Python offers various methods. You can add an item to the end of a list using the `append()` method. For example, if you have a list called `myList` with values 1, 2, 3, 4, you can append the value 5 to it by typing `myList.append(5)`.
To insert an item at a specific position in the list, you can use the `insert()` method. For instance, if you want to insert the value 10 at position 3 in `myList`, you can type `myList.insert(3, 10)`.
There are two main ways to remove items from a list. The `remove()` method removes an item based on its value, not its index. For example, to remove the value 5 from `myList`, you can type `myList.remove(5)`.
The `pop()` method removes and returns the item at the end of the list. For example, typing `myList.pop()` removes the last item from `myList`.
You can use a loop with `pop()` to remove all items from the list. For example, a `while` loop with the condition `while len(myList) > 0:` can be used to pop items until the list is empty.
When you assign a list to a variable, the variable stores a reference to the list, not a copy. This means changes to the list through one variable affect other variables referencing the same list. To make a copy of a list, you can use the `copy()` method.
Lists are essential and powerful data structures in Python. Experimenting with them and trying out the different methods discussed here will help you get comfortable with their functionality.

# Tuples and Sets
Sets and tuples are two data structures worth exploring in Python. 
Sets are defined using curly brackets, like this: {'a', 'b', 'c'}. You can also create a set by passing any iterable object in the constructor of the `set` class. 
One common use of sets is to remove duplicates from a list. For example, you can convert a list with duplicate values into a set and then back into a list to eliminate duplicates.
Sets are not ordered, and you can't access elements using an index or slicing syntax. However, you can add elements to a set using the `add()` function and remove them using `discard()`. You can also check for membership using the `in` operator and find the length of a set using the `len()` function. Additionally, sets have a `pop()` function that removes and returns an arbitrary element.
Now, let's talk about tuples. They're similar to lists but are declared with parentheses instead of square brackets. Tuples are ordered and subscriptable like lists, but they are immutable, meaning you can't modify them. 
One common use case for tuples is when you want to return multiple values from a function. You can separate the values with commas, and Python will automatically create a tuple. You can also unpack the values in a tuple into individual variables using the syntax `A, B, C = myTuple`.
While tuples may not be as flexible as lists, they offer convenience and elegance in certain situations.

# Dictionaries
In Python, two main data structures you'll use are lists and dictionaries, which can handle most of your data needs. Let's dive into dictionaries using an example of an animal dictionary.
You might notice a comma at the end of the last key-value pair; this is called a trailing comma and is good practice.
To access a specific key-value pair, just type the dictionary's name followed by the key in square brackets. To add or update a key-value pair, use the assignment operator.
You can access keys and values using the `.keys()` and `.values()` methods, respectively. The result of `.keys()` is a dict_keys object, which is immutable.
If you're unsure if a key exists, you can use the `get()` function, which takes a key as its first argument and an optional default value as its second argument.
Another common pattern is a dictionary where values are listed. Adding to it is straightforward if the key exists; otherwise, use an if-else statement to handle both cases.
Remember, you can use the `len()` function to get the length of a dictionary.
If you find this code complicated, there's a simpler solution called defaultdict from the collections package.
To create a defaultdict, specify the type of object it should return by default using a callable function. Then, you can add items to it like a regular dictionary.
The cool thing about defaultdict is that it automatically creates a new default value if a key doesn't exist, instead of raising an error like a regular dictionary.
While combining lists and dictionaries is powerful, Python's data structures offer even more!

# List comprehension
List comprehensions in Python are powerful tools that allow you to create lists in a concise and readable way. 
You start by writing an expression inside square brackets, then a for loop, and optionally, a conditional expression. 
For example, you can double each number in a list like this: `[2 * item for item in my_list]`. 
You can also apply filters to the list comprehension to get specific items, like selecting numbers divisible by 10: `[item for item in my_list if item % 10 == 0]`. 
List comprehensions can also work with strings. For instance, you can split a string into words and clean them by removing punctuation and making them lowercase: `[clean_word(word) for word in my_string.split() if len(word) > 2]`. 
Nested list comprehensions are also possible. They allow you to iterate over multiple sequences, like cleaning words in sentences: `[clean_word(word) for sentence in my_string.split('.') for word in sentence.split()]`. 
Overall, list comprehensions are versatile tools that can simplify your code and make it more Pythonic. So, give them a try and have fun experimenting!

# Dictionaries and Comprehensions
In Python, you can use dictionary comprehensions to quickly create dictionaries from other iterable structures, similar to how list comprehensions create lists. 
For example, suppose we have a list of tuples called `animalList`, where each tuple contains a key-value pair. We can create a dictionary from this list using a comprehension like this: 
```python
animals = {key: value for key, value in animalList}
```
This syntax allows us to directly specify the key and value for each item in the list, enclosed in curly braces.
Another way to write this comprehension is by using tuple unpacking. Instead of indexing each tuple element, we can use `key` and `value` directly, like this:
```python
animals = {key: value for key, value in animalList}
```
However, remember that tuple unpacking only works if each tuple has exactly two elements. 
If we want to convert our dictionary back into a list, we can use the `items()` method, which returns a `dict_items` object containing key-value pairs. We can then convert this object into a list. 
But what if we want to change the structure of our list? We can use a list comprehension to create a list of dictionaries with specific keys, like this:
```python
name_value = [{'name': key, 'value': value} for key, value in animals.items()]
```
This demonstrates the flexibility of both dictionary and list comprehensions for manipulating and formatting data in Python.

# If and Else
We'll start with the if and else statements, but we'll also introduce a new one: elif, short for "else if." It helps make code more readable, especially when dealing with multiple conditions.
Now, let's tackle a classic programming problem: FizzBuzz. We want to iterate through numbers from 1 to 100 and print "Fizz" if the number is divisible by 3, "Buzz" if divisible by 5, "FizzBuzz" if divisible by 15, and the number itself otherwise. We can achieve this using if, elif, and else statements.
Sometimes, if-else statements can make code lengthy and hard to read. That's where the ternary operator comes in handy. It allows you to write compact, one-liner conditionals. However, be cautious not to overuse them, as they can make code difficult to understand if used excessively.

# While
When working with a while loop, it's crucial to avoid situations where it runs indefinitely. To control the flow of the loop, you can use two important statements: break and continue.
The break statement helps you exit the loop prematurely. Once encountered, it immediately exits the loop and moves to the next line of code outside the loop.
Conversely, the continue statement allows you to skip certain lines within the loop. When encountered, it skips any code below it and jumps back to the start of the loop for the next iteration.
You might use continue within an if statement to skip specific code under certain conditions. Additionally, restructuring your code with break and continue can enhance readability for other programmers. While not always necessary, knowing when to use them is essential for effective loop control.

# For
The for loop in Python is incredibly straightforward and easy to understand. 
With the for loop, you can iterate through each element in a list, assigning it to a variable like "item" for processing. It's the go-to loop for most tasks in Python because of its simplicity.
Similar to while loops, you can use statements like pass, continue, and break with the for loop. Pass lets you create a placeholder for a loop, continue skips to the next iteration, and break ends the loop prematurely if needed.
A neat trick we haven't discussed yet is the break else statement, handy for finding prime numbers efficiently in Python. This pattern can also be applied to while loops. Understanding these loop statements will help you write clean, Pythonic code.

# WEEK 2
# Anatomy of Functions
Functions are fundamental to programming in Python, providing modular and reusable blocks of code. Let's break down their anatomy and explore their various aspects.
Functions
In Python, functions are defined using the def statement, followed by the function name and parameters in parentheses. These parameters represent the inputs to the function. For example, we can define a function called performOperation that takes num1, num2, and operation as parameters
This function aims to perform basic arithmetic operations like addition or multiplication based on the input parameters. For instance, calling performOperation(2, 3, "sum") should return 5.
However, specifying the operation parameter every time can be repetitive. To address this, we can assign a default value to the operation parameter, such as "sum".
Named Parameters
We can also assign specific values to parameters using keyword arguments. This allows us to specify which parameter is which without relying on their order.
For instance, we can add a message parameter to our function, which defaults to a predefined message. By passing in the message as a keyword argument, we can enhance readability and clarity.
To handle a variable number of positional arguments, we can use *args, a special syntax that gathers all additional arguments into a tuples
This allows us to pass in any number of arguments to the function without explicitly defining them in the parameter list. However, *args only works for positional arguments, not keyword arguments.
Similarly, **kwargs gathers any additional keyword arguments into a dictionary, providing flexibility in handling named parameter
By leveraging *args and **kwargs, we can make our functions more versatile and adaptable to various use cases.
In summary, understanding the anatomy of functions in Python, including parameters, default values, *args, and **kwargs, allows us to write cleaner, more flexible code. With these tools, we can create functions that cater to diverse requirements and facilitate code reuse and readability.

# Vriables and Scopes
Understanding how variables interact within different scopes in Python is crucial for writing efficient and error-free code. Let's simplify this concept without diving too deep into technical jargon.
Function Scope
In Python, functions have their own local scope, meaning variables defined inside a function are accessible only within that function. To see all the variables within a function, we can use the locals() function.
locals()
We can modify a function to perform an operation on given numbers and then print all the local variables using locals(). This gives us insight into what variables are available within the function.
For example, calling performOperation(1, 2, "multiply") will display a dictionary containing all the variables passed to the function.
Global Scope
In addition to local variables, Python also has global variables, which are defined outside any function. We can use the globals() function to access all these variables
Experimenting with globals() reveals various pre-defined variables and those defined in our code. Understanding variable scope helps us grasp which variables are accessible from where in our code.
Global and Local Scope
When we define variables in different scopes, such as inside functions or globally, each scope has its own set of variables. Functions can access both local and global variables, but they can't access variables from other functions' scopes.
We can define variables like message globally and access them from any function. However, attempting to access variables defined in one function from another will result in an error.
Nested Functions
Python allows us to define functions within functions, known as nested functions. These inner functions are only accessible within the outer function. Trying to call them from outside results in a syntax error.
In summary, understanding variable scope—local and global—helps us write clear and organized code. By knowing which variables are accessible from where, we can avoid errors and write more efficient programs.

# Functions as Variables
Variables and functions are both fundamental in Python programming. While variables store data, functions store instructions to be executed. In Python, functions are treated as objects.
Understanding Function Data with "__code__"
The "code" attribute of Python function objects reveals that functions are essentially variables containing data. This attribute displays variable names and the instructions to be executed within the function.
Functions are no different from other variables in Python; they simply hold data associated with their execution instructions.
Text Processing in Python
Text processing often involves applying various operations to manipulate text. By organizing these operations as functions and storing them in a list, we can easily apply them to text in different orders
We can create a list of text processing functions and apply them to a text variable using a loop. This approach provides flexibility in executing text processing tasks.
Lambda Functions
Lambda functions are anonymous functions defined using the lambda keyword. They are useful for creating small, one-time-use functions without assigning them variable names.
Lambda functions are handy when passing functions as arguments to other functions, such as the sorted function. They offer a concise way to write simple functions on-the-fly.

# Anatomy of class
Instance Attributes
Understanding classes can be challenging, but let's break it down. Consider the example of a dog class. This class has two instance attributes: name and legs. Every instance of the dog class, like "Rover," will have these attributes. We can access these attributes using "my_dog.name" and "my_dog.legs
While we can't directly see the value of the legs attribute, it's there in the background. If we try to access "dog.legs," we'll encounter an error because we can't modify the value of legs.
So, is having four legs inherent to being a dog? Even though some dogs have three legs, we can still create a class for them.
Static Attributes
Let's change how the legs attribute is handled. Instead of defining it in the constructor, we'll make it a static variable outside of the constructor. This means all instances of the class will have the same value for legs. You can access static variables directly on the class itself
Remember, static variables can still be changed, so conventionally, an underscore is added before the variable name to indicate that it shouldn't be modified directly. Instead, use a getter method to retrieve its value.
A getter method retrieves the value of the variable. In this case, legs is a static variable, so we can call the method without passing in any attribute.
Classes have their own variable scope rules similar to functions. If legs is not set to something else, it references the class variable. However, the instance variable can also be modified by assigning a new value to it.
When creating a class, consider how it will be used and what's most convenient for the user.

# Instance and static methods
String parsing in Python can be quite enjoyable. Let's create a class called WordSet to demonstrate this. This class will contain a set of words.
Start with an empty set and add text to it by passing in large blocks of text, including punctuation. We'll use a method called add_text for this, which first calls another method called clean_text to remove punctuation and convert everything to lowercase. Then, we'll split the sentence into a list of words using the split function, and add these words to the set. Finally, we'll print the set of words
The clean_text method is a static method because it doesn't belong to any specific instance of the class. On the other hand, add_text is an instance method that belongs to a particular instance of the class. We can also include static variables like replace_puncs to control which punctuations get replaced. We can use either the class name or the class instance to refer to static variables, but this can't be done with instance methods.
To address this issue in Python, we can use a decorator. Decorators are special annotations for function definitions.
By adding the @staticmethod decorator to the function definition, we explicitly state in Python that the function is a static method and should not have "self" passed in as an argument. This allows us to use the function without creating an instance of the class.
After adding the decorator and running the code, the function works as expected. However, using a decorator is not always necessary and depends on personal preference or company style guidelines. As you continue to work with Python, it's recommended to develop your own coding style.

# Inheritance
In Python programming, one class can inherit all the methods and attributes of another class. The original class is called the parent class, while the new class that extends it is known as the child class. This inheritance process happens automatically when the child class is created.
Consider the example: there's a dog class, and we need to create a chihuahua class that inherits from the dog class. To do this, simply write "class Chihuahua(Dog):" and include "pass" for now to create the new class. A chihuahua instance can then be created using all the methods and attributes of the parent dog class.
However, if the child class defines an attribute or method that is the same as the parent class, the child's version will overwrite the parent's version.
In this example, let's overwrite the dog class's "speak" method with a more appropriate "yap, yap, yap" method for chihuahuas. We can also add new methods to the child class, like a "wag tail" method, which the chihuahua can use. This is useful when we need to modify or add to an existing class.
Extending Built-in Classes
We can also extend Python's built-in classes. For instance, creating a new list can be done by instantiating it as "list". Although it looks like a function, "list" is actually a class
Suppose we want a list that ensures all appended items are unique, like a set. We can create our own unique list class by extending the list class. The unique list class inherits from the list class, and we override the append function.
The new function checks if the item is already in the list, and if so, it returns. But remember, we cannot use self.append because it will cause infinite recursion or an endless loop. Instead, we call the original append function in the parent class using the "super" function, which accesses the parent class's instance.
To test the new class, create a new instance of the unique list, append some items to it, and then print the list to see that it only records unique items.
Another common scenario where the "super" function is used is in the constructor. If a new attribute needs to be added to our child class instance, we can use "super" to ensure that the parent constructor is called first before adding our new property. When this new class is initiated, the new property has been added successfully.
Although class extensions may seem complicated at first, they are an elegant and powerful tool that can resolve challenging coding issues.

# Hndling errors and exceptions
In Python, we often encounter issues, like the infamous division by zero error. Sometimes these problems are called errors, and other times they're called exceptions. But don't fret about the terminology; they work similarly. Essentially, all Python errors and exceptions stem from a class called the base exception.
Consider the division by zero error, a type of arithmetic error, which is a type of exception, extending from the base exception class. This class provides useful properties like halting code execution and providing info about why and how the execution halted.
For example, if we try 1/0 within a function called "causeError," and then call this function, we get a stack trace showing where the error occurred. This trace helps debug our program by showing the function call location and where within the function the error was triggered.
In large programs, stack traces can get extensive, so it's crucial to interpret them. Also, writing clear code and organizing your program structure can help avoid excessive debugging.
Exceptions might seem daunting, but they're just classes. We can catch an exception using a try/except statement and obtain an instance of the raised exception
Try/Except
Let's try it out. Add 1/0 in a try block, then catch the exception using except. Print the type of the exception instance. 
This is a zero division error. We've caught it, so it won't crash the program. Remember, exceptions, when handled correctly, are like a secondary layer of code, making your program more robust. Stick with this course to learn how to write code with beautiful errors.

# Managing and Handling Exceptions
Exceptions are nothing to be afraid of, but they do need to be managed. We've previously seen how to handle them using the Try/Except statement. Here, we catch the exception and then return it.
We don't get a stack trace, but we do see the instance of the zero division error returned. There are a few ways to use this Try/Except pattern. For instance, if we don't need the specific instance of the exception and just want to print something, we can catch an exception without using "as e".
Finally
Another useful tool is the "finally" statement. Adding it to a Try/Except block ensures it always executes, as shown below.
The "finally" statement executes no matter what happens inside the try block, even if there's no exception raised. It's often used for tasks like timing how long a function takes to execute.
Catching Exceptions by Type
We can catch exceptions by their specific types. By ordering the "except" statements properly, we ensure the right one is caught. It's good practice to start with the most specific exceptions and end with the most general one
Custom Decorators
Custom decorators can streamline exception handling. We define a function to handle exceptions and then apply it as a decorator to other functions.
The "handleException" function is created to handle various exceptions. We can reuse this decorator for other functions.
Raising Exceptiptons
We can also raise exceptions ourselves using the "raise" statement. This allows us to create functions that raise exceptions based on certain conditions, enhancing the clarity and robustness of our code.

# Working With Custom Exceptions
Creating custom exceptions is simple. You already know how to do it: just define a class that extends the built-in Exception class. Here's an example: 
In this example, the pass statement is used because we don't need to define anything specific for our new CustomException class. It inherits everything it needs from the Exception class it's extending. 
Usually, the name of the custom exception provides enough information about the error. But if you want to provide additional details, you can pass a custom message when raising the exception.
Custom exceptions are typically lightweight classes with minimal attributes and methods. They might have some attributes to organize and present information about the error to the user. For instance, in a web server application, you might define an HttpException class and specific subclasses for different HTTP error codes.
Adding Attributes
Let's enhance our custom exception with some attributes like a status code and a message. We'll also format the string that it passes to the parent exception.
In this example, we create an HttpException class with a status code and a message attribute. Then we define subclasses like NotFoundHttpException and ServerErrorHttpException, each with its own status code and message. When raising these exceptions, the message gets formatted with the status code.
Writing custom exception classes is a good practice for keeping your code organized and easy to understand. These classes serve as documentation for potential errors, their causes, and potential solutions, and help distinguish common expected errors from more severe issues that require developer attention.

# Fundamentals of Threads and Processes
Computers operate on both memory and file storage, which can be likened to short-term and long-term memory, respectively. When we save or load a file, it's like accessing long-term memory, while declaring a variable in a program utilizes short-term memory within the processor. However, these two types of memory are not directly interchangeable.
Each program running on a computer, referred to as a process, is allocated its own segment of memory by the operating system. This segmentation ensures that processes cannot access each other's memory directly. The operating system regulates this access, creating distinct boundaries between processes.
While it's crucial for programmers to understand where data is stored and who can access it, operating systems offer a solution: they allow multiple pieces of code to share memory by placing them within the same process. This enables parallel execution without the need for separate processes; instead, separate threads within the same process can execute simultaneously.
In a single process, multiple threads can run concurrently, executing code in parallel. Unlike the sequential execution we've been doing in Python so far, where each statement is computed one after the other, this chapter introduces the concept of parallel computation, employing different threads and processes.
 
# Multithreading
To dive into multithreading, let's start by importing the threading and time modules. Then, we'll create a function called "longSquare" that calculates the square of a number but takes a while to do so, using the time.sleep function. 
Next, we'll use threads to calculate the squares of several numbers simultaneously. This is handy for tasks like waiting to fetch data from a remote server, where the code would otherwise sit idle. 
To demonstrate, we'll create two threads: t1 and t2, using the threading.Thread class. We'll specify the target function (longSquare) and pass arguments using the "args" keyword. After starting both threads, we'll join them to ensure they complete execution. 
However, accessing the results directly from the threads isn't straightforward. Instead, we'll leverage the fact that threads can share memory. We'll modify the "longSquare" function to take a dictionary ("results") as an argument and store the results there instead of returning them. 
To streamline this process, we'll use a list comprehension to create a list of threads, starting from 0 to 9. We'll then start and join all the threads in the list. 
Running multiple threads significantly speeds up the process, as shown when we scale it up to 100 threads. This approach is much faster than waiting for each calculation to finish one by one.

# Multiprocessing
You might already be familiar with multiprocessing in Python without realizing it. Consider a simple script called "1000seconds.py" that just uses the `time.sleep` function for a thousand seconds. If you open this script in a second tab and run it, you effectively have two Python processes running independently, demonstrating multiprocessing in action.
Now, how do we write a program to start, stop, and manage these processes automatically? Enter the `multiprocessing` module, which is similar to the `threading` module we've used before.
Before diving in, there's a small catch with the official Python `multiprocessing` module. On some operating systems, you can't spin up a new process to run a function defined in the same file. However, there's a third-party module called `multiprocess` that solves this issue. You can install it with `pip install multiprocess`.
The `multiprocess` module functions just like `multiprocessing`, but without the bug regarding function definition location. Let's import it along with the `time` module.
The `Process` class in `multiprocess` is very similar to the `Thread` class we've used before. We can simply copy and paste our previous threading code and replace `Thread` with `Process`. We'll also rename our processes from `t1` and `t2` to `p1` and `p2`. However, there's one important difference: processes don't share memory, so we can't access the computed values directly.
To address this, we can print the computed values from within the function instead of returning them. However, if we print them directly, they may appear jumbled together. Adding a print statement after the computation helps organize the output. 
If we add more processes, we follow the same pattern as before, but the output may start to look a bit messy with unexpected newlines.

# Opening, Reading and Writting
Working with Files
Reading Files
As programmers, we often need to work with physical files, whether it's to create reports, analyze data, or process information provided to us. In Python, reading files isn't as simple as clicking on an icon; it involves working more closely with the operating system to manage access and changes.
To read a file, we use the `open()` function and provide the file's name along with the mode, which in this case is "r" for reading.
Once the file is open, we can use methods like `readline()` to read lines one by one or `readlines()` to read all lines at once and store them in a list. Remember, each line has a newline character at the end, which we can remove using the `strip()` function.
Writing Files
Similarly, to write to a file, we use the `open()` function with the mode "w" for writing. If the file doesn't exist, Python creates it for us.
We can then use the `write()` function to add content to the file. Python buffers the data we write to the file and only saves it when the buffer is full or when we explicitly close the file using `close()`.
Remember to include newline characters `\n` when writing multiple lines to ensure proper formatting. After writing, if we reopen the file, we'll see our changes reflected.
Appending Files
Appending to a file is similar to writing, but we use the mode "a" instead of "w" to append content to an existing file. Like writing, we need to include newline characters for each line to maintain formatting.
After appending, if we reopen the file, we'll see our additions at the end, preserving the existing content.

#   CVS
Working with CSV Files
Python's CSV module allows us to work with CSV files effortlessly, and it's included with Python, so no need to install anything. Just import it at the top of your script.
To read a CSV file, open it using the `open()` function in read mode and pass the file object to `csv.reader()`. This reader object allows us to iterate over the rows in the CSV file.
If your CSV file isn't comma-separated but rather tab-separated or uses another delimiter, you can specify it using the `delimiter` parameter.
To skip the header row, you can use the `next()` function on the reader object to skip to the next row.
If you want to work with the CSV data as dictionaries where the keys are the header values, you can use `csv.DictReader()`.
Filtering Data
Once you've read the CSV data into a list, you can filter it based on specific criteria. For example, if you're interested in finding postal codes that are prime numbers and located in a specific state, you can filter the data accordingly.
First, convert the reader object to a list. Then, apply filtering criteria using list comprehension. For instance, you can filter postal codes that are prime numbers and belong to a particular state
Finally, print out the length of the filtered data to see how many records meet your criteria.

# JSON
Working with JSON
Loading JSON
JSON files, denoted by the .json extension, are commonplace and you'll likely encounter them often. While we'll mostly focus on JSON strings for now, it's essential to understand their handling.
To start, let's create a JSON string. Remember, JSON isn't Python; it's its own format. Although JSON strings may resemble Python dictionaries, they're strings, not Python objects. To convert a JSON string to a dictionary, import the JSON module (`import json`) and use `json.loads()`.
Note the plural "loads" and not "load." Adding a trailing comma to a JSON string can lead to a JSONDecodeError, especially when dealing with data from untrustworthy sources. Wrapping `json.loads()` with a try-except block (`try-except JSONDecodeError: print Could not parse JSON`) can handle such errors.
Dumping JSON
Conversely, to convert a Python dictionary to a JSON string, use `json.dumps()`. Unlike loading JSON, dumping typically doesn't require extensive exception handling since valid Python dictionaries usually serialize well.
Custom JSON Decoders
However, there are exceptions, such as when dealing with custom Python classes like the Animal class. Attempting to dump a dictionary containing instances of this class will result in a TypeError since the JSON module doesn't know how to handle it.
To address this, we can create a custom JSON encoder by extending the JSONEncoder class and overriding its `default()` method. This method determines how objects are encoded into JSON. By providing a custom encoder, we can specify how instances of the Animal class should be handled during JSON serialization.


# WEEK 3
# Project Planning
# Finding Inspiration for Python Projects

When starting a new programming project for fun or practice, the first question to tackle is: What should the program do? This open-ended question can be challenging, similar to an aspiring author facing a blank page. To overcome this, let's explore various sources of inspiration for your next Python project.

**Hobbies as Inspiration**

Consider your hobbies outside of coding. For instance, if you love attending concerts, you could create a Python script to track your favorite bands' upcoming performances and help you buy tickets. If you're passionate about photography and accumulate thousands of images each month, a Python script could organize your photo collection just the way you want.

**Workplace Automation**

Your job can also inspire ideas. Are there tasks that could benefit from automation? For example, if you and your colleagues spend hours manually transferring data between spreadsheets or generating reports, a Python script could automate these tedious processes, making you the office hero.

**Daily Routine Improvements**

Reflect on your daily routine at home. Are there tasks you could streamline with automation? For example, every morning, I check the weather, read the news, and browse various apps and websites. To make this routine more efficient, I thought of developing an application that sends me a daily email digest with all the information I need in one place. This idea will guide us throughout this course.

**Brainstorming Project Ideas**

Before diving deeper into any project, take a moment to brainstorm at least three project ideas inspired by your life. Write them down or type them out, and keep adding new ideas as they come to you. This way, you'll always have exciting project ideas ready to explore.

# Use Cases
Use cases are a helpful planning tool for applications, similar to user stories but with a different focus. A use case typically includes:

1. **Title**
2. **Actor** (a user or system)
3. **Scenario** (describes how a goal is achieved, either as a paragraph or a list of steps in simple language)

For example, a use case might describe a digest recipient reading tweets on a specific Twitter trend by opening an email, clicking on the trend link, and accessing the corresponding Twitter page.

**Comparison with User Stories**

- **User Stories** focus on the who, what, and why of a task or goal.
- **Use Cases** cover the who, what, and how of achieving that goal.

They complement each other and can be used together or separately depending on your project's complexity and your personal working style.

# Project Requirements

In addition to user stories and use cases, writing traditional requirements helps formally capture an application's capabilities and limitations. 

**Functional Requirements**

These describe what the application should or should not do, starting with "the application must" or "the application shall." For example:

- The daily digest application must generate a random inspirational quote and retrieve current weather forecasts, Twitter trends, and a random Wikipedia article.
- It should format this content into an email and send it to a specified recipient list.

These requirements act as a checklist to ensure all necessary functionalities are met. They are kept high-level, omitting specific details like forecast duration or temperature units. Additional requirements might include configuring content sources, adding and removing recipients, scheduling the email digest, and setting email account credentials.

**Non-Functional Requirements**

These describe how the application should accomplish its tasks, focusing on qualities like maintainability, reliability, and usability. For example:

- The application should have a configurable GUI for the admin.
- It should be extensible for adding more content types.
- It should be resilient to content errors.

With these requirements, you can start the first iteration of the application. This is a good time to pause and write your own set of functional and non-functional requirements for your project.

# Architecture

With the requirements captured, it's time to organize and structure the code. Python, being an object-oriented programming language, benefits from using objects and classes. By identifying nouns in the requirements, use cases, and user stories, potential objects become clear. For instance, words like quote, forecast, location, trends, article, content, email, and recipients suggest potential objects.

**Grouping Nouns into Classes**

Related nouns can be grouped into potential classes, such as:

- **Content**
- **Email**
- **GUI**

**Assigning Behaviors to Classes**

Behaviors and responsibilities are derived from simplified verb phrases in the requirements, such as:

- Generating quotes
- Retrieving forecasts
- Formatting content
- Sending emails

These behaviors are assigned to the corresponding classes:

- **Content Class**: Generates and retrieves content.
- **Email Class**: Formats content and sends emails.
- **GUI Class**: Manages configuration-related behaviors.

**Drafting Methods and Attributes**

Attributes and method names are determined, like storing the list of digest recipients in the email class and setting the send time property. While a detailed plan is crucial for team projects, a rough plan with three classes is enough to start coding for solo developers and smaller projects. The plan will evolve with implementation, and changes are expected.

**Adapting the Plan**

The final product may differ from the initial plan as new insights and learning opportunities arise throughout the development process.


# Stub Code

To start coding, a structure has been set up using three Python modules: `dd_content.py`, `dd_email.py`, and `dd_gui.py`. 

**dd_email.py:**
- Contains the skeleton for the daily digest email class.
- Placeholder methods use the `pass` statement, allowing the script to run without errors despite lacking functionality.
- Includes an `if __name__ == "__main__":` section for testing the email class.

**dd_content.py:**
- Includes an `if __name__ == "__main__":` section for test code.
- Instead of a daily digest content class, it has independent functions for retrieving random quotes, weather forecasts, Twitter trends, and Wikipedia articles. This design choice makes it easy to add more content sources later.

**dd_gui.py:**
- Manages the graphical user interface (GUI) for the email digest administrator using the Tkinter module.
- Import statements for Tkinter are included.
- The `if __name__ == "__main__":` section contains standard code to build and run the GUI when executed as the main script.
- Comments describe the desired functionality of the GUI for future development.

This stub code provides a structure for the implementation, allowing for the separate development of the email class, content functions, and GUI.


# Content Retrieval 
# Daily Inspirational Quotes

With the program structure outlined, it's time to implement the code. In the upcoming section, we'll add four functions to the "dd_content.py" module. Let's start by creating a "get_random_quote" function. Your implementation may vary, as the requirements allow flexibility.

**Steps for Implementing "get_random_quote":**

1. **Determine the Source of Quotes:** Instead of using web scraping libraries like Beautiful Soup or Scrapy, we'll curate a personal list of inspirational quotes.
2. **Store Quotes:** Quotes and their authors will be stored in a CSV file for simplicity. Each line in the file will have the author and quote separated by a vertical pipe symbol.

**Implementing the "get_random_quote" Function:**

1. **Location:** The function is added to the "dd_content.py" file, starting at line seven.
2. **Parameters:** It takes a named parameter for the quotes file location, defaulting to "quotes.csv".
3. **Error Handling:** The file loading code is wrapped in a try-except block to handle exceptions.
4. **Reading the File:** The CSV file is opened, and a list of dictionaries is created using list comprehension, with each dictionary representing an author and their quote. The CSV reader uses the vertical pipe symbol as the delimiter.
5. **Default Quote:** In the except block, a default quote is defined in case the file fails to load.
6. **Random Selection:** The random module's "choice" function selects a random quote from the list, which is returned as a dictionary object.

**Testing the Function:**

- In the main execution block, testing code demonstrates the quote generation functionality.
- The "get_random_quote" function is called without an input argument, and the returned quote is printed.
- Another test sets the quotes file argument to None, triggering the exception clause and returning the default quote.

Running the script will display the generated quotes. The first quote is retrieved from the "quotes.csv" file, and the second is the default quote by Eric Idle.

# Weather Forecasting with OpenWeatherMap

Now that the "get_random_quote" function is complete, let's move on to the next content function, "get_weather_forecast," in the "dd_content.py" module. This function will fetch current weather data from the internet using the OpenWeatherMap API.

**Steps to Implement "get_weather_forecast":**

1. **Choosing a Data Source:**
   - Instead of storing weather data locally, we'll fetch it from the internet using OpenWeatherMap's API.

2. **API Setup:**
   - Register with OpenWeatherMap to obtain a free API key.
   - Use the 5-Day / 3-Hour Forecast API, which provides weather data in three-hour intervals.
   - We’ll use geographic coordinates (latitude and longitude) to specify the location.

3. **Implementation Details:**
   - For simplicity, use a default location (near Cape Canaveral, Florida) for the forecast.
   - Customize the forecast for other locations later if needed.

**Implementing the "get_weather_forecast" Function:**

1. **Imports:**
   - Add the `request` module from `urllib`, the `json` module, and the `datetime` module at the beginning of the script.

2. **Function Definition:**
   - Start the "get_weather_forecast" function at line 25 with an optional `coords` parameter for latitude and longitude.

3. **API Call:**
   - Format the API URL using the API key and coordinates.
   - Retrieve the JSON response from the API using the `request` module.

4. **Processing Data:**
   - Parse the JSON response into a Python dictionary.
   - Create a simplified forecast dictionary containing only the necessary information (city, country, forecast periods).
   - Use a loop to gather forecast data for the next 24 hours (first nine three-hour periods).

5. **Error Handling:**
   - Use a try-except block to handle potential errors during the API call and data processing.

**Example Code Snippet:**

```python
import urllib.request as request
import json
import datetime

def get_weather_forecast(coords=None):
    if coords is None:
        coords = {"lat": 28.3922, "lon": -80.6077}  # Default: Cape Canaveral, FL
    try:
        api_key = 'YOUR_API_KEY'  # Replace with your API key
        url = f"http://api.openweathermap.org/data/2.5/forecast?lat={coords['lat']}&lon={coords['lon']}&appid={api_key}&units=metric"
        response = request.urlopen(url)
        data = json.load(response)
        
        forecast = {
            "city": data["city"]["name"],
            "country": data["city"]["country"],
            "periods": []
        }
        
        for period in data["list"][:9]:
            forecast["periods"].append({
                "timestamp": datetime.datetime.fromtimestamp(period["dt"]),
                "temperature": period["main"]["temp"],
                "description": period["weather"][0]["description"],
                "icon": period["weather"][0]["icon"]
            })
        
        return forecast
    except Exception as e:
        print(f"Error: {e}")
        return None

if __name__ == "__main__":
    # Test cases
    print(get_weather_forecast())
    print(get_weather_forecast({"lat": 30.2672, "lon": -97.7431}))  # Austin, TX
    print(get_weather_forecast({"lat": -9999, "lon": -9999}))  # Invalid coordinates
```

**Testing the Function:**

- Run the script with `python dd_content.py`.
- The output should display the weather forecast for the default location (Cape Canaveral), Austin, TX, and an error message for invalid coordinates.

This setup will provide current weather forecasts by calling the OpenWeatherMap API and processing the data to extract relevant information.

# Trending Social Media Content (Twitter)

To fetch current Twitter trends for the DD content module, we used the Twitter API. Here’s a simplified guide on how this was done:

1. **API Access:**
   - Register a Twitter account, request API access, and obtain an API key from the "Getting access to the Twitter API" section on Twitter’s website.
   - The authentication process can be complex, so we searched for a Python library to simplify this.

2. **Finding a Library:**
   - After searching PyPI, we found over 3,000 related projects but focused on finding a well-maintained library.
   - Google searches and blog posts helped us find "Tweepy," a popular and regularly updated library suitable for our needs.

3. **Using Tweepy:**
   - Install Tweepy with `pip install tweepy`.
   - Import Tweepy in your code and define a function `get_twitter_trends` with an optional WOEID parameter (Where On Earth Identifier).

4. **Implementation:**
   - Use a try block to handle potential errors.
   - Authenticate using your Twitter API key and secret key.
   - Use Tweepy’s `trends_place` method to retrieve current trends based on the WOEID.

**Example Code Snippet:**

```python
import tweepy

def get_twitter_trends(woeid=23424977):  # Default WOEID for the United States
    try:
        api_key = 'YOUR_API_KEY'
        api_secret = 'YOUR_API_SECRET'
        auth = tweepy.AppAuthHandler(api_key, api_secret)
        api = tweepy.API(auth)

        trends = api.trends_place(woeid)
        return trends[0]['trends']
    except Exception as e:
        print(f"Error: {e}")
        return None

if __name__ == "__main__":
    # Test cases
    print(get_twitter_trends())  # Default: United States
    print(get_twitter_trends(44418))  # London WOEID
    print(get_twitter_trends(9999999))  # Invalid WOEID
```

**Testing the Function:**

- **Default Trends:** Call the function without arguments to get trends for the United States.
- **Specific Location:** Provide a WOEID for another location, like London.
- **Error Handling:** Test with an invalid WOEID to ensure the function handles errors properly.

Running the script displays trends for the United States, followed by trends for London, and an error message for the invalid WOEID. This setup effectively fetches and handles Twitter trends using the Tweepy library and the Twitter API.

# Trending Social Media Content (Twitter)

To fetch current Twitter trends for the DD content module, we used the Twitter API. Here’s a simplified guide on how this was done:

1. **API Access:**
   - Register a Twitter account, request API access, and obtain an API key from the "Getting access to the Twitter API" section on Twitter’s website.
   - The authentication process can be complex, so we searched for a Python library to simplify this.

2. **Finding a Library:**
   - After searching PyPI, we found over 3,000 related projects but focused on finding a well-maintained library.
   - Google searches and blog posts helped us find "Tweepy," a popular and regularly updated library suitable for our needs.

3. **Using Tweepy:**
   - Install Tweepy with `pip install tweepy`.
   - Import Tweepy in your code and define a function `get_twitter_trends` with an optional WOEID parameter (Where On Earth Identifier).

4. **Implementation:**
   - Use a try block to handle potential errors.
   - Authenticate using your Twitter API key and secret key.
   - Use Tweepy’s `trends_place` method to retrieve current trends based on the WOEID.

**Example Code Snippet:**

```python
import tweepy

def get_twitter_trends(woeid=23424977):  # Default WOEID for the United States
    try:
        api_key = 'YOUR_API_KEY'
        api_secret = 'YOUR_API_SECRET'
        auth = tweepy.AppAuthHandler(api_key, api_secret)
        api = tweepy.API(auth)

        trends = api.trends_place(woeid)
        return trends[0]['trends']
    except Exception as e:
        print(f"Error: {e}")
        return None

if __name__ == "__main__":
    # Test cases
    print(get_twitter_trends())  # Default: United States
    print(get_twitter_trends(44418))  # London WOEID
    print(get_twitter_trends(9999999))  # Invalid WOEID
```

**Testing the Function:**

- **Default Trends:** Call the function without arguments to get trends for the United States.
- **Specific Location:** Provide a WOEID for another location, like London.
- **Error Handling:** Test with an invalid WOEID to ensure the function handles errors properly.

Running the script displays trends for the United States, followed by trends for London, and an error message for the invalid WOEID. This setup effectively fetches and handles Twitter trends using the Tweepy library and the Twitter API.

### Importing Articles

To implement the function for fetching random Wikipedia articles, we used the Wikipedia REST API. Here’s a simplified guide:

1. **Check Wikipedia API:**
   - Search for the Wikipedia API documentation using Google.
   - Find the Wikipedia REST API which allows access to their content.

2. **Using the API:**
   - The REST API provides options to get a random page title, full page HTML, or a summary.
   - We select the summary option since we only need a brief extract for the digest email.

3. **Fetching the Data:**
   - Use the API to get a URL that returns a random article summary in JSON format.
   - The JSON response includes fields such as the page title, summary, and URL.

**Example Code Snippet:**

```python
import requests
import json

def get_wikipedia_article():
    try:
        url = 'https://en.wikipedia.org/api/rest_v1/page/random/summary'
        response = requests.get(url)
        data = response.json()

        article = {
            'title': data['title'],
            'extract': data['extract'],
            'url': data['content_urls']['desktop']['page']
        }
        return article
    except Exception as e:
        print(f"Error: {e}")
        return None

if __name__ == "__main__":
    article = get_wikipedia_article()
    if article:
        print(f"Title: {article['title']}")
        print(f"URL: {article['url']}")
        print(f"Summary: {article['extract']}")
```

**Testing the Function:**

- Run the script to fetch a random Wikipedia article.
- Print the article’s title, URL, and summary.

**Expected Output:**

Running the script will display a random Wikipedia article with its title, URL, and summary. Each execution fetches a different random article, demonstrating the API’s functionality.

This function, along with previous implementations for quotes, weather, and Twitter trends, completes the initial requirements for content retrieval. These examples illustrate how to use various APIs to fetch and process web information.

# Digest Email
# Writing and Formatting Email Messages
Now, let's delve into crafting and formatting email messages, a crucial aspect of the Daily Digest email module. Here's a simplified walkthrough:

1. **Understanding Email Formatting:**
   - Initially, we planned a method called `format_message` to structure content for emails. However, the specifics of email formatting were unclear.
   - Through research, we found Python's `MIMEMultipart` class, allowing both plaintext and HTML formats within a single email message.

2. **Implementation Overview:**
   - The `format_message` method generates both plaintext and HTML versions of the email content.
   - In the constructor method (`__init__`), we initialize a dictionary to store four types of content, each marked with a Boolean flag for inclusion. Content is fetched using functions from the DD content module.

3. **Formatting Plaintext:**
   - We format plaintext content by setting up a string (`text`) with a header containing the current date.
   - Section headers and content are added based on inclusion flags. For instance, weather forecasts and Twitter trends are formatted using loops for clarity.

4. **Generating HTML Content:**
   - Similar to plaintext, HTML content is constructed using HTML strings (`HTML`).
   - Content inclusion is determined by `if` statements. Each section, like the weather forecast or Twitter trends, has its own HTML formatting.

5. **Final Steps and Testing:**
   - Towards the end of `format_message`, an HTML footer is appended, and the plaintext and HTML messages are returned as a dictionary.
   - Test code generates a message, prints plaintext and HTML content, and saves them as files for review.

**Test Output:**
- Running the script shows plaintext content followed by HTML code in the terminal.
- A text file with plaintext content is created in the directory.
- For full HTML content, opening the HTML file in a browser reveals the formatted email content, including stylized headers, organized forecast data, and clickable hyperlinks for Twitter trends.

This process ensures emails are well-structured and visually appealing, enhancing user experience.

# Sending an Email
After getting the daily digest content formatted, the next step is to send it as an email. Here's how it works:

1. **Email Management with Python's 'email' Library:**
   - Python's standard package includes the 'email' library, particularly the 'email.message' module, which helps manage email messages. The central component is the "Email Message" class, used to assemble various parts of the daily digest email like the subject line, recipient list, and message content.

2. **Connecting to an SMTP Server:**
   - SMTP-Lib, another Python module, enables creating a client session to send emails through an SMTP server. However, setting up and running your own email server locally is cumbersome. Instead, you can use online email services like Outlook, which provide an SMTP server that you can connect to.

3. **Configuring Outlook SMTP Settings:**
   - Microsoft's support page provides server name, port, and encryption method details for connecting to the Outlook SMTP server, ensuring secure email transmission.

4. **Implementation Overview:**
   - The `send_email` function begins by importing the necessary modules: SMTP-Lib and the `email.message` class.
   - In the `__init__` method, additional instance variables are initialized, including a list of recipient email addresses for testing and a dictionary to store the sender's email address and account password.
   - Next, the function creates a new email message object, setting fields such as the subject line, sender and recipient email addresses.
   - The message body is generated using the `format_message` method, and plain text content is configured using the `set_content` method.
   - To include the HTML version of the content, the `add_alternative` method is used, making the message a multi-part container with both plain text and HTML parts.
   - Finally, the function establishes a secure connection to the SMTP server using TLS encryption, logs in with the sender's credentials, and sends the email message object using the `send_message` method.

5. **Testing the Code:**
   - A call to the `send_email` method is added at the end of the script. Running the script sends the email.
   - Checking the inbox of one of the recipients reveals a new message with the subject "daily digest" and today's date. Opening the email displays the HTML formatted content, including the quote of the day, weather forecast, Twitter trends, and a Wikipedia summary.
   - By including both plain text and HTML versions, the daily digest email becomes compatible with a wider range of email clients and settings.

This process ensures smooth transmission of the daily digest email, ensuring recipients receive the information in a clear and accessible format.

# Task Scheduling

After successfully implementing the format message and send email methods for the daily digest email class, the final task is to schedule the email to be sent at a specific time every day.

1. **Choosing a Scheduling Library:**
   - Initially, the plan was to use the "schedule" library from the Python package index. However, it was discovered that this library lacks the ability to operate in the background, which would cause the main thread to become unresponsive.

2. **Workaround with Threading:**
   - To address this limitation, a workaround was found in the documentation, suggesting the use of Python's threading module to run the scheduler as a separate thread from the main program.

3. **Implementation Overview:**
   - A new class named `Scheduler` was created to handle the scheduling of daily digest emails.
   - This class inherits from Python's threading module's `Thread` class, allowing it to run independently from the main thread.
   - The constructor method initializes a threading event object to indicate when to stop running the thread.
   - The `schedule_daily` method schedules the email sending task using the schedule API, ensuring it runs every day at the specified time.
   - The `run` method continuously executes pending tasks until the stop flag is set.
   - A `stop` method is provided to set the stop flag and halt the execution of the scheduler.

4. **Test Code:**
   - In the test code, a daily digest email object is instantiated, and a scheduler object is created to start running as a separate thread.
   - A test email is scheduled to be sent one minute into the future, and the program remains active until the scheduled time.
   - After the email is sent, the scheduler is stopped to halt the execution.

5. **Outcome:**
   - Running the scheduler script schedules a test email to be sent at the specified time. Upon checking the email client, a new daily digest is received as expected.

By running the scheduler as a separate thread, the main program remains responsive, ensuring smooth execution of tasks without freezing the user interface. This implementation effectively schedules and sends the daily digest email at the specified time every day.

# Building a Graphical User Interface (GUI)
# GUI Design Planning
1. **Keep It Simple:**
   - GUI development is usually left until the end of a project to ensure that the underlying functionality is built first. Simple methods like sketching ideas on paper or using basic tools like PowerPoint slides can help in planning the GUI layout.

2. **Identify Admin Needs:**
   - Refer back to the requirements list to determine what functionalities the admin needs in the GUI. These may include content customization, recipient management, scheduling options, and configuration of sender credentials.

3. **Break It Down:**
   - Break down the GUI design into smaller parts to make the process more manageable. Envision each task as a separate section and arrange the elements within them.

4. **Design Each Subsection:**
   - Design each subsection of the GUI separately. For example:
     - **Content Configuration:** Use check buttons for binary choices like selecting content sources.
     - **Recipient Management:** Utilize a list box for managing recipients, with buttons to add and remove selected recipients.
     - **Scheduling Options:** Use spin boxes to select the hour and minute for scheduling the email digest.
     - **Sender Credentials:** Provide text entry fields for entering the email account and password.

5. **Consider Safety Measures:**
   - To prevent accidental changes triggering unwanted actions, include an "Update Settings" button. This button will allow the admin to deliberately lock in the new configuration settings, ensuring that unintended actions are prevented.

By breaking down the GUI design into smaller subsections and carefully planning each component, it becomes easier to visualize the layout and ensure that the GUI meets the admin's needs effectively.

# Exploring Python Tkinter GUI

The GUI module, named "dd GUI," is around 250 lines long. Let's focus on the key design decisions made in its implementation. You can find the complete code in the exercise files for a more detailed exploration.

1. **Module Imports:**
   - Besides importing Python's Tkinter module, the daily digest email and scheduler modules are also imported since the GUI interacts with instances of both.

2. **Initialization Method:**
   - The initialization method of the daily digest class initializes the TKinter window where the GUI is built. It adds a title and a header label to the window and defines font styles to be used.

3. **Building GUI Sections:**
   - Different parts of the GUI, like adding and removing recipients, scheduling delivery time, configuring email content, updating sender credentials, and controlling settings updates, are built using TKinter frames and widgets.
   - Variables are instantiated within the initialization method to easily initialize their values in one place, allowing for easy modification.
   - Functions for creating and placing GUI widgets are organized into two sections: creating widgets and positioning them within the frame using TKinter's grid geometry manager.

4. **Callback Methods:**
   - Four callback methods are associated with buttons in the GUI, such as adding recipients, removing selected recipients, updating settings, and manually sending an email digest.
   - These methods handle user interactions and update the GUI accordingly.

5. **Shutdown Method:**
   - The "shutdown" method stops the scheduler thread before closing the GUI window, ensuring proper termination of the application.

6. **Main Section:**
   - The "if __name__ == '__main__'" section spawns the GUI as the top-level script when the module is run. It creates the GUI window with controls for various functionalities like adding/removing recipients, scheduling send time, selecting content, updating settings, and triggering manual email sends.

This Python Tkinter GUI provides all the necessary controls for the project, allowing the admin to customize and manage the daily digest application efficiently. For more in-depth learning about building GUIs with Python's Tkinter module, consider exploring courses on Python GUI development with Tkinter.

# Design Iteration
# Iterative Enhancements

Great job on completing the initial scope of the daily digest project! Let's break down the tasks to consider for further enhancing the application based on your ideas and priorities:

1. **Save Configuration Settings:**
   - Modify the program to store configuration settings in a file or database. This ensures that changes made by the admin are retained across program restarts.

2. **Customizable Content for Recipients:**
   - Allow recipients to customize the content they want to receive in their digest. Create a settings section for recipients to select preferred content categories or topics.

3. **Personalized Weather Forecast:**
   - Enhance the weather forecast by customizing it for each recipient's location. Include a field in the recipient's information to store their location and fetch location-specific forecasts using a weather API.

4. **Timezone-based Email Sending:**
   - Adjust the sending time of the email digest based on each recipient's timezone. Ensure that all recipients receive the digest at a time relative to their day.

5. **Notification of Unavailable Content Sources:**
   - Implement a mechanism to notify the admin when a content source becomes unavailable. Periodically check content source availability and send notifications or generate error logs when issues arise.

6. **Persistent Application as a Scheduled Service:**
   - Modify the application to run as a scheduled service instead of requiring continuous Python interpreter running. Use OS-specific mechanisms like cron jobs to schedule program execution at the desired time.

7. **Secure Storage of Sensitive Information:**
   - Enhance security by finding a more secure way to store sensitive information like sender credentials and API keys. Consider encryption or storing credentials in a separate, restricted-access configuration file.

8. **GUI Improvements:**
   - Enhance the visual appeal and usability of the GUI. Refine layout, add icons, use color schemes, and incorporate user-friendly features like tooltips or keyboard shortcuts.

# Preserving Configuration Settings
Here's a simplified version of the process for preserving configuration settings:
To save and restore configuration settings between program runs, JSON file format is used. In the GUI module, two new methods were added to the GUI class: save_config() and load_config().
In save_config(), the current state of GUI elements is collected into a configuration dictionary and saved to a file using JSON.dump().
In load_config(), the JSON file is loaded into a dictionary, and GUI variables are set accordingly. Then, the update_settings() method is called to apply the configuration.
To integrate these methods into the program's flow, two calls are made:
1. In the shutdown method, a try-except block is added to save the current configuration when closing the program.
2. In the init method, a try clause is added to load the configuration from the JSON file. If loading fails, default settings are used.
Implementing this new feature takes about half an hour but significantly improves the usability of the digest project. Enjoy tackling the next idea on your to-do list!

#  Project Packaging and Distribution 
# Distributing Python Projects
To distribute your Python project as an executable, you can use a tool called PyInstaller. First, install PyInstaller by running "pip install pyinstaller" in your terminal.
Once installed, navigate to your project directory and run the command "pyinstaller -w -F dd_gui.py". Here, "-w" hides the console window, and "-F" bundles everything into a single executable file.
After running PyInstaller, you'll find the generated EXE file in a "dist" folder. You can share this executable with others who want to use your app, like your mom. They can simply double-click the EXE file to launch the program and access the GUI.
Remember, PyInstaller offers more features than covered here. Check the documentation for further details on distributing Python apps as executables.

# Week 4














































