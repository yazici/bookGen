bookGen
=======


BookGen is a free  book-generation addon for the open-source 3D-package Blender.
It allows you to fill shelfs or cupboards with books – fast and easy.

##Features:##

  - control width, height, depth, cover thickness and more parameters of the books
  - use randomization to generate a variety of different books
  - subsurf-ready
  - automatic uv-unwrap for texturing

##Installation:##

  - Download the .zip
  - Open Blender, click on “File” and open the “User Preferences”
  - Switch to the addons-tab  and click on “install from File”
  - Choose the .zip and click “install”
  - Now Activate it by clicking on the checkbox next to it. Done.

##Demo:##

  https://vimeo.com/90801687

##Getting started:##

After you installed the Blender addon as described above you can start it by clicking on “Add”. In the “mesh”-category you will find “Add Books”. If you click on that you will see some books in the 3D-Viewport. You can now use the settings in the operator panel to change the amount and the look of your books.

##Options:##

At the top of the operator panel you will find settings affecting all books:

  - width: changes the width of all books together. This is normally the width of your shelf.
  - scale : changes the overall scale of your books. This does not effect the books proportions.
  - seed: changes the random numbers. It allows you to get different layouts with the same settings.
  - spacing: changes the spacing between two books. You can adjust the randomness by changing the slider next to it.
  - x-y: changes the axis on the which the books are distributed

The first box contains settings to change the proportions of your books:

  - height: changes the height of your books. You can again adjust the randomness by changing the slider next to it.
  - depth: changes the depth of your books. I think knew it: You can adjust the randomness by changing the slider next to it.
  - width: changes the width of your individual books. I think you got the randomness thing now.

The second box changes the details of the generated books:

  - textblock-offset: changes the offset between cover size and textblock size
  - cover-thickness: changes the thickness of the books covers
  - spline-curl: changes how bulgy the back of the books are.
  - hinge-inset: changes the inset at the hinge
  - hinge-width: changes the width of the hinge

Below those boxes there are some additional options:

  - Add Subsurf-Modifier: adds a subdivision surface modifier to your books.
  - shade smooth: set the shading of all books to smooth
  - unwrap: auto-unwrap all books generated by the bookGen addon

##Roadmap:##

  - [ ] stacking of books with random z-axis-rotation
  - [x] distributing books along a custom axis
  - [x] control the alignment of books (e.g. align backs)
  - [ ] allow leaning of books
  - [ ] distribute books based on groundplanes

##License:##

© Copyright Oliver Weissbarth 2014. This addon is licensed under GPLv3.

##Issues:##

As this is still in Alpha state serious issues are possible. If you do find any bugs please use the issue tracker, email me at mail@oweissbarth.de or use the contact form at www.oweissbarth.de/contact.
