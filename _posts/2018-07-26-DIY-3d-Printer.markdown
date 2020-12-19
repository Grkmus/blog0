---
layout: post
title:  "Building a 3d Printer"
img: printer/IMG_6702.jpg
tags: [Project, DIY]
---
Hi all, as 3d printers became so popular, I couldn't stay away without doing anything. I had already started to build CNC(computer numerical control)machine but before finishing it, I thought that it would be very noisy to use in my flat. So, I decided to convert it to a 3d printer. The CNC and 3d printer have too much in common. The principle behind is more or less the same.

There are tons of information about 3d printers and how to build them on the internet. I didn't need to ask even one question. I was able to find a solution to every problems that I encountered. My main source was  [reprap](https://reprap.org "reprap") and its sub forums.

The model I picked was Prusa - i3 Steel. I decided to build that model because it is much more rigid and stable comparing to other prusa models. You can find all the necessary information and drawings about it in reprap.org. Building a 3d printer is not so complicated as it sounds. The process is relatively straightforward. First, you have to decide which model you are gonna make. You should consider supplying or manufacturing the materials and parts in your model. I found a good deal for proper second hand bodyparts of prusa i3 steel on internet and bought it. It was being sold by someone who started to build it but eventually gave up. Before that, I tried to build my own wooden frame but I decided to not to continue with it after considering the rigidity. 
 For the extruder's cold end, I ordered all the necessary parts from 3d hubs web site. Then I used it with some chinese hot end. Not suprisingly, it clogged after one or two experiments. So, I bought a fancy hot end from E3D company. I ordered E3D lite product. It is working quite well. I printed almost 200 hundred parts, changed 5 filament rolls, still working seemlessly. It is obvious that they pay attention to material quality and design of the product. So my suggestion to you, do not order some unknown 3d printer hot ends or equivalents. It is gonna make you frustrated because maintaining the 3d printer gonna be problematic.

I used Arduino Mega 256 with RAMPS shield for the electronics. Marvin is on the firware side. I checked all the connections with multimeter before the assembly. I tested it out with 3 NEMA23 step motors. There were no problems.

![3dPrinter]({{ site.baseurl }}/assets/img/printer/IMG_6702.jpg)

After whole assembly process done, It was looking like this.

I tried to use some designed endstops from thingiverse but It was lack of fine tune adjustment feature. So, I designed my own end stop for the z-axis in the end. I used sketchup for modeling. It can be attached to step motor and stays stable enough while the device is printing. I also added fine tune mechanism with a help of a screw to it. The result was great! All in all, It is so nice to think about something and get it in your hand in minutes like that.

![3dPrinter](/assets/img/printer/IMG_6760.png)

![3dPrinter](/assets/img/printer/IMG_6759.png)

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
