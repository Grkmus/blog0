---
layout: post
title: "Web MIDI Piano App"
img: webpiano/web-piano-cover.jpg
tags: [Project, Web Development, JavaScript, MIDI]
---

I've developed a web-based MIDI piano application that brings music creation directly to your browser! This project combines my passion for music and programming, creating an interactive piano that works with MIDI devices and keyboard input.

## 🎹 Try the App

**[Launch Web MIDI Piano](https://grkmus.github.io/web-piano/)**

The app features a fully functional piano interface that you can play using:
- Your computer keyboard
- MIDI keyboard/controller (with Web MIDI API support)
- Mouse/touch input on the virtual piano keys

## 🛠️ Technical Features

- **Web MIDI API Integration**: Connect your physical MIDI keyboard for a realistic playing experience
- **Responsive Design**: Works seamlessly on desktop and mobile devices  
- **Real-time Audio**: Low-latency sound synthesis for smooth performance
- **Visual Feedback**: Keys light up as you play for better interaction
- **Cross-browser Compatibility**: Optimized for modern web browsers

## 🔗 Project Links

- **Live Demo**: [https://grkmus.github.io/web-piano/](https://grkmus.github.io/web-piano/)
- **Source Code**: [https://github.com/Grkmus/web-piano](https://github.com/Grkmus/web-piano)

## 💡 Development Insights

This project was an excellent opportunity to explore the Web MIDI API and learn about browser-based audio synthesis. The biggest challenges were:

1. **Latency Optimization**: Ensuring minimal delay between key press and sound output
2. **MIDI Device Compatibility**: Supporting various MIDI controllers and keyboards  
3. **Audio Context Management**: Handling browser audio policies and user interaction requirements
4. **Mobile Responsiveness**: Creating an intuitive touch interface for smaller screens

## 🎵 How to Use

1. **With MIDI Keyboard**: 
   - Connect your MIDI keyboard to your computer
   - Open the app and allow MIDI access when prompted
   - Start playing!

2. **With Computer Keyboard**: 
   - Use the designated keys to play notes
   - Enjoy the full range of the piano

3. **Touch/Mouse**: 
   - Simply click or tap the virtual piano keys
   - Perfect for mobile devices and tablets

Feel free to explore the code on GitHub and try out the live demo. I'd love to hear your feedback and any suggestions for improvements!

## 🔧 Technologies Used

- **HTML5 & CSS3**: For the user interface and styling
- **JavaScript (ES6+)**: Core application logic and Web MIDI API integration
- **Web Audio API**: For sound generation and audio processing
- **Web MIDI API**: For MIDI device communication

---

*This project represents my exploration into web-based music applications and showcases the power of modern web APIs for creative applications.*