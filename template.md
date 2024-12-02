# Process Writeup

## Name: Eva Chen
## Course: SEP10 Web Design
## Period: 7
## Concept: Applied Visual Design Jigsaw

  ### Context

We are currently in  Unit 1, web design. The topic for the project is applying visual designs. In this project, every group had a topic. We had to make a webpage about the topic. My group's topic was animations. We learned lessons on FCC(Free Code Camp) and we were able to create a simple webpage about the lessons we learned.

### FreeCodeCamp
In FCC, it was really fun because I was able to solve challenges as I went though the lesssons. Some of the lessons on FCC include ```Animation-name```, ```keyframes```, color, ```Animation-iteration-count```, and ```Animation-Timing-Functions```. Theses were also the topics included into the project. Each topic had its own header and we explained how each element worked. 

**Here are some of the other topics that other groups did:**
* Basic (text-align, height, strong, s, horizontal lines, background-color, etc..)
* Colors (Hue, gradient, etc..)
* Positioning (relative, absolute property, fixed property, float property, z-index, auto)
* Geometry (skewX, skewY, hover, transform, scale,, rotate, box shadows)
* Animation (animation-name, keyframes, color, animation-iteration-count, animation-timing-functions)

For example, we explained how ```Animation-name```  was used to name an animation so that it is easier to select that specific animation.
Here's an example:
```
animation-name: example;
animation-name: underline;
animation-name: whatever;
```

For ```keyframes```, it was like a timestamp for the animation. So basically, you would use percentage signs to represent the parts of the animation.
Here's how keyframes would work:
```
@keyframes ex{
0% { color: red;}
50% {color: orange;}
100% {color: yellow;}
 ```
In this code, the animation selected will start on red and then half way through the animation(50%), it would turn orange and then end with yellow. This is because 0% is the start of the animation and 50% is the middle of the animationa and at 100% it would be the end. You can add more percentages throughout. It doesn't just have to be 0%, 50%, and 100%.

Then, we have ```color```. This one, I found the easiest since it is just used to change the color of anything. Colors was also used in the previous example since the keyframe is using red, orange, and yellow.

After that, we have ```animation-iteration-count```. This is used to loop how many times you want your animation to loop.
Here is an example:
```
animation-iteration-cound:1;
animation-iteration-count: 3;
animation-iteration-count: infinte;
```
By adding 1, the animation will loop once, so if it was 3, it would loop three times. So, you woudld just put how many times you want your animation to loop. If you want your animation to contiuously loop, you would put infinte.

Lastly, we have ```animation-timeing-function```. This is used to change how the animation would progress. You able to change how fast the animation moves. This can be used to accelerate the animation just like a graph.
Example:
```
animation-timing-function: ease-out;
animation-timing-function: ease-in;
animation-timing-function: linear;
animation-timing-function: cubic-bezier(0.25, 0.25, 0.75, 0.75);
```
In this example, the animation would ease-out and ease-in. This means that at the beginning it would slowly get faster and then slowley get slower towards the end. Linear is used to the animation stays the same speed throughout. The cubic-bezier is used to set 2 points for the animation and for the animation to have a custom curve.

All of these topics were used into the [project](https://app.pickcode.io/share/cm3nc386v91029fpuh7uvpvqy).

###Challenges
The major challenge I really faced was learning how to use the keyframes. I got confused and didn't really understand how to use keyframes. I struggled with understanding the format with the curly brackets and the percentages.
Here is how to properly use keyframes:


Inline `code` snippet

```language
multi
line
code
snippet
```

---

NOTE: to see the raw code for this file, click [here](https://raw.githubusercontent.com/hstatsep/other/main/writeups/template.md)
