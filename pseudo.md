"responsive layout"

xs = phones
s = tablets
md = "desktops" (i think laptops here)
lg = "larger desktops (more desktops)

when coding a column, you set the width of the column based on the size of the window.

so, if a column is:
    col-xs-12, it will act as size 12 when the screen is extra small.
        but in the same class name, if there is say, a col-lg-6, then when the viewport/window is of "large" size, the col will act as a size 6. nifty!


so if i want a column to always take up the length of the page when the window reaches a certain size, i would code it as "make a column take the whole page when the page width is _blank_", otherwise for this size make it this width... etc.

if i leave everthing as xs, everything will try to just display on the page as usual.

for the hw, 
    640px is "s"
    768px is "m"
    980px is "l"

    i think. it could also be xs s m.





everything needs to be its own movable object. 

first, fix the code so it works without any sort of screen.
    then, make it so the pieces will resize with the size of the window.
    On xs and sm screens, each section should take up the entire grid. On m and larger screens, each section should take up 2/3 of the grid and the sidebar should take up 1/3 of the grid

    so, should be col-xs-12 for main and side bar.
    then, col-m-8 for main, and col-m-4 for sidebar so it shifts for each.


when moving on to the second part using "media screen", its the same thing.



I SPENT TOO MUCH TIME TRYING TO MATCH THE PICTURES FOR PART 2 OF THE HW WITH PART 1 RIP

