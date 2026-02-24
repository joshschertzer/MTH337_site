# Weekly digest 4
## Joshua

:::{epigraph}
Will grading for project 2 be more strict now that we feedback from project 1?
:::
## Alan

:::{epigraph}
When will our next project be due? Is this project expected to be shorter than the last one?
:::

Project 2 will be due on Saturday, February 28. As for length - I don't expect it to be 
significantly shorter than the first project.

## Joseph

:::{epigraph}
What is the next project going to be about?
:::

We will be looking at modeling the spread of epidemics. 


## Erica

:::{epigraph}
How would you write the code for last week's Exercise 5? I think I'm a little lost on 
how to set two conditions for two different arrays to satisfy the output of the code.
:::

Do you maybe mean Exercise 4? In any case. we will work more on it on Tuesday. 

## Pierce

:::{epigraph}
How do the past couple weeks with projects incorporate into the things we have learned this week?
:::

I am not sure if I understand the question, but for the past weeks we looked at some computations 
related to images processing and this is also the topic of the current project. 

## Jaimie

:::{epigraph}
Can you explain exercise 4 from this week? 
:::

We will work some more on these exercises on Tuesday this week. 

## Chloe

:::{epigraph}
Are these weekly digests a part of our grade?
:::

Yes, this is explained in the syllabus. What counts toward the grade is only if you submit these 
digests. I don't grade you based on what you write. 


## Daniel

:::{epigraph}
How does the grading scale in the class? (What numeric is needed for an A, A-, etc.) And how can 
we convert our project grade to a numerical score
:::

Majority of the grade is based on project reports, and the total grade for project reports is just 
the average of individual report grades. To compute this average, convert letter grades for the reports
into grade points (A+ = 4.33, A = 4.0, A- = 3.67, B+ = 3.33 etc.), compute the average, and then 
convert the average into a letter grade. 

## Ryan

:::{epigraph}
Will there ever be some sort of partial credit on quizzes? 
Or if you make a small mistake, you just don't get the question right? 
:::

There is no partial credit for quiz questions, it is either 0 or 1 point. However, if I see some small 
mistake I often just count the answer as correct. 

## Alyssa

:::{epigraph}
Are there any jobs that would require people use image denoising? I am curious about who would use this and what they would use it for.
:::

Any software processing images (including software running digital cameras, medical imaging equipment etc.)
has some methods built in reducing noise in images in order to improve image quality. People who write such 
software need to work with image denoising. This is also an active research area, since people are trying to 
come up with better methods for reducing noise. 

## Jenna

:::{epigraph}
How many images should be used in the project?
:::

As many as you feel makes sense. You can choose just one image and experiment with it, 
or you can choose a few images with various features (light background, dark background, 
images of people, image with some text etc.). Either way can be fine, depending how you 
structure your report.

## Nicholas

:::{epigraph}
Are these fundamental changes, like shifting RGB values, the foundation of all image "filters" 
on phones and such?
:::

All image filters boil down to manipulating numerical data describing colors of pixels. Some methods are 
more complex than others - they can involve linear algebra, Fourier analysis, machine learning algorithms 
etc. 

## Shane

:::{epigraph}
Is this next project going be worth more or less points than the first one?
:::

It will be worth as much as the first project. It is possible that at some point I will assign some project 
that will involve writing code only, without narrative, and such project will be worth less than projects 
where narrative is required. 

## Rodrigo

:::{epigraph}
What would you say is good code etiquette? Also, what are some good tips on debugging code?
:::

- Structure the code into relatively short functions that serve a well defined purpose. 
- Document the code with docstrings and code comments as needed. 
- Give functions and variables meaningful names. 
- Do not copy and paste code if you want to use it more than once. If you need to to this, 
  you should write a function and use it instead. 
- Do not use "magic numbers" - i.e. numbers with random-looking values that appear in the code 
  without an explanation. If you need to use such a number, assign it to a variable with a easy to 
  understand name. For example, `hours_in_week = 168` make more sense than just using 168 without 
  any context. 

As for debugging, in this course we are not writing code that is long or very complicated, so 
there is no need to use anything fancy. Test each function separately to make sure that it works
as expected. Temporarily add print statements inside your code to print out intermediate values 
of a calculation. It you get an error message, read it and try to figure out what it means.


## Andrew

:::{epigraph}
- Can exercise 5 from last week be completed without loops (or list comprehension)?

- When we use `&`,  `|` and `~` with NumPy arrays, are these Python bitwise operators  
  or NumPy specific logical operators?
:::

Exercise 5 can be done efficiently without loops. Exercise 6 can be done without loops too, but 
it may be less efficient than using loops. 

By default, `&`,  `|` and `~` are bitwise operators that work on integers. However, in Python 
these and other operators can be overloaded to specify how they should work on other kinds of 
objects. Numpy uses this to define how these operators behave when used with numpy arrays.


## Henry

:::{epigraph}
If Boolean indexing only selects values where the condition is True, is there a way to use False 
values to select elements instead?
:::

The easiest way is to use the negation operator `~` to reverse `True` and `False` values in an array. 
For example, if `arr` is a Boolean array then `~arr` will be an array that has `True` in places 
where `arr` has `False` and vice verse.



## Berkley

:::{epigraph}
For the image denoising project, are we using the provided photos, or do we need to pick our own?
:::


You can pick your own photos it you wish, but you need to either pick grayscale photos (or convert 
color photos into grayscale), since in this project for simplicity we are working with grayscale images. 

## Brianna

:::{epigraph}
When exactly is our next project report due? Also are we allowed to work together for project reports or no?
:::

The project is due by the end of Saturday, 2/28. You can work together, but everyone has to write the report 
on their own and must be able to explain any piece of code included in the report. No AI tools are allowed. 

## Jarrod

:::{epigraph}
Is there a way to stretch an image uploaded to jupyter notebook by manipulating the array? 
is there a way to change an image to look like a fish lense using jupyter notebook? 
:::

Both of these are possible. Stretching an image is not difficult to implement from scratch. 
Fish lens effect is more complicated, it is easier to do it using specialized Python libraries 
for image manipulation. 

## Aidan

:::{epigraph}
Are the algorithms used by things like our camera app to de-noise images really as simple as the ones 
we're building in class? I feel like they should be far more complicated.
:::

Some algorithms are more complicated, but they essentially build on mean and median filters and then 
try to improve them. There are also algorithms for correcting other types of noise in images 
(i.e. Gaussian noise), and they tend to use more complex ideas. Nowadays, there are also AI tools that 
can be used for noise removal, but their effect is less predictable. They can also hallucinate what should 
be in an image rather than just trying to improve image quality. 

## Christian

:::{epigraph}
In real-world data analysis when would Boolean arrays be useful?
:::

They are commonly used to filter and manipulate data. For example, if you have an array where rows are representing 
students and columns are exams scores, then you can use Boolean arrays to e.g. select students with scores that are
above average or who missed some exams.

































<br/><br/>
