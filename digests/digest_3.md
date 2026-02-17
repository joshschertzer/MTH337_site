# Weekly digest 3
## Joshua

:::{epigraph}
Will the projects be cumulative /  build upon each other, or will we be starting with a blank project each time?
:::
## Joseph

:::{epigraph}
How are we going to use arrays/ colormaps in the next project?
:::

The next project will deal with processing images so, as I have shown 
already, arrays and colormaps will come handy. 

## Vidhi

:::{epigraph}
How many projects will there be this semester?
:::

About six. Some may take more or less time than I plan, so this number may 
change somewhat. 


## Pierce

:::{epigraph}
How does the creation of a project with Jupyter Notebook become useful in the workplace?
:::

Jupyter Notebook is often used in exploratory data analysis or scientific in a way 
that resembles writing project reports in this class. It lets one create a documents that 
combines computations with narrative that explains what these computations mean. 

Python code itself can be run in other settings too, depending on particular applications.  



## Alyssa

:::{epigraph}
When you post the practice quizzes, would you be able to also post the solutions to the practice quizzes? 
There have been questions that I thought I understood until I took the quiz, because I didn't know 
the correct answer when studying.
:::

I don't plan on posting solutions to practice quizzes. However, in questions where you are
supposed to figure out what some code does, you can check the solution yourself: just 
copy and paste the code from the quiz to Jupyter Notebook, run it, and see what it outputs. 
Also, if you have any question about a sample quiz, you can either post it on Piazza or 
ask it in class before the actual quiz starts.


## Jenna

:::{epigraph}
Will all the projects be of the same formatting rubric?
:::

In general, yes. There may be some project that will include coding only, no narrative, 
but if so, it will be clearly indicated. 


## Jaimie

:::{epigraph}
Are there a set number of projects we will be completing throughout the semester? 
:::

I am aiming for six. Some project may take more or less time than I plan, so this number may 
change somewhat. 


## Dixith

:::{epigraph}
When we reshape an array, how do we know if it makes a new array or just changes 
the way we look at the same data 
:::

With numpy, slicing and reshaping produce views of the original array. This means that 
modifying a sliced or reshaped array modifies the original. To make sure that this does not 
happen, create a copy of an array before making changes. If `arr` is the original, then 
execute `arr2 = arr.copy()`. After that, modifying `arr2` will have no impact on `arr`. 

## Alan

:::{epigraph}
Can we get a crash course on exercise 4 from this past week? The one about the bands? 
:::


Below is one way it can be done. It involves one `for` loop that creates smaller and smaller 
squares filled with either zeros or ones. It is possible to do it without a loop, but it would be a bit 
more complicated. 

:::{code} python
import numpy as np

def bands(n):
    
    arr = np.zeros((n, n), dtype=int)
    for i in range(1, n//2 + 1):
        arr[i:-i, i:-i] = i % 2
    return arr
:::

## Ryan

:::{epigraph}
I saw that the project are a big portion of our grade. How many projects are we going to 
have throughout the semester?
:::

About six. Some project may take more or less time than I plan, so this number may 
change somewhat. 

## Rodrigo

:::{epigraph}
Aside from the grade and rubric, will any other feedback be given on projects? 
:::

Yes, you will get detailed feedback.


## Henry

:::{epigraph}
How does python handle image data internally when doing edits? 
:::

`plt.imread()` and `iio.imread()` convert image data into a numpy array. 
The rest are just computations on elements of this array. 


## Brianna

:::{epigraph}
Well I was wondering if we could have more examples and information on how to write our project 
reports? Like more of a laid out example of what you want so we can execute it better.
:::

In graded reports for project 1, I included comments on what I liked and what should be improved. 
I hope it will clarify the expectations. I can also answer any additional questions. 


## Shane

:::{epigraph}
When do you think the projects will be back and graded?
:::

I am finishing grading as I write this. 


## Erica

:::{epigraph}
When will the next project be due?
:::

Probably on Friday next week.


## Christian

:::{epigraph}
What's the must complicated or interesting thing you can do with a photo on python?
:::

I guess this is a matter of opinion. You can do any sort of image manipulation, 
you can write code to recognize objects or people in images etc. 


## Bernice

:::{epigraph}
Have mathematicians found what number creates the longest Collatz sequence?
:::

There is no such number. Collatz sequence that starts with $2^n$ has length 
$n$. Since $n$ is abritrary, this gives Collatz sequences of any length. 

## Berkley

:::{epigraph}
Are there any real-world applications of creating the colored/patterned graphs from matrices? 
:::

Sure, this is commonly used to create computer graphics. It is also used to 
visualize data contained in matrices and we will use it later in this course. 


## Daniel

:::{epigraph}
How long until we get our grades for the collatz sequences project?
:::

Grading is mostly done as I type this.


## Aidan

:::{epigraph}
Is there a maximum number of lines of code that can be included 
in one cell in Jupyter?
:::

I don't think there is any technical limit for that, but Jupyter Notebook 
is intended for content that combines narrative and relatively short code snippets. 
For large coding projects there are other tools.

## Muhammed

:::{epigraph}
Are projects graded with a curve?
:::

No. I am not sure how it would work in this context. 



<br/><br/>
