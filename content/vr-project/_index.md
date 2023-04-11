---
title: Virtual Reality Project
layout: single
---

## Installing

1. Download the APK: 
2. If not already, put the Quest 2 or Quest Pro headset in [developer mode](https://youtu.be/lFTXv2aScJ8?t=169).
3. Install the APK using [Sidequest](https://sidequestvr.com/) advanced installer (recommended) or [android developer bridge](https://developer.oculus.com/documentation/native/android/ts-adb/).

---

## VR App Design Notes
With knowledge of the exact target audience and classroom, we were able to tailor the design of our experience. At a high level, we aimed for the experience to be more of a digital exploration tool than a guided tour.
The experience should be easily interruptible, easily restartable without any fragile user states, and facilitate communication between those outside and inside VR. It must be usable by those with extremely limited VR experience.
### Asymmetric Communication
We knew a goal was to facilitate communication between a Professor outside of VR, and student wearing the headset.

- Directionally recognizable environment (utilizing landmarks)
- Almost No Audio
- Verbally communicable interaction signifiers
- Verbally understandable fossil site names
- 3D model of controller instead of hand model
- *While not completed yet, we would like to explore "pass-through" AR support, and research how to design for asymmetric classroom environments*

### Allow for Minimal Movement.

- Standing or Seated
- Can "bring the fossil to you" instead of walk over to it
- Hand-held close-ups that can be scaled and repositions

### Accessibility

- Everything works either standing/seated
- Colorblind-friendly UI elements
- Simple, effective interaction feedback
- Run with enough performance overhead to allow for smooth casting.
- Extensive student testing
- Rely on minimal controls, and use only pre-learned interaction paradigms (i.e. Quest's OS-level interactions, like laser-pointer menus)


## Notes on Scope and Future Goals
We were not able to implement everything we wished. With more resources, we would like to continue the project as a study in designing for asymmetric classroom experiences. We believe that asymetric classroom experiences, where not all the participants are in VR, and all are in the classroom together, is a fruitful avenue of research and future projects, and remains under-explored currently.

Other elements that were out of scope were accessibility features that required more technical investment to get running or working. An experience must be usable for as many humans as possible if the goal is to deploy it in the classroom, and we have more work to do in this regard.

- Listen to events fired off a macropad controlled by an arduino, allowing a professor to trigger events for students in VR.
- We wanted smoother support for adjusting the heights of the table for individuals seated. 
- Haptics feedback for interactions
- A flashlight. We think it would be interesting to allow the user to get close with a light to change the shadows on the fossil, exploring its shape in a novel way that is difficult to do without a realtime rendering engines.
- More fossil sites.
- We are not completely sold on our map interaction. Efforts at designing more tangible and flexible solutions add a cost of onboarding or prevent standing-only interaction.
