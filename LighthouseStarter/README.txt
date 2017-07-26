cis151 Lighthouse Example-
working with a page container


1) create a folder "css", create a file: "lighthouse.css" inside this folder.

2) transfer all embedded styles from index.html to the stylesheet file and
   add the link to the index.html file. Test.

3) create a folder "images" and transfer all image files into this folder. 
   Adjust all references to these files to the new location.

4) Create an h1 style definition. Add the background image file "lighthouselogo.jpg" 
   to the h1 style definition. Set the height to 100px and the width to 700px. 
   Set the font size to 3 times the default size.

5) Adjust the h1 style by adding left padding of 150px and padding to the top of 30px.

6) Add a border of 2px solid; and a border radius of 15px to the h1 style definition.

7) Add the background image file "background.jpg" to the body style definition.

8) We want to wrap the entire page content in a container to separate it from
   the background. Create a style definition id called "container" with these 
   style rules:

  - center the container horizontally by setting the right and left margin to auto.
  - apply a fixed width of 850px;
  - apply 0 padding to the top, 20px to the right and left, and 10px to the bottom.
  - make the background color white
  - apply the box-shadow property with horizontal and vertical offset of 5px, blur radius of 5px,
    and color #1e1e1e.

9) In the index.html page, create a div that references the container style definition and wraps the entire page content.

10) Modify the h1 style definition by adding a text-shadow property with horizontal and vertical offset of 3px, 
    blur radius of 3px, and color #666666.

11) Modify the h2 style definition by adding a text-shadow property with horizontal and vertical offset of 1px, 
    no blur radius, and color #cccccc.

12) Compare with the image lighthouseResult.png.