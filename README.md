Download Link: https://assignmentchef.com/product/solved-cs2303-homework-2-loops-arrays-console-output-random-numbers-display-path-through-2d-space-2
<br>
Homework 2

loops, arrays, console output, random numbers, display path through 2D space




The objective is to give you practice with two dimensional arrays, and with linked lists.

The context of this problem is that a two dimensional metric space exists, not centered on coordinates (0,0), but rather, offset, such that the leftmost bottom corner is at 0,0, and all other locations have at least one positive integer. Your code will navigate an object within this space, and show the trail it followed. The problem to be solved:

A display screen is to be modeled as having 20 x 20 “fat” pixels (These are regions of the screen consisting of more than one pixel on each side.). You should model this screen as an array with 20 x 20 locations. Initialize the content of your array to all zeros. Use a random number generator, and modular arithmetic, to choose a location on this screen, in which to start. Seed the random number generator such that the list of random numbers is not the same every time you run your code. We think of a marker being at that point. Fill that array location with an (initially 1) index. Next, make your marker wander randomly. You might wish to create this appearance by making a new marker each time. Use the next index each time. Each time the marker “moves”, print the display, with the index number showing. Note that a marker may reuse a location. The display should show the most recent index.

As your marker wanders through the array, you should also record every marker location in a linked list.

After the wandering is over, traverse the linked list, printing the index and location of the path travelled.

<ul>

 <li>Construct a sequence diagram for your project. You can draw it by hand and include a phone/photo, or draw it with a software tool.</li>

 <li>Use the test-driven development style for developing your code. Document this for each production function by:</li>

</ul>

<ol>

 <li>Write your function prototype, test function and stub implementation.</li>

 <li>Run your test function (which should invoke the stub and notice thatthe stub is insufficient as an implementation).</li>

</ol>

Figure 1: In the process of creating a new test.

Figure 2: Starting some production code.

<ol start="3">

 <li>Take a screen shot showing the stub function and the report of itsfailure (The “before” screenshot).</li>

 <li>Modify your stub to do its job.</li>

 <li>Run your test function (If the implementation is right, this shouldbe observed.).</li>

 <li>Take a screen shot showing the replacement of the stub and its testresults. (The “after” screenshot).</li>

</ol>

Be sure to run your code every time you add a few lines of test or production code. (See Figures 2 and 3.) Do not allow the number of warnings and errors to get large.

<ul>

 <li>Imagine a function for placing a marker in the array. Choose a known (not a random number) location. Build a test that checks for this.</li>

 <li>Imagine “moving”the marker (adding successive markers). To do this, it will probably help a lot to have a function that will print the array, for</li>

</ul>

Figure 3: Adding more production code.

example, ’|’ between horizontally adjacent cells, and ’ ’ between vertically adjacent cells. Don’t worry about underlining the marked location. By printing the array between moves of the marker, you should be able to see the result of your code running. Build a test for this display function. You can populate the array with known data, print it, and check it (by eye if you wish).

<ul>

 <li>Use a loop to “move” the marker multiple times. Ihe index value of the marker should increase; show it as modulo 10, in the array printout, so the field is always 1 character wide. Build a test function that checks the length of your marker path.</li>

 <li>There are several linked list functions provided in starter code. You should read this code for understanding. Test that you can create an empty linked list. Test that you can create a linked list of length 1. Test that you can add elements onto the end of this list.</li>

 <li>Print, from the linked list the path the marker takes through the space. Test that the list you produce matches the list your code prints. There should be several test cases. Length zero, length 1, length greater than 1.</li>

</ul>

Things to do:

<ol>

 <li>Either:

  <ul>

   <li>Make a C project from the Hello,World project.</li>

   <li>Populate that project with tests.c, tests.h, production.c and production .h.</li>

  </ul></li>

</ol>

or use the starter code.

<ol start="2">

 <li>Create the sequence diagram and include the electronic file (diagram,screenshot or photo). Make sure your name appears within the sequence diagram.</li>

 <li>Place function prototypes for all of your functions from the sequence diagram into .h files.</li>

 <li>As you work on the assignment, collect a sequence of befroe-and-afterscreen shots showing how your production code is growing.</li>

</ol>

<ol start="5">

 <li>Be sure to build and run often; do not allow warnings and errors to buildup.</li>

 <li>Show the sequence of moves by listing them, and also show the final paththrough the 2D space.</li>

</ol>


