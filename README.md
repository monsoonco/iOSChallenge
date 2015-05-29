#Monsoon iOS

You have been handed the included PSD.  Your assignment is to build a View Controller from that PSD.  You will find the assets you need in the assets folder.  All other graphics should be generated in code.  

This View Controller is part of an app that helps people choose what they want to eat from a set of six prompts.  There should be a way (either as a property or a method) to read the choices made by the user.

The View Controller must contain the following elements:

###Navigation Bar
A Navigation bar that contains four buttons:
- Search
- Calendar
- Compass
- Menu
These buttons do not need to go anywhere but should have a consistent tap state.

###Custom UIControl

A set of six custom UIControls (or one Custom UIControl subclass instantiated six times) that when pressed cycle between a limited number of choices.  

For each control the number of choices is demonstrated by the number of arcs around the circle. The user will be able to see which option they are on by the different color of the selected arc.

Starting from the left arc and moving clockwise, each control has the following choices:

1. one of a kind / mass market / small batch / large batch

2. savory / sweet / umami

3. crunchy / mushy / smooth

4. spicy / mild

5. a little / a lot

6. breakfast / brunch / lunch / snack / dinner


###Buttons

1. A randomize button that will randomly select a new selection for each UIControls.

2. A go button that will move to the next View Controller where you would display the selected options of each control

### Bonus Points
1. Animations (and sound)for when the for randomize button is pressed 
2. Custom animation in or out of this VC to the detail page
3. The Custom UIControl you create is accessible via storyboard. 

The goal here is to create the View Controller to be as functional as possible, and look as good as the sample image on all iPhone sizes (4s+) with code that is self documenting, and easily understandable by another developer.  

If you have any questions feel free to reach out to eric@monsoonco.com. When you have completed the test, please post your completed Xcode project to Github and share a link to the person who administered you the test.

