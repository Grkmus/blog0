---
layout: postGallery
title:  "Arduino Based Midi Keyboard"
img: midiKeyboard/1.jpg
tags: [Project, DIY]
gallery: [midiKeyboard/2.jpg, midiKeyboard/3.jpg, midiKeyboard/4.jpg, midiKeyboard/5.jpg,midiKeyboard/6.jpg, midiKeyboard/7.jpg,]
midiKeyboardVideo: mLeFq4I4QS0
---

Playing keyboard has always been a challenge for me, something I’ve never quite mastered. But after watching this [video](https://www.youtube.com/watch?v=z840N9P-T2k), I thought, maybe I could build a MIDI keyboard like this and play the same song. Challenge accepted! I did some research and learned how to create a similar device using Arduino. There was a wealth of information online, and the basic requirements were:

1. A proper key set with a key matrix.
2. An Arduino Uno or Mega.
3. A suitable casing.

I searched online and scoured flea markets until I found a key set that would work for my project. It had 64 keys, so I needed to expand the Arduino’s digital pins using a semiconductor. I found a lot of help on [Jen Shen's Site](http://www.codetinkerhack.com/2012/11/how-to-turn-piano-toy-into-midi.html#more), where he had built something similar. I even asked him a few questions about the issues I encountered, which you can see in the comments on his blog post. I also modified some parts of his code to fit my design. You can find my code here: [Link to code](https://drive.google.com/file/d/14axEuFyu0-OFf8lliA6FxOXe2eYkT7Bu/view?usp=sharing).

For the casing, I sketched a simple design and built it. It’s nothing fancy, but it works well. In the end, I might not have learned to play the song from the video, but at least I built the keyboard! Here’s a video of me testing it for the first time:

{% include youtubePlayer.html id=page.midiKeyboardVideo %}
<br>

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
