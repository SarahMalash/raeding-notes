# read 12
*Creating a Chart: nedds a script and a single <canvas> node to render the chart.*
## canvas:
 <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes
  <canvas> element has only two attributes, width and height.
  The <canvas> element can be styled just like any normal image
  unlike the <img> element, the <canvas> element requires the closing tag (</canvas>)
  The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it.
  The <canvas> element has a method called getContext(), used to obtain the rendering context and its drawing functions.

# Drawing rectangle:
<canvas> only supports two primitive shapes: *rectangles and paths*
(All other shapes must be created by combining one or more paths)
fillRect() function draws a large black square
clearRect() function then erases a square from the center 
strokeRect() is called to create a rectangular outline 50x50 pixels within the cleared square

# Drawing paths
1. create the path.
2. use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.

beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
Path methods
Methods to set different paths for objects.
closePath()
Adds a straight line to the path, going to the start of the current sub-path.
stroke()
Draws the shape by stroking its outline.
fill()
Draws a solid shape by filling the path's content area.
# Moving the pen:
moveTo() function
moveTo(x, y)
Moves the pen to the coordinates specified by x and y.

# Colors:
fillStyle = color (Sets the style used when filling shapes)
strokeStyle = color (Sets the style for shapes' outlines)
strokeStyle property to change the colors of the shapes' outlines.
# Line styles:
lineWidth = value (Sets the width of lines drawn in the future)
lineCap = type (Sets the appearance of the ends of lines)
lineJoin = type (Sets the appearance of the "corners" where lines meet)

miterLimit = value (Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes)
getLineDash() (Returns the current line dash pattern array containing an even number of non-negative numbers)

setLineDash(segments) (sets the current line dash pattern)
lineDashOffset = value (Specifies where to start a dash array on a line)
# Drawing text:
*fillText(text, x, y [, maxWidth])*
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

*strokeText(text, x, y [, maxWidth])*
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

The text is filled using the current strokeStyle.
measureText()
Returns a TextMetrics object containing the width, in pixels.
