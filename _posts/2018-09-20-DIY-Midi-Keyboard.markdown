---
layout: postGallery
title:  "Arduino Based Midi Keyboard"
img: midiKeyboard/1.jpg
tags: [Project, DIY]
gallery: [midiKeyboard/2.jpg, midiKeyboard/3.jpg, midiKeyboard/4.jpg, midiKeyboard/5.jpg,midiKeyboard/6.jpg, midiKeyboard/7.jpg,]
midiKeyboardVideo: mLeFq4I4QS0
---

Playing keyboard was always a challenge for me that I've never achieved. But after watching this [video](https://www.youtube.com/watch?v=z840N9P-T2k) I thought that, maybe I can build one midi keyboard like this and play the same song in the video. Challenge accepted! I research a bit and learned how to build such a device with arduino. There were huge amount of information on the internet. Basics need are;

1. A proper key set with key matrix along it.
2. Arduino uno or mega
3. Suitable casing

I searched online and also a lot of flea market and finally found a key set which is fitted for my project. It has 64 keys and for that reason I needed to extend my arduino's digital pin with a semiconductor. I got a lot help from [Jen Shen's Site](http://www.codetinkerhack.com/2012/11/how-to-turn-piano-toy-into-midi.html#more) he also built something like this and I asked him about my problems that I encountered. You can find my questions in below on his blog post. Also, I changed some part of his code according to my design. You can find it also here; [Link to code](https://drive.google.com/file/d/14axEuFyu0-OFf8lliA6FxOXe2eYkT7Bu/view?usp=sharing)

For the casing I sketcht a simple design and built it. It was nothing fancy but worked verywell. At last, I might couldn't play the song in the first video but at least I have built it :). You can find a video below that I am testing it first time.

{% include youtubePlayer.html id=page.midiKeyboardVideo %}
<br>

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
