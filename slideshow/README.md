# Slideshow

A responsive fullscreen slideshow that allow users to cycle through elements (images).

## Keynotes

### CSS Triangle

A triangle shape can be made with a single div.

The idea is a box with zero width and height. The actual width and height of the arrow is determined by the width of the border. In an up arrow, for example, the bottom border is colored while the left and right are transparent, which forms the triangle.

Dave Everitt writes in:

For an equilateral triangle it's worth pointing out that the height is 86.6% of the width so (border-left-width + border-right-width) * 0.866% = border-bottom-width

## Credits

-W3School [How TO - Slideshow](https://www.w3schools.com/howto/howto_js_slideshow.asp)

-Traversy Media [Full Screen Image Slider With HTML, CSS & JS](https://youtu.be/7ZO2RTMNSAY)

-CSS Tricks [CSS Triangle](https://css-tricks.com/snippets/css/css-triangle/)

Hi Brad! Love your tutorials! At 12:34 I wanted to add you can vertically center
the arrow class with the following code - I think that'll be more responsive:

position: absolute;
top: 50%;
transform: translate(0, -50%);

instead of using "margin-top".

Keep up the great work!
