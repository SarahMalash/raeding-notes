# read 8
## Lists:
**Ordered lists:** numbered list. The ordered list is created with
the < ol> element, < li> contains each item.
**Unordered lists:** bullit points. created with the <ul> element, < li> contains each item.
**Definition lists:** are made up of a set of terms along with the definitions for each of those terms, created with the < dl> element, < dt> This is used to contain the term being defined, < dd> This is used to contain the definition.
### Nested List:
 You can put a second list inside an < li> element to create a sublist or nested list.

 # Box Dimensions: 
 By default a box is sized just big enough to hold its contents, To set your own dimensions for a box you can use the height and width properties. (hight, width ( pixels, percentages, or ems))
  **percentages:** the size of the box is relative.
  **ems:** the size of the box is based on the size of text within it.
  **pixels:** most popular method because they allow designers to accurately control their size.
  ## limiting hight and width:
  (min-width, max-width), (min-height, max-height)
  # What if the content is larger than the Box that contains it?
  **use overflow to tell the browser what to with the extra content, you can hide it using (hidden) and (scroll)**
  ## Border, Margin and padding:
  ### Border: 
  **each box has a border when we spicify border for a box we spicify the space between a box and another.**
  ### Margin: 
  **Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.**
  ### Padding: 
  **Padding is the space between the border of a box and any content contained within it.**
  A border can have a style (solid, dotted, dashe...ect) and a color for all sides or eah side might have it's own color.

  # Change Inline/Block:
  allows you to turn a block element to an inline element and vise versa.

# Hiding Boxes:
hidden boxes from the user but they creat spaces.
## Border Styling:
Images: add a sliced image to your border.
Shadows:shadow around a box
Roundes Corners: using a poperty called border-radius.

# switch:
You have a default option that is run if none of the cases match, If a match is found, that code is run; then
the break statement stops the rest of the switch statement running (providing better performance than multiple if statements).
## TRUTHY & FALSY VALUES:
**falsy values:**
Traditional False Value: false;
The Number 0: 0;
Not a Number (nan): 10/'score'
Empty Value: ''
A variable with no value assigned to it: var value =
**Truthy Value:** everything that is not in the falsy table can be treated as if it were true. 
# Loops:
checks condition if true runs command untill the run times equals the counter.