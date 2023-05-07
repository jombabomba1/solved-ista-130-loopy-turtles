Download Link: https://assignmentchef.com/product/solved-ista-130-loopy-turtles
<br>
Please read the instructions below carefully and follow them closely. All problems (and parts of problems) are required except as noted in the instructions below.

<strong>Important: </strong>Your filenames <em>must </em>be identical to the filenames given below. For any functions you are asked to write, you <em>must </em>use the <em>exact </em>function names given in the descriptions, and you <em>must </em>have parameters in the order shown in the description. Otherwise, our tests will fail.

<strong>Also Important: </strong>Make sure you <em>always </em>save a backup of your work somewhere safe (such as your UA box or <a href="https://db.tt/x6MRLis">dropbox.com</a><a href="https://db.tt/x6MRLis">)</a>.




<h1> 1 Part I: Functions with Loops (35 points)</h1>

It may help you to sketch pictures out on scratch paper before writing any code.




<h2>Polygons</h2>

Open <strong>your editor </strong>and create a new file called “polygons.py”. In the file:

<ul>

 <li>Copy the code from the “template.py” file and paste it into your new file.</li>

 <li>Update the documentation string at the top.</li>

 <li>Write a function called polygon that has 3 parameters. The first is for a turtle object. The second is for a numeric value giving the number of sides the polygon will have. The third is for a numeric value giving the length of the sides of the polygon. The function draws a <em>regular </em>polygon with the given number of sides, each side of the given length.  Make left turns only. For example, if you were to call the function like this: polygon(so<u>m</u>e_turtle, 4, 100)</li>

</ul>

it would draw a square with sides of length 100:

<ul>

 <li>If you were to call the function like this:</li>

</ul>

polygon(s<u>o</u>me_turtle, 3, 300)

it would draw an equilateral triangle with sides of length 300:

<ul>

 <li>Note: you’ll need a for loop to do this. (See  the  lecture  slides  and code for examples)</li>

 <li>If you’re having trouble, think about drawing a polygon from the tur- tle’s perspective. How many turns do you take? How much do you turn in total? How much do you turn on each individual turn?</li>

</ul>

<strong>– </strong>If you answer these questions first for a triangle, then a square, and then a pentagon, you’ll see a pattern. We also derived the answer in class using geometry (see ppt).

<ul>

 <li>In the main function definition write code that will draw the following figure (set speed to 0):</li>

 <li>Notes:

  <ul>

   <li>You’ll need to use a for loop to repeatedly call your polygon function</li>

   <li>The polygons in the figure are size 100</li>

   <li>The figure shows 3 sets of 5 polygons (triangles, squares and pentagons)</li>

   <li>The 5 polygons in a given set are offset from each other by 20. ∗ (e.g. the horizontal edge of each of the green triangles is offset by 20 from the next green triangle) ∗ The following diagram may help:</li>

  </ul></li>

</ul>




<ul>

 <li>You can choose your own colors, but use three different colors, one for each set of polygons.</li>

 <li>If you need to scale down the sizes to make the figure fit in your drawing window that is fine (e.g. instead of size 100 use 50 and instead of shifting by 20 shift by 10).</li>

 <li>From the figure you can see that three different turtles were used. You don’t have to use different turtles, but it will probably make things easier for you.</li>

 <li>It will also be easier if you start by drawing only the red pentagons. The other two sets of polygons are drawn in exactly the same way.</li>

</ul>

<ul>

 <li>Verify that your documentation makes sense and that you’ve added docu- mentation to each of your functions.</li>

 <li>Verify that your program works.</li>

 <li>Upload your file to the Program 2 Assignments folder on D2L.</li>

</ul>

<h1>2        Part II: More Loops (35 points)</h1>

It may help you to sketch pictures out on scratch paper before writing any code.

Castles

<ul>

 <li>Download the “castles.py” program posted on D2L (the same place you found this HW file).</li>

 <li>Run the file to see what it does.</li>

 <li>Update the documentation (add your name and your section leader’s)</li>

 <li>Now make the following changes to the file:

  <ul>

   <li>Copy the polygon function you wrote in Part 1 above and paste it in this file.</li>

   <li>NOTE: Use only left turns in your polygon function so that it works well with the existing code</li>

   <li>Delete the triangle function from the code.</li>

   <li>Update the code to use the polygon function instead of the triangle function you deleted.</li>

   <li>make sure it works before you go to the next step!</li>

   <li>Delete the square function from the code.</li>

   <li>Update the code to use the polygon function to draw any squares.</li>

   <li>make sure it works before you go to the next step!</li>

   <li>Change the code in main so that it draws castles in the pattern seen in the following figure, using 1 or 2 loops:</li>

  </ul></li>

</ul>




<ul>

 <li>Verify that your documentation makes sense and that you’ve added docu- mentation to each of your functions.</li>

 <li>Verify that your program works. 6.) Upload your file to the Program 2 Assignments folder on D2L.</li>

</ul>

<h1>3        Part III: Get Weird Revisited (30 points)</h1>

It may help you to sketch pictures out on scratch paper before writing any code.  Some of the wilder drawings will get shown in class.

<h2>Draw Weird Shapes</h2>

In your text editor create a <strong>new file </strong>called “drawing.py”.  In the file:

<ol>

 <li>Add the required documentation and add a main</li>

</ol>

<ul>

 <li>After this homework we’ll stop reminding you to add your docu- mentation. We’ll just assume you know to <em>always </em>add the required documentation.</li>

 <li>We’ll also assume you know how to add the main If you forget, just look at “template.py”.</li>

</ul>

<ol start="2">

 <li>Write a function called shape that draws a shape of your choice. The function should have 2 parameters. The first is for a turtle. The second is for a numeric value giving the size of shape to draw.

  <ul>

   <li>The shape <em>must </em>have some part that can be repeated inside of a loop. The function <em>must </em>use a for loop to draw the repeated part

    <ul>

     <li>It is acceptable to draw the same shape you drew in Part III of the first homework if it can be drawn using a for loop (i.e. there is something repeated in it)</li>

     <li>Otherwise it must be a new shape. Don’t use one of the shapes we’ve already written functions for in lecture, lab, or earlier in this assignment (or any simple variant of those shapes like an- other regular polygon). Be creative, draw something wacky and fun!</li>

    </ul></li>

  </ul></li>

</ol>

<ol start="3">

 <li>Write a function called rotated_shapes that has four parameters. The first parameter is for a turtle. The second parameter is the size of shape to draw.  The third parameter is the number of shapes to draw.  The fourth parameter is the angle between each shape. The function draws the requested number of shapes, each of the requested size, and each rotated from the previous shape by the requested angle.

  <ul>

   <li>For example, using the star shape from hw1: <strong>– </strong>Calling the rotat<u>e</u>d_shapes function like this: rotate<u>d</u>_shapes(s<u>o</u>me_turtle, 200, 3, 120)</li>

  </ul></li>

</ol>

Produces 3 stars, each of size 200, and each rotated by 120 de- grees from the previous star. See the following figure:

<ul>

 <li>NOTE: since your shape will be different your shapes will probably end up in different locations than those in the figure! Don’t worry about that.</li>

 <li>Calling the rotated_shapes function like this:</li>

</ul>

rotate<u>d</u>_shapes(s<u>o</u>me_turtle, 400, 10, 1)

Produces 10 stars, each of size 400, and each rotated by 1 degree from the previous. See the following figure:

<sub>                                                                                 </sub>

<ol start="4">

 <li>In the main function definition write code that will:

  <ul>

   <li>Set the turtle speed to 0</li>

   <li>Use your rotated_shapes function to draw rotated shapes in at least three different locations

    <ul>

     <li>Use different arguments each time you call the rotated_shapes function</li>

     <li>Change the pencolor before each call (or use a different turtle with a different color) For example:</li>

    </ul></li>

  </ul></li>

</ol>

c.) Note: • this will take some trial and error since you probably won’t know where your turtle will end up facing after each call to rotated_s<u>h</u>apes

<ol start="5">

 <li>Verify that your documentation makes sense and that you’ve added doc- umentation to each of your functions.</li>

 <li>Verify that your program works.</li>

 <li>Upload your file to the Program 2 Assignments folder on D2L.</li>

</ol>


