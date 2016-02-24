# High Performance Animations

## Paul Lewis - @aerotwist - 24th Feb 2016


Works for Google on the performance team, working with Chrome.

 - Scale Mount Render
 - Explore the workflow
 - Gaze into a crystal ball
 

### Scale Mount Render

Have to render the page using threads. 

Lots to this - _See diagram later_

Then comes **repaint**

Most if the above happens on CPU. People assume it happens a lot on GPU, but most of the "drawing" is still CPU. Only the last stage that goes to the GPU.


### Explore the workflow

Example of transitioning a box from one place to another on the screen.

There is a rumour that CSS is better at this than JS.

New site [CSS Triggers](http://csstriggers.com) that tells you what else is updated when you update a CSS Attribute.

The enemies of animation are **Layout** and **Paint**!

jQuery now uses requestAnimationFrame, but used to use setTimeout.

[The is a blog on all of this](https://aerotwist.com/blog/flip-your-animations/)

Also made a [library that can do this for you](https://github.com/googlechrome/flipjs)

[Joshua Comeau has done this in React too](https://github.com/joshwcomeau/react-flip-move)

### Gaze into a crystal ball

[Houdini](https://github.com/w3c/css-houdini-drafts/wiki/specs) is a bunch of specifications that cover things we don't normally have access to and gives us access to them.

Understand the pixel workflow. It will unlock a lot of power!




