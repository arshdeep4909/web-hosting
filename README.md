# moshify

typo graphy

-includes all the typography defined along with the font adjusted for responsiveness

Links

-defined the ornage color arrow link in this and also made it responsive
-added the color property in this as well

Badges

-these includes the 10% off badges defined in the card component of the webpage & the list of badges right above the card and below the search button
-these are of two types a normal one and one included in the popular card
-they just have a different skin

Icons

-adding small icons that appear almost every where in the webpage
-using a sprite to cobine all the icons
-styling includes defining different skins as well as different
container style

buttons

-so we divided buttons based on - upon their skin & based upon their width property

- one was takingthe size of container and other just to fit the content - also one was outline button which was just the part
  of the card block

Input group

- creating the input group along with the button
  -crating both component in the same div to give the
  illusion of a single element
- finished creating the whole block and giving it all the styles

cards

-creating a basic structure of a card
-just defining a header and different skins for the header
-defining a body and just a basic layout, the padding, text color etc

plan

- created the complete card component including the list
- used the card component build befoer and then added badges and list
  components which were previously created
- Also create a new class and then used pseudo selector to add the
  popular badge on the plan
- a better approach then adding the popular badge mannualy

media

-just created a normal layout for the media object
-did not define the color and back ground and will fine
tune later when we define the block in which it is layed out

quotes

-here we just created the quotes component without the image

- we did this because we can have some quotes in the future that might not include an image
- we used pseudo to add quotes before and after
- the author section was a media section so we added media
  section and styled it according to our needs

grid

-just defined a normal grid with two and three colums
-made it reponsive with breaking points
"# web-hosting"
"# web-hosting"

Callout

-ready to get started section

- used a grid and then previous classes such as buttons
- used media querries to make a lot of subtle changes

Collapsible

- creating the footer slider which shows the content on clicking
  -used javascript to add a class
- and then in our style sheet we defined the visibility when
  that particular class was present .

Block

-just defining the layout of a normal block that is used
various times in this page

- This is defined in a dark skewed pattern and also in a white pattern
  just below plan
- using clip path to get the skewed block
- block header can be used to align items in the
  header at center

Navigation Bar

- the top menu section that contains a collapsible list
- used the previouly built collapsible component to
  design the block
- a lot of critical adjustments very importnat here

Hero

- the top most component with the black background
- used gird-1X2 and block component in sync to get
  the layout
  -texta align was to be adjusted for larger screens

Domain-block

- using the block to get the header align to center
- the input group was already created
- we used grid to make list responsive

Features block

- building out the side content pannel manually
  -then adding the image
- using grid--1X2
- using order property to switch the order for each alternate feature
- all the content is contained within a container block

Showcase Block

- we put everything within a section
- used grid--1X2
- put heading outside the grid
- everthing was withing a section, and the
  section was dark block
- the grid and image was withing a div, which
  had a class of container and grid
- the image was then set to have width auto but
  max-width of 700px, prevents it from being violently
  big
- visibility is visible by default, so we set the
  justify self to end and let a part of it be outside the screen

Testimonial Block

- everything enclosed within a section with a
  class of block
- after heading we enclosed the image and quotes section
  within a div and then gave it a class of grid--1X2
  and container (so it has a max-width).

Footer

-use the block the conatiner

- using collapsibles that we previously built
- using grid , to make the layout responsive
- used order function to make the logo appear
  first on thr grid on dekstop
- also used list to define list within
  the collapsibles
