---
title:  'Mini Course'
date: "2015-11-06"
---


### Data Bootcamp Mini-Course, 2015 edition  

This document:  https://github.com/DaveBackus/Data_Bootcamp/blob/master/Markdown/bootcamp_mini_2015.md

A brief overview of the tools and skills you'll learn in **[Data Bootcamp](https://github.com/DaveBackus/Data_Bootcamp#data-bootcamp)**, a course at NYU's Stern School of Business. Developed by Dave Backus, Chase Coleman, Spencer Lyon, and Glenn Okun.  With the help and support of Sarah Beckett-Hile, Hersh Iyer, Itamar Snir, and executives at Amazon.  

November 6 and 13, 2-4pm, Tisch UC 25

* Session 1:  Python fundamentals, examples    
* Session 2:  data management (Pandas), graphics (Matplotlib), examples

---
#### Announcements

We'll post announcements here.  

**Bring your computer to class.**  We'll put it to work.  

**Before the second session.** Download the code files below.  We'll use three:  one for the data package (Pandas), one for graphics (Matplotlib), and one for examples putting both to use.  Remember to click on the Raw button to get the right file.

**Code files for class.**  [Class 1](https://github.com/DaveBackus/Data_Bootcamp/blob/master/Code/Python/bootcamp_fundamentals_1.py) | Class 2  ([data](https://github.com/DaveBackus/Data_Bootcamp/blob/master/Code/Python/bootcamp_pandas_1.py) | [graphics](https://github.com/DaveBackus/Data_Bootcamp/blob/master/Code/Python/bootcamp_graphics_1.py) | [examples](https://github.com/DaveBackus/Data_Bootcamp/blob/master/Code/Python/bootcamp_examples.py)).  Click on the link, then click on the **Raw button** in the upper right, then save in a directory where you can find it.  Setting up a Data_Bootcamp directory wouldn't be a bad idea.  

**Before the first session.**
Please install the **Anaconda** distribution of **Python 3.4 or (now) 3.5** from the download page: <https://www.continuum.io/downloads>.  If you have trouble, read [this chapter](https://davebackus.gitbooks.io/test/content/installing-python.html), but keep in mind that the Anaconda download page has changed a little since it was written.  Or come 20 minutes early to the first session and we'll (try to) set you up.  

---

#### Session 1


**Skills**

Why skills?

* Businesses want people with skills (duh!)

Why code?

* One of the skills businesses value (not the only one)
* Do things Excel can't do, and do them faster

Why Python?

* User-friendly
* Broad range of applications  

**Overview**

Where we're headed

* Think of a **picture** you'd like to produce -- a "visualization"
* And about what **data** you'll need
* And the **coding skills** to get there
* Examples:  [Gapminder](http://www.gapminder.org/world/) | [cancer screening](http://www.vox.com/2015/10/28/9631500/does-mammography-work) | [Uber in NYC](http://fivethirtyeight.com/features/uber-is-serving-new-yorks-outer-boroughs-more-than-taxis-are/) | [mortality](http://www.pnas.org/content/early/2015/10/29/1518393112.full.pdf) | [earthquake](https://jawbone.com/blog/napa-earthquake-effect-on-sleep/)   

Philosophy  

* Target **coding novices**, no prior experience required or expected
* Not a typical programming course:  cover only those aspects of Python relevant to data work

Rules to live by

* **Don't panic**.  The jargon and concepts will seem mysterious at first, but if you keep with it they'll start to make sense.  
* **One step at a time.**  We'll go as slowly as we need.  Speed is the enemy, it leads to mistakes.  
* **Doing is learning.**  We'll set you up to teach yourself.  If you're stuck, either **ask for help** or practice your **Google fu** and find the answer with Google.   

**Prelaunch checklist**

Install Anaconda

* Google "anaconda download"
* Download installer for **Python 3.5**
* Run installer

Locate this file in a browser

* Google "nyu data bootcamp" and follow links
* Or:  type in url at the top

Save today's code file in a handy place

* Create directory/folder `Data_Bootcamp`
* Click on code link above, then Raw button
* Save file in `Data_Bootcamp` directory

Launch

* Look for **Launcher** in your programs
* Start it up (takes a minute)
* Click on **Spyder** (another minute)

**Programming basics**

Our typical program

* Input data
* Manipulate data until it's in the form we want
* Produce a compelling graphic

Spyder basics  

* Editor
* IPython console, object inspector    

Python basics

* Calculations, assignments, comments, strings and quotes, lists, built-in functions (print, type), objects and methods, tab completion, getting help

If you'd like to do more of this on your own:     

* Work your way through the [Codecademy](https://www.codecademy.com/tracks/python) course.  You can stop when you get to Advanced Topics.     
* Read the Python Fundamentals chapters of our [Data Bootcamp book](https://www.gitbook.com/book/davebackus/test/details).
* Read Mevan's [wonderful guide](https://medium.com/keep-learning-keep-growing/how-i-learned-to-stop-worrying-and-love-the-code-af1a809457c7) "to the misconceptions and anxieties that people like me -- people newly learning to code -- may have."  

**Next Wednesday or Thursday:**  Work through the review below.

---

#### Session 2

**Prelaunch checklist**

* Start Spyder
* Locate this document (Google "nyu data bootcamp", look for mini-course link)
* Save code files, open them in Spyder

**Review.**  Sketch brief answers.  Feel free to consult your neighbor.

Concepts.  Explain each of the following:   

* `x = 107.3`
* `x = x**2`
* `'this'` and `"this"`
* `y = '3.14159'`
* `y = 2 * y`
* `float(y)`
* `z = [3, 2, 7, 2]`
* `type(x)`
* `type?`
* `w = z.count(2)` (This one's harder; the idea is to use the available help to find out what it does. Or just try it.)

Problems.  

* What should you do if you don't follow what we're doing in class?  
* Set `first = 'Hersh'` and `last = 'Iyer'`.  Construct a string `bothnames` that consists of the first name, a space, and the last name in upper-case (capital) letters.  
* Suppose we have a variable `z = '12,345.6'`.  What is its type?  Can we convert it to a floating point number?  (This one's harder.  Hint:  What method can we use to get rid of the comma?)  

Reminders:  IPython console, Object explorer, code cell

**Data and graphics**

Packages

* Packages/libraries/modules = plug-ins that add new tools to Python
* There are lots of them
* Our favs:  Pandas (data), Matplotlib (graphics)
* The `import` command

Data basics

* `import pandas as pd`
* Reading spreadsheets and csv files
* Dataframes:  column labels, row labels, dtypes, ...   
* Internet sources with APIs:  FRED, World Bank, Fama-French  

Graphics basics

* `import matplotlib`
* Approach 1:  `plot(x,y)`
* Approach 2:  apply methods to `fig, ax`
* Parameters and styles
* Approach 3:  apply `plot` method to dataframe

Examples

* GDP in various countries
* Emerging market indicators
* US GDP and GDP growth
* Indicators of US economic conditions
* US stock returns
* Healthcare spending

**Graphics practice.**
Randy Olson has a
[nice blog post](http://www.randalolson.com/2014/06/28/how-to-make-beautiful-data-visualizations-in-python-with-matplotlib/) (or Google "randy olson beautiful") about creating effective graphics.
He starts with [this gif](http://gfycat.com/ImprobableFemaleBasenji).
Skim his post, play the gif, and

* Write a Python program that recreates the data in the figure, both numbers and labels.
(There are only a few points, you can just type them into lists.)
* Approximate the various graphs using Matplotlib.
* Play around with the graphics parameters.
What is the best graph you can produce?
What do you like about it?
* Variant:  Do the same with our GDP per capita bar charts.

If you'd like to do more of this on your own:     

* Browse the [Practical Business Python](http://pbpython.com/) blog, it's filled with practical information about how to go between Pandas and Excel.  Start with [this one](http://pbpython.com/excel-pandas-comp.html).
* Watch Brandon Rhodes's [video](https://youtu.be/5JnMutdy6Fw), it's a wonderful start on advanced features of Pandas.  Two hours long, but worth it.  
* Check out the Matplotlib [gallery](http://matplotlib.org/gallery.html) of examples, they all come with code you can run yourself.  
* Wait till we write the relevant chapters of our book.  

**Mailing list.**  If you'd like to get announcements about similar events, sign up for the NYU Data Bootcamp [Google Group](https://groups.google.com/forum/#!forum/nyu_data_bootcamp).  
