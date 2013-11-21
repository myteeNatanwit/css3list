Css3 list
=========

I got the idea of this app while doing experiment with rbga(red, blue, green and Alpha). Ive been staying with opacity long, long time and had so much trouble to lay several divs on top each other to create rbga effect. Man! spending few hours reading ab Css3 saving me few days work. Phew!

Try this in a resized to phone screen, you can c it works correctly while on browser screen it looks real bad.

Just have a play with the source code, having fun with the numbers, change them, make them big number, or small one to see the effect. That how I did.

The idea is to use :active, :before, :after, :hover in Css3 for the effect.
The screen is divided in 3 divs, top, left, and right. The top is the Tab panel, 2 tabs. The left with position:fixed; width:20%. The right div, position: absolute, margin-left:20% so it stays next to the left div. 
2 background imgs for the left div are the foot path and the home pngs. You can just change them to anything, provided new pngs must be alpha supported.
The list backgound is rbga(0,0,0,0.6), the a:after with arrow img.

The tabs are the radio input, but hidden, active however. They link to the article panel to show the content. Why using article? oh! experiment. You can change it to div.

There is no Javascript, no Jquery in this template. Only Css3. Obviously it does nothing yet. The active parts were cut off as it is an submitted app for airport ternimal navigator. You can do anything with the code by following:
1- Delete the copyright div if there is any ;-), or put your name there if u wish.
2- Add the script section with document.ready or $(function () {}); and bind("click", fn.... to the elements, or using ajax by put the link in href# in the list item.
3-dont forget to have a link back to the index.
4-set the link to the "leftpanel" as it should show the terminal map. Get the map in large size with pinch enabled so that user can find "you are here" pot.

Bugs?
none, as far as I known, but there is room for improvement ..ie icons dont look good, toilet doesnt show, however, your version should be better.
