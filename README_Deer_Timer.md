
## README for Deer Timer Project

### Introduction
Deer Timer is a study-focused application inspired by the mobile app Forest. It's designed to help university students stay focused while studying by using a unique motivational approach involving an on-screen deer.

### How It Works
1. **Display**: A deer is shown on the screen for the duration of the app's runtime.
2. **Timer**: Users set a study duration, and the app counts down this time.
3. **Focus Mechanism**: If the user switches windows, the deer will "spontaneously combust" and slowly perish. This represents the user getting distracted.
4. **Reward**: If the user remains on the application window, the deer stays alive, rewarding the user.

### Built With
- Python and PyQt libraries for the main application.
- PyGetWindow and threading for additional functionalities.
- DaVinci Resolve for deer image creation.

### Features
- **backgroundMusic.py**: Manages background music, using sources cited in the project for music and sound effects.
- **main.py**: The central script, integrating the UI, screen detection, and background music.
- **screenDetection.py**: Implements screen detection to identify window switching.
- **ui.py**: Manages the user interface, including displaying the deer and timer.

### Future Enhancements
Plans include incorporating more distraction detection methods, like using a webcam and machine learning to detect if the user is using their phone.

### Citations
Inspired by the Forest App, with resources used for deer drawings, fire greenscreen effects, and background music from various web sources.

---

This README provides a comprehensive overview of the Deer Timer project, its inspiration, functionalities, and the technologies used. It aligns with the project's focus on aiding students in maintaining focus during study sessions.
