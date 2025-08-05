# this trippy kaleidoscope thing i made 🌀

soooo i made this thing.
it's basically a digital kaleidoscope. you just move your mouse and it makes all these sick symmetrical patterns. kinda mesmerizing tbh.
Gemini helped me code it up, which is pretty cool.

## what's it running on?

-   **HTML:** duh, just the basic page.
-   **Tailwind CSS:** to make the buttons and stuff not look like total garbage.
-   **p5.js:** this is where the magic happens. it's a js library that does all the heavy lifting for the drawing. the real MVP.
    

## how the heck does it work?

the whole kaleidoscope effect is just a few simple tricks stacked together:
1.  **`translate(width / 2, height / 2)`**: first it moves the (0,0) point to the middle of the screen. so everything starts from the center.
2.  **`rotate(angle)`**: then it just spins the canvas around and around.    
3.  **`line(mx, my, pmx, pmy)`**: this just draws a line wherever your mouse goes. simple.   
4.  **`scale(1, -1)`**: ok this is the secret sauce. it flips the drawing upside down to make a mirror image. so it draws your line, then draws the flipped version, and that's what makes the crazy patterns. lol.
    

## wanna make your own?

if u wanna learn how to do this kinda stuff, check out these links:

### The Basics
-   **HTML:**  [MDN Web Docs - HTML Basics](https://developer.mozilla.org/en-US/docs/Web/HTML "null")   
-   **Tailwind CSS:**  [Get started with Tailwind CSS](https://tailwindcss.com/docs/installation "null")    
-   **p5.js:**  [Official p5.js Get Started Guide](https://www.google.com/search?q=https://p5js.org/get-started/ "null")
    

### The p5.js Magic Tricks

-   **`setup()` & `draw()`:**  [The main loops in p5.js](https://p5js.org/reference/#/p5/setup "null")    
-   **`translate()`:**  [Moving the canvas around](https://p5js.org/reference/#/p5/translate "null")    
-   **`rotate()`:**  [Spin it!](https://p5js.org/reference/#/p5/rotate "null")    
-   **`scale()`:**  [Flipping and resizing stuff](https://p5js.org/reference/#/p5/scale "null")    
-   **`mouseIsPressed` & `mouseX`:**  [Tracking the mouse](https://p5js.org/reference/#/p5/mouseIsPressed "null")
