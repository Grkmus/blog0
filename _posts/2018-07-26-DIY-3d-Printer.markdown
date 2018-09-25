---
layout: post
title:  "Building a 3d Printer"
img: printer/IMG_6702.jpg
tags: [Project, DIY]
---
Hi all, as 3d printers become so popular, I couldn't stay away without doing anything. At first, I have started to build CNC(computer numerical control)machine but before finishing it, I thought that it would be very noisy to use in my flat. Eventually, I decided to convert it to 3d printer.

The main key to become successful in this work is 'reading'. Read as much as you can on the internet. There are tons of information regarding to 3d printers and how to build them. I didn't need to ask even one question. I was able to find a solution to every problems that I came accross. My main source was  [reprap](https://reprap.org "reprap") and its forums.

My model was Prusa - i3 Steel. I decided to build that model because it is much more rigid and stable comparing to other prusa models. It is an open source 3d printer model that you can find all the necessary information and drawings about it in reprap.org. Building a 3d printer is not so complicated as it sounds. The process is straightforward. First you have to decide which model you are gonna make. You should consider supplying or manufacturing all the materials and parts in your model according to your location and budget. Considering that, I searched online and found proper second hand bodyparts of prusa i3 steel. It was being sold by someone who started to build it but eventually gave up. Also, I have started build my own wooden frame but I concluded to this solution gonna be better because the price was good and it cost much less work to me.
 For the extruder's cold end, I ordered all the necessary parts from 3d hubs site. Then I used it with some chinese hot end. Not suprisingly, it failed and clogged after one or two experiments. So I bought a fancy hot end from E3D company. I ordered E3D lite. It is working quite well. I printed almost 200 hundred parts, changed 5 filament rolls, still working seemlessly. It is obvious that, they make attention to material quality and engineering of the product. So my suggestion to you, do not order some unknown 3d printer hot ends or equivalents. It is gonna make you frustrated because maintaining the 3d printer gonna be problematic.

I used Arduino Mega 256 with RAMPS shield for the electronics. Marvin is on the software side. I checked all the connections with multimeter before the assembly. I tested it out with 3 NEMA23 step motors. There were no problems.

![3dPrinter]({{ site.baseurl }}/assets/img/Printer/IMG_6702.jpg)

After whole assembly process done, It was looking like this.

I tried to use some designed endstops from thingiverse but It was not so convenient because it was lack of fine tune adjustment feature. So, I designed my own end stop for the z-axis in the end. I used sketchup for modeling. It can just attached to step motor and stays stable and also I added fine tuning mechanism to it. It is great to think about something and get it in your hand in minutes like that.

![3dPrinter]({{ site.baseurl }}/assets/img/Printer/IMG_6760.PNG)

![3dPrinter]({{ site.baseurl }}/assets/img/Printer/IMG_6759.PNG)

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
