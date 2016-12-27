# interactiveMap
version 0.2;

This is a very early, alpha version.

Instructions for each button:

Clear:  
  Clears the canvas of all points and images. Resets the internal storage of link points. This process is irreversable.  
Add Link:  
  Add a single link from the textarea below the buttons. The first link is stripped from the textarea when you click on the canvas (which will place a point that persists).  
Add Links:  
  Similar to 'Add Link' but allows you to add links to the canvas in batches. Each click on the canvas will place a new point on the canvas that will be associated with the first link inside the textfield at the time of clicking. Each click will strip the first link. If you want two or more points to have the same link, you need to paste the link for each point inside the text field.  
View / Edit:  
  Clicking this button will allow you to click on any points that have already been placed on the canvas. This will display the point's location data and any link that is associated with it. If you want to change the link, you can click on the 'Link Data' and supply a new link. Points can be placed on the canvas with an empty textarea, so using the 'View / Edit' button can allow you to add links to empty points.  
Add Map Image:  
  This will add an image as the background to the canvas. Points are drawn on top of this image. Like the links for points, paste an image link inside the textarea then click the button.  
Interact:  
  Clicking this button allows you to click on existing points on the canvas and open the associated links.  

Misc:  
  Clicking on the bottom half of the control box will close any output that's been displayed.  
  There's no link validation, so you need to make sure to use valid links.  
