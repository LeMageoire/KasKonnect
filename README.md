<h1 align= "center">
  PROJECT KasKonnect
</h1>

---
---
---

In a project integrated to my HES bachelor in a course called "Multidisciplinary Projects", we were 3 on this project

# Goal
- The goal was to design an embedded wearble human interface with the purpose of :
  - Being usable on a bike
  - Provide Trajectory informations

# Solution provided
- Based on the time and budget constraints, we customised a standard bike helmet
  - so we used a Arduino with some battery management system a bluetooth module
- We conducted experiments about the user experiences to send the info.
- I programed using Java, a mobile application that could connect to the Google map API, to self-locate
- I programed the arduino, so that i could recieve from bluetooth connection the data fetch on the Android Phone

# Conclusion
- most of the prototype was fonctional (the bike helmet worked with the Led communication)
- we got 6.0/6.0 for our project

# Notes

- The algorithm part needs rework 
  - From what I've read, Librairies Exists
- I'll rework it once I could afford the budget to rebuilt a similar prototype

# To-Do
## Main Design
- [ ] Redo the Google Map Api setup
  - [ ] Generate the Path
  - [ ] Get the Orientation from the build-it sensor of the phone (sensor fusion)
  - [ ] find the angle between the path and your self-orientation
  - [ ] send info to the hardware headset (+design of specific cases)
## Hardware Design

---
---
---
