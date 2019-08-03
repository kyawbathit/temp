
# Exercises

## Exercise 1
Create web page where you introduce yourself. It should only have a headline, an image and some text.

- Accomplish the above without styling any of the elements
- Add inline styles.
- Add a reference to an external css file and transfer the styling to this file.


## Exercise 2

Create and index.html with the follow hierachy:

```
<div id="container">
    <div>
        <p>
            First p tag in first div child
        </p>
        <p class="cool-style">
            Second p tag in first div child
        </p>
    </div>
    <div>
        <ul>
            <li>
                First li tag in second div child
            </li>
            <li>
                Second li tag in second div child
            </li>
        </ul>
    </div>
    <div>
        <ul>
            <li>
                Li tag in third div child
            </li>
        </ul>
        <p class="cool-style">
            P tag in third div child
        </p>
    </div>
</div>

```
Create an external main.css file and add a reference in the index.html.
Do not add ids or classes to the tags. Now add the following specific styles:

- select all tags. Add blue font color
- select all li tags. Add red font color
- select the second p tag in the first div child. Add green color to the font. Hint: use the nth-child selector 
- select the li tag in the third div child. remove the dot
- select the elements that have a class of 'cool-style'. Add some cool styling. 


Now add your own improved styles so the hierachy becomes visible/obvious to the viewer.
  
## Exercise 4

You have been hired to create a website for at company. It has to have the structure that is depicted below. 

![alt text](https://github.com/senner007/temp/blob/master/img_sem_elements.png "Logo Title Text 1")

- use div tags only
- use semantic tags
