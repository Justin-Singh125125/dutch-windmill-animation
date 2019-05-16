Here, we will turn  `windmill.jpg`  into an animated image. 
See it deployed on [Github Pages](https://captainalan.github.io/dutch-windmill-animation/). 

Here is the source image we'll be trying to animate:

![windmill](windmill.jpg)

## Workflow

First, I created a vector image in Inkscape. You can see that file in this
repo (`windmill.svg`).

I then exported some `.png` images to manipulate in the browser. See
`index.html`, `index.css` (and maybe `index.js`) for the web programming stuff.

I found that the blades were spinning the wrong way. So rather than change
the animation scripting, I just flipped the blades image, lol.

[This thread](https://stackoverflow.com/questions/16771225/css3-rotate-animation) on 
Stack Overflow helped me with the animation.

