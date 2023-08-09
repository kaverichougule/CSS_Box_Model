Hostel Link: https://kaverichougule.github.io/CSS_Box_Model/

# Box Model
![image](https://github.com/kaverichougule/CSS_Box_Model/assets/101037685/0eeac905-d434-467c-95e7-33ddeb2d82c2)
index.html: <br>
'div class="frame"': This <div> acts as a frame for the painting. <br>
It has a black border, padding, and margins for creating spacing around the painting. <br> 
It contains a <div> with the class canvas. <br><br>
'div class="canvas"': This is the canvas of the painting, where the colored rectangles will be displayed. <br>
It has a fixed width and height, and the background color is set to a dark reddish-brown. <br>
The overflow: hidden; property ensures that any content exceeding the canvas size is hidden. <br>
A blur(2px) filter is applied to the canvas to give it a slightly blurred appearance. <br>
Three 'div' elements with classes one, two, and three: These represent the colored rectangles on the canvas. <br>
<br>
style.css <br> 
.canvas: This class styles the canvas.  <br>
It sets a fixed width and height, background color, and applies a blur filter. <br>
The filter adds a subtle blurred effect to the canvas. <br><br>
.frame: This class styles the frame surrounding the canvas.  <br>
It adds a black border, padding, and margins to create a framed appearance. <br><br>
.one, .two, .three: These classes style the colored rectangles on the canvas. <br>
Each rectangle has a distinct size, background color, margins, and box shadow. <br>
The transform property is used to apply a slight rotation to the rectangles for a dynamic look. <br>
A blur filter is applied to the first two rectangles, giving them a blurred effect. <br>
The third rectangle has a different background color, a larger box shadow, and a more complex border-radius to create an irregular shape <br>
