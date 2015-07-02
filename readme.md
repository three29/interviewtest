Three29 Web Developer Test

Requirements:
- build a page that has 4 divs and they look exactly like in the screenshots provided at the end of this requirements
- use the template provided in this repository
- initial state of each div:
#div1 - has width 25%, a responsive background image ( see $cover_image ), on click width becomes 100%
#div2 - has width 75&, background color orange, contains a random image from $random_images array - every refresh should pull a random image, on click width becomes 100%
#div3 - has width 50%, background color blue, on click width becomes 100% and background color animates into a red
#div4 - has with 90%, shows an iteration of numbers (see details below)
- iteration of numbers: using a SINGLE for loop and no arrays please output: 1 3 5 7 9 7 5 3 1
- the page needs to be responsive - all divs will fill in the entire vertical space - please see screenshot - if page resizes their sizes are changed accordingly see screenshot 
- when you click one of the divs (#div1,#div2, #div3, #div4) their state needs to toogle
    - example: - if you click #div1 - width goes 100% - if you click again it goes back to initial state ( width 25%) - if you click again it goes back to width 100% etc
               - if you click #div2 - width goes 100% - the image is still centered - if you click again it goes back to initial state - if you click again it goes back to width 100% etc
               - if you click #div3 - width goes 100% and at the same time the background color changes to red - if you click again it goes back to initial state (background color as well) - if you click again it goes back to width 100% and background color red etc
               - if you click #div4 - width goes 100% - the text is always centered -  if you click again it goes back to initial state - if you click again it goes back to width 100% etc
               
- IMPORTANT! For every click on any of the divs (#div1, #div2, #div3, #div4) you need to make an AJAX call and save a cookie with the state of that div - if you refresh the page the div should have the same state as the last time you clicked it:
    - example: - if I click #div1  
    
- Other: you can use and change anything you want, use as many php variables, css classes, any javascript libraries you want etc

Working example and screenshots:
Full screen
![screenshot](https://s3-us-west-1.amazonaws.com/three29/screenshot1.png)

Responsive
![screenshot](https://s3-us-west-1.amazonaws.com/three29/screenshot2.png)

Video of working examples and what needs to happen
https://s3-us-west-1.amazonaws.com/three29/testexample.mov

Good Luck!
