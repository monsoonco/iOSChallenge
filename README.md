#Monsoon iOS

You have been handed the included PSD.  Your assignment is to build a View Controller from that PSD.  You will find the assets you need in the assets folder.  All other graphics should be generated in code.  

This View Controller is part of an app that helps people to choose what they want to eat from a set of six prompts.  There should be a way (either as a property or a method) to read the choices made by the user.  

The View Controller must contain the following elements:

###Navigation Bar
A Navigation bar that contains four buttons:
- search
- Calendar
- compass
- menu
These buttons do not need to go anywhere but should have a consistent tap state

###Custom UIControl

A set of six custom UIControls (or one Custom UIControl subclass instantiated six times) that when pressed cycle between a limited number of choices.  

For each control the number of choices is demonstrated by the number of arcs around the circle.  They function the same way as segmented controls.  

Starting from the upper right and moving across each control has the following choices that it will cycle between:

1. one of a kind / small batch / large batch / mass market

2. savory / sweet / umami

3. spicy / mild

4. crunchy / mushy / smooth

5. a little / a lot

6. breakfast / brunch / lunch / snack / dinner


###Buttons

1. A randomize button that will set the UIControls to a random set of choices

2. A go button that will move to the next View Controller

### Bonus Points
1. Animations (and sound)for when the for randomize button is pressed 
2. Custom animation in or out of this VC
3. The Custom UIControl you create is accessible via storyboard. 

The goal here is to create the View Controller to be as functional as possible, and as Pixel perfect as possible with code that is self documenting, and easily understandable by another developer.  

Please post your completed Xcode project to Github and share a link with andrew[at]monsoonco[dot]com. 

If you have any questions feel free to reach out to andrew[at]monsoonco[dot]com. 

