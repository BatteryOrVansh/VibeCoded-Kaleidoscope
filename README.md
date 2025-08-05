this trippy kaleidoscope thing i made 🌀
soooo i made this thing.

it's basically a digital kaleidoscope. you just move your mouse and it makes all these sick symmetrical patterns. kinda mesmerizing tbh.

Gemini helped me code it up, which is pretty cool.

what's it running on?
HTML: duh, just the basic page.

Tailwind CSS: to make the buttons and stuff not look like total garbage.

p5.js: this is where the magic happens. it's a js library that does all the heavy lifting for the drawing. the real MVP.

how the heck does it work?
the whole kaleidoscope effect is just a few simple tricks stacked together:

translate(width / 2, height / 2): first it moves the (0,0) point to the middle of the screen. so everything starts from the center.

rotate(angle): then it just spins the canvas around and around.

line(mx, my, pmx, pmy): this just draws a line wherever your mouse goes. simple.

scale(1, -1): ok this is the secret sauce. it flips the drawing upside down to make a mirror image. so it draws your line, then draws the flipped version, and that's what makes the crazy patterns. lol.

wanna make your own?
if u wanna learn how to do this kinda stuff, check out these links:

The Basics
HTML: MDN Web Docs - HTML Basics

Tailwind CSS: Get started with Tailwind CSS

p5.js: Official p5.js Get Started Guide

The p5.js Magic Tricks
setup() & draw(): The main loops in p5.js

translate(): Moving the canvas around

rotate(): Spin it!

scale(): Flipping and resizing stuff

mouseIsPressed & mouseX: Tracking the mouse
