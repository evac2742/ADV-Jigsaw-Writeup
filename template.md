# Process Writeup

## Name: Eva Chen
## Course: SEP10 Web Design
## Period: 7
## Concept: Applied Visual Design Jigsaw

  ### Context

We are currently in  Unit 1, web design. The topic for the project is applying visual designs. In this project, every group had a topic. We had to make a webpage about the topic. My group's topic was animations. We learned lessons on FCC(Free Code Camp) and we created a simple webpage about the lessons we learned.

### FreeCodeCamp
In **FCC**, it was really fun because I was able to solve challenges as I went through the lessons. Some of the lessons on FCC include ```animation-name```, ```keyframes```, color, ```animation-iteration-count```, and ```animation-timing-functions```. These were also the topics included in the project. Each topic had its own header and we explained how each element worked. 

**Here are some of the other topics that other groups did:**
* **Basic** (text-align, height, strong, s, horizontal lines, background-color, etc..)
* **Colors** (Hue, gradient, etc..)
* **Positioning** (relative, absolute property, fixed property, float property, z-index, auto)
* **Geometry** (skewX, skewY, hover, transform, scale, rotate, box shadows)
* **Animation** (animation-name, keyframes, color, animation-iteration-count, animation-timing-functions)

For **example**, we explained how ```animation-name```  was used to name an animation so that it is easier to select that specific animation.
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
In this code, the animation selected will start on red and then half way through the animation (50%), it would turn orange and then end with yellow. This is because 0% is the start of the animation and 50% is the middle of the animation and at 100% it would be the end. You can add more percentages throughout. It doesn't just have to be 0%, 50%, and 100%.

Then, we have ```color```. This one, I found the easiest since it is just used to change the color of anything. Colors was also used in the previous example since the keyframe is using red, orange, and yellow.

After that, we have ```animation-iteration-count```. This is used to loop how many times you want your animation to loop.
Here is an example:
```
animation-iteration-count: 1;
animation-iteration-count: 3;
animation-iteration-count: infinite;
```
By adding 1, the animation will loop once, so if it was 3, it would loop three times. So, you would just put how many times you want your animation to loop. If you want your animation to continuously loop, you would put infinite.

Lastly, we have ```animation-timing-function```. This is used to change how the animation would progress. You are able to change how fast the animation moves. This can be used to accelerate the animation just like a graph.
Example:
```
animation-timing-function: ease-out;
animation-timing-function: ease-in;
animation-timing-function: linear;
animation-timing-function: cubic-bezier(0.25, 0.25, 0.75, 0.75);
```
In this example, the animation would **ease-out and ease-in**. This means that at the beginning it would slowly get faster and then slowly get slower towards the end. Linear is used so the animation stays at a constant speed. The cubic-bezier is used to set 2 points for the animation and for the animation to have a custom curve.

All of these topics were used in the [project](https://app.pickcode.io/share/cm3nc386v91029fpuh7uvpvqy).

### Challenge #1
The major **challenge** I really faced was learning how to use the **keyframes**. I got confused about how to apply keyframes to things since it was its own property. I basically didn't understand how to connect things to keyframes. I was soon able to learn that the word after keyframes was the animation-name. So, after keyframes, I would put the animation name.
**Example**:
```
#anim{
animation-name: example;
}
@keyframes example {
0% {
background-color: red;
}
50% {
background-color: orange;
}
100% {
background-color: yellow;
}
}
```
### Challenge #2
Another challenge I faced was that when my group was making the website, we didn't really **rehearse** before we went up. I think I rehearsed my own part once but the rest of us didn't really practice. So, when we were presenting, I didn't know who was before me and I just had to look at our website until I saw my part come up.

### Takeaways
* To use **keyframes**, I need to use the animation-name after @keyframes
* **Practicing and rehearsing** before presentation would help because then everything would be organized and everyone would know who goes next when presenting.

Click [here](https://app.pickcode.io/project/cm3nc386v91029fpuh7uvpvqy) to view my group's project!
