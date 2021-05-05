1. 
	Test: Asked a family member to review initial app set up which had theme MCW components. 
	Feedback: There should be some uniformity and a way to know where to click.
	Modification: Added a Hamburger Menu for options and mentioned about it in instructions. 

2. 
	Test: Asked a family member to view their location using the app.
	Feedback: There should be some icon for map.
	Modification: Added map icon for Location menu. 

3.
	Test: Asked a family member to view their live coordinates using the app.
	Feedback: There should be an option to view specific coordinates. 
	Modification: Added a show coordinates button to view location which gets displayed above the map div. 

4.
	Test: Asked a family member to review the live coordinates change. 
	Feedback: " I do not want it to keep displaying entire time, it should go away after some time."
	Modification: Added a snackbar to show location coordinates which disappears after a while.

5.  
	Test: Asked the coordinates reviewer to retest the modified coordinates option. Currently it can only be viewed on the location tab.
	Feedback: There should be an option to view coordinates on all tabs not just location tab.
	Modification: Added show coordinates button on all menu tabs. 

6.
	Test: Asked another family member to finally meet location expectations. Currently circle color doesn't match app bar theme.
	Feedback: The location circle color should match the app bar color.
	Modification: Changed the fill color of location circle from orange to green. 

7.  
	Test: Asked a friend to review theme and location tab match. 
	Feedback: The coordinate snackbar is dark color but map is light theme, it should match. 
	Modification: Added styles to the map to make it darker.

8. 
	Test: Asked a friend to try speech. 
	Feedback: There should be some identification on the Speak Button. 
	Modification: Added an icon on the Speak Button.

9.  Test: Asked a friend to review the updated speech button. 
    Feedback: Earlier they thought they couldn't identify the button but now they feel speech is not working. 
    Modification: I realized that show coordinates and speak buttons had same classes and hence eventListeners would pick only the first one. Hence changed the identification classes for Speak button.