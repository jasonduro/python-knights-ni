# python-knights-ni
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


