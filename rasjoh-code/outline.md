# CSS II

## Position Tag
- to start this show the image of the layered boxes with the dots.
  - talk about how we will be nesting all these items inside eachother to allow them to exist inside of them.
  - explain what parent child and siblings relationship looks like in HTML
- start by giving the body a background and a height and width to fill the screen, explain VH
- make the first inner div and talk about centering it. for the x axis use margin on the element itself, for y use padding on the parent.
- % needs the parent to have a defined value or it wont work, use it make the outer div.
  - this is a great time to show border box and how it effects padding.
- do the same for the inner div.
- put 4 divs in the inner div and make them circles.
- notice how they stack by default
- lets add posistion absolute to those and add top 0, plus give the body absolute and watch what happens.
- move absolute to the inner div, now it snaps to that one.
- move absolute to the inner most div.
- show how relative works.
- show how fixed works, might want to add double the height to the body for the full effect.
- now lets put them in the proper place.
  - show how you can add multiple classes to the same item
  - this could be a cool time to introduce css variables for the top bottom left right values

## Flex

- Most tags or options in css alter the position of itself, much like the position tags earlier, Flex is a bit different as it changes the position of the immediate children in side of it.
- put a few divs on the page and point out how they stack.
- put them all in a div and give the parent display flex and watch how they change.
  - now left to right.
  - we can use justify content to put space between the items, main axis
  - align items is used to align items on the cross axis.
  - we can change the main axis by using flex direction.
- lets look over the page were going to build and talk about the layout.
  - use illustraitor to help make the point about nesting divs a bit more obvious
- once you have the basic layout and the navbar then introduce the more complex center section. this can be a good way to show a few cool techniques in css.
- if there is time import a font to show how you can do that
- https://www.designbetter.co/


## afternoon
https://blackrockdigital.github.io/startbootstrap-freelancer/