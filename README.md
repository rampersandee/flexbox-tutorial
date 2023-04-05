# flexbox-tutorial

**********************
<h3>Greetings, loved ones.
               -R&y</h3>
<h4>This is just a little tutorial a made in order to help folx in my 2023a Resilient Coders cohort better understand the beast that is 'flexbox.'</h2>

<p>I created what is essentially a "playground" for understanding flex with examples written in the code.  I provide HTML and CSS depicting several ways to use flex through a combination of &lt;section&gt; and &lt;div&gt; tags<br><br> 
Here's what ChatGPT says about using 'flex' properties such as 'flex,' 'flex-grow,' and 'flex-shrink':<br>
<em>And with examples no less</em></p>

Example 1:


```.container {
  display: flex;
}

.box {
  flex: 1 1 auto;
}
```
In this example, we have a container element with display: flex; set, which makes it a flex container. Inside the container, we have a child element with the class .box which has flex: 1 1 auto; set. This means that the child element will take up all available space within the container, and will also shrink and grow as necessary to fill the available space.

Example 2:

```
.container {
  display: flex;
  flex-direction: row;
}

.box {
  flex: 1 1 auto;
}
```
In this example, we have a container element with display: flex; and flex-direction: row; set, which makes it a flex container that arranges its child elements in a row. Inside the container, we have a child element with the class .box which has flex: 1 1 auto; set. This means that the child element will take up all available space within the row, and will also shrink and grow as necessary to fill the available space.

Example 3:

```
.container {
  display: flex;
  flex-direction: column;
}

.box {
  flex: 1 1 auto;
}
```
In this example, we have a container element with display: flex; and flex-direction: column; set, which makes it a flex container that arranges its child elements in a column. Inside the container, we have a child element with the class .box which has flex: 1 1 auto; set. This means that the child element will take up all available space within the column, and will also shrink and grow as necessary to fill the available space.

In all of these examples, flex: 1 1 auto; is used to make the child element fill the available space and also grow and shrink as necessary to fit the available space. The 1 1 auto values represent the flex-grow, flex-shrink, and flex-basis properties respectively. 1 1 means that the element will grow and shrink equally with the other elements in the container, and auto means that the initial size of the element will be based on its content size.

<em>I hope my guide was helpful to anyone who lays eyes on it.<br>
Thank you and be blessed.</em>
