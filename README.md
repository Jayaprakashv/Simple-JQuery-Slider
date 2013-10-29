# [Simple JQuey Slider ](http://jayaprakashav.com)
 

## Quick start

Stage 1

1) Load the script on document ready.

2) Grab the first slide and add a class 'active' to it so we know which slide we are dealing with.

3) Hide all slides and show active slide. So now slide #1 is display block and all the rest are display:none;


Stage 2 Working with the button-next click event.

1) Remove the current active class from the slide that will be disappearing and give it the class oldActive so we know that it is on it's way out.

2) Next is an if statement to check if we are at the end of the slideshow and need to return to the start again. It checks if oldActive (i.e. the outgoing slide) is the last child. If it is, then go back to the first child and make it 'active'. If it's not the last child, then just grab the next element (using .next() ) and give it class active.

3) We remove the class oldActive because it's no longer needed.

4) fadeOut all of the slides

5) fade In the active slides


Step 3

Same as in step two but using some reverse logic for traversing through the elements backwards.

It's important to note there are thousands of ways you can achieve this. This is merely my take on the situation.
 


## Features

* 


## Documentation

Coming Soon

## Contributing

Coming Soon
 
