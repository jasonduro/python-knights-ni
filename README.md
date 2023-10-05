[Practice Task 4.txt](https://github.com/jasonduro/python-knights-ni/files/12743535/Practice.Task.4.txt)# python-knights-ni
My first python project - a recipe app 

## Exercise 1.1
### Install Python on your system
python --version  Python 3.9.6

<img width="560" alt="python version" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/b049a0d7-16a3-4f34-b120-997084255b42">


* Set up a new virtual environment:
<img width="568" alt="mkvirtualenv" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/18dfaa83-5c8e-4a4a-9610-fabdea5c1c92">

* Install Visual Studio Code
<img width="954" alt="Visual Studio Code" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/c05d241e-daf7-4d57-9f27-add40f70a29a">

  
* Set up an IPython Shell:
<img width="546" alt="ipython" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/891b1b3b-9b6a-41d4-8180-3fab47b75dee">

* Export a requirments file then create a new environment to install packages from the requirements file: 
<img width="567" alt="install requirements file" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/cbe16212-d4a2-469f-ab79-b7525feb24c3">

## Exercise 1.2
### Practice Exercise 1

To begin, copy the following lines of text into a text file, and then save it as “codepractice1.txt”:
`1000
0.145
3`

Now navigate to the directory where this text file is stored, open an IPython shell, and copy each of the following lines into your shell to store these values as their respective variables:

    f = open('codepractice1.txt', 'r')
    lines = f.readlines()
    [principal, rate, time_period] = [x.strip('\n') for x in lines]
    f.close()

This command 1) reads your saved text file, 2) turns the lines into values, and then 3) assigns them to the variables `principal`, `rate`, and `time_period`.
You now have three variables:
1. `principal` = 1000
2. `rate` = 0.145
3. `time_period` = 3

<img width="514" alt="create variables from txt file" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/71796caa-626b-4c62-b7a2-01be273dc4a1">

Convert each of the variables—`principal`, `rate` and `time_period`—into the `float` data type through explicit type conversion, and reassign these values to their own respective variables (e.g., `principal = float(principal)`).
    1. f_principal = float(principal)
    2. f_rate = float(rate)
    3. f_time_period = float(time_period)
    
<img width="330" alt="convert to float" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/f3997f4c-6acd-4f89-91a5-0a891f587de2">

Now calculate the new compounded principal from the formula below, using the mathematical operations from earlier (remember that time_period will use exponation operators //). Assign the result to the variable name compounded_principal (Compounded Principal = Principal * (1+Rate) {Time_Period} ).

<img width="555" alt="compounded_principal revised" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/cc7631d3-5f80-415f-8c6c-2fc725200972">


### Practice Exercise 2
1. Enter the total world population listed above into a tuple called total_population.
2. Make the data more concise! Perform a slice on total_population such that only every third data point is considered (6789088686, 7041194301, etc.), and store the slice as sliced_total_population.
3. Also, find the maximum value insliced_total_population.
<img width="560" alt="Screen Shot 2023-09-19 at 08 48 43" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/10793b98-5af2-438e-933d-14ab783e5eae">

### PRACTICE Exercise 3: LISTS

Here’s a portion of Ford’s vehicle lineup for 2020:
* Fiesta, Focus, Mondeo, Galaxy, Edge, Kuga, Ecosport, Puma, Ranger
However, the list is missing an element: the Mustang. To practice what you’ve learned, complete the following steps and take screenshots of your IPython shell after each step:

1. Make a list of the above lineup in the same order.
2. Add Mustang to the end of the list.
3. Next, sort the list in alphabetical order, and then display the sorted list.
   
<img width="871" alt="Ford_2020 List" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/8d6199e4-4618-45b6-9b35-abceccae4a7d">

### PRACTICE Exercise 4: STRINGS

Assume that you’ve run the following statements:

>>> str1 = 'hello, '
>>> str2 = 'how are you?'
>>> str3 = str1 + str2
>>> print(str3)
>>> 'hello, how are you?'

To practice what you’ve learned, without using Python’s shell, work out on your own what the following statements would return:

str3[3:]
returns: lo, how are you?

str3[-3:]
returns: you?

str3[2:9:3]
returns: l,o

str3[::-2]
returns: o, y, e, a, w, h, ',', l, e 
^ incorrect - correct answer is: '?o r o olh'
	the starting position is still '?', then you move every -2 	positions. 

str3[2:8]
returns: llo, h

### PRACTICE Exercise 5: DICTIONARIES
Time for your last practice task of the Exercise! To practice what you’ve learned, complete the following steps and take screenshots after each step:

1. Make a list of the months in a year, and store it as `months_named`.
2. Next, make another list of numbers ranging from 1 to 12 as `months_numbered`.
3. Use the `zip()` function to merge the two lists together into a dictionary called `months_dict` such that the values in `months_named` act as the keys for the dictionary. An example of a key-value pair in this dictionary would be `October: 10`.
4. Clear both initial lists (`months_named` and `months_numbered`) with the `clear()` method available to them.
5. Print the entire dictionary onto your screen.
6. Finally, convert the keys of this dictionary back into another list, `months_extracted`, and then list them in alphabetical order.
<img width="531" alt="1 2 P5 Months" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/152767c2-b161-4c76-a936-e2f189021ebd">
<img width="530" alt="1 2 P5 Months Sorted Alphabetically" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/ec38a70f-d652-4022-a647-bf7ecd2a8916">

## Exercise 1.2 TASK
Directions
1. Create a structure named recipe_1 that contains the following keys:
name (str): Contains the name of the recipe
cooking_time (int): Contains the cooking time in minutes
ingredients (list): Contains a number of ingredients, each of the str data type
Decide what data structure you would use for this purpose, and in your README file in the repository for this task, describe in approx. 50-75 words why you’ve chosen to use it.

For this purpose, I've chosen to use a combination of dictionaries and lists in Python.

Dictionaries: I used dictionaries (recipe_1, recipe_2, etc.) to represent each recipe because they allow me to store structured data with named keys (e.g., 'name', 'cooking_time', 'ingredients'). This makes it easy to access and manipulate specific attributes of each recipe.

List: I used a list (all_recipes) to store all the recipe dictionaries. Lists are ideal for storing a collection of items, and in this case, they allow me to keep all the recipes in a sequential order. I can easily add, remove, or iterate through the recipes as needed.

This combination of dictionaries and a list provides a clean and organized way to manage multiple recipes, making it easy to expand the collection of recipes and access their individual attributes.

2. The recipe_1 structure that you create will be for a cup of tea, with the following attributes:
Name: Tea
Cooking time: 5 minutes
Ingredients: Tea leaves, Sugar, Water
<img width="435" alt="Task 1 2 step 1   2" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/fccc04c8-3921-48b8-bcfc-0661da5723ed">

4. Create an outer structure called all_recipes, and then add recipe_1 to it. Figure out what type of structure you would consider for all_recipes, and briefly note down your justification in the README file. Ideally, this outer structure should be sequential in nature, where multiple recipes can be stored and modified as required.
<img width="616" alt="Task 1 2 step 3" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/2160dfac-3a01-4ae7-a941-2c01b6f4c318">

5. You can make your own recipes too! Generate 4 more recipes as recipe_2, recipe_3, recipe_4, and recipe_5, and then add them as well to all_recipes.
<img width="507" alt="Task 1 2 step 4" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/58a0df81-f66e-41f1-a84c-417ae19d7a62">

6. Once you’re done setting up all_recipes, print the ingredients of each recipe as five different lists, inside the IPython shell.
<img width="956" alt="Task 1 2 step 5" src="https://github.com/jasonduro/python-knights-ni/assets/38364361/ee81d156-9705-4739-86b2-dd6a22e5b0fa">
