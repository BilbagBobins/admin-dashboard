# Admin Dashboard

## <u>The Brief</u>
This is the Admin Dashboard project as part of The Odin Project.

We are required to build a full dashboard design webpage based off a provided sample design. It is a layout project and will not have any functionality at this stage. It is advised that we lean heavily on CSS Grid for the layout as that is what the lessons leading up to this project have been focusing on.

<img src="file:///home/aaron/Coding/repos/admin-dashboard/img/dashboard-project-small.png" width="600" height="400" />

We are to gather assets like SVGs, fonts and other images to recreate the design in our own style.

## <u>The Build</u>
As per the brief, I leant heavily on GRID for the layout. There were a couple of elements that I resorted to FLEX because it just worked better:

* The sidebar I went with a FLEX column because it allowed me to space out the separate lists as well as the footer.

* The project icons instead of creating a grid and then assigning the columns to each icon FLEX allowed me to position the icons in a more efficient way.

I added a `:hover` pseudo-class to most of the elements to make things more interactive and interesting.

One CSS method of note that I implemented on this project was the function of changing the color of an image. The method was mentioned by [Manish Menaria on Stack Overflow](https://stackoverflow.com/questions/22252472/how-to-change-the-color-of-an-svg-element/53336754#53336754 ) who has built [a function](https://codepen.io/sosuke/pen/Pjoqqp) which takes a CSS color value and spits out a bunch of values for a CSS filter property. The caveat is that the original color of the image must be black.

I utilised this filter function for the `:hover` pseudo-class of the main logo.

