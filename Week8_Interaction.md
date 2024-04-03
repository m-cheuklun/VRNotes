# Interaction

[Discussion Link](https://github.com/orgs/sit-dia/discussions/14)

## Viewpoint Control

- Basically controlling the camera
- Is a **passive** interaction
- Inertial Measurement Units (IMUs) use accelerometers and gyroscopes to determine where a device is in 3D space
> - Viewpoint control in VR typically involves the following aspects:
> -Positional Tracking: VR systems often use sensors or cameras to track the user's head movements in real-time, allowing them to change their position within the > -virtual environment by moving their head. This enables users to look around and explore the virtual world from different angles.

> - Orientation Control: Users can also rotate their viewpoint by turning their head or using input devices such as controllers to change their orientation within the virtual environment. This allows them to view the surroundings from different perspectives.

> - Teleportation or Locomotion: In addition to natural movement, VR applications may offer alternative methods of navigation such as teleportation or simulated > -walking. These techniques allow users to move to different locations within the virtual space, expanding their ability to explore and interact with the > -> -environment.

> - Scale and Proximity Control: Some VR experiences allow users to dynamically adjust their scale within the virtual environment or manipulate their proximity to objects. This feature can be useful for examining details, interacting with objects, or adapting the environment to fit personal preferences.

## Hand Gestures

- Haptic Gloves
- Computer Vision-based Finger Tracking
- Dedicated VR controllers

## Body Gestures

- Embodiment: "the feeling of being in control of a virtual representation of the human self"
> - Perception that a virtual body is one's own. Often correlated to Presence
- Hand gestures are partial embodiment, because only the hands are being controlled
- IMU Trackers
- 360 degree treadmills
- Haptic suits
- No real desktop replacement using desktop modalities (e.g. keyboard, mouse) to give embodiment

## Interaction Authenticity

- Interaction Authenticity: "the consideration of whether the desired experience should be natural or artificial"

### Natural Interactions

- Natural Interactions: "interactions where the outcome is very close to what is done in the real world"
> - Natural interaction offers the most optimal interaction authenticity

### Artificial Interactions

- Artificial Interactions: "interactions that are impossible in the real world"

#### Magical Interactions

- Plausibility Illusion: "events that happen in the virtual world closely affects the perception of how credible these things can actually happen IRL"
- Having the Plausibility Illusion is the key to providing an immersive experience for the user
- E.g literally controlling the flow of time by moving (Superhot)

#### Augmented Natural Interactions

- Allows users to perform highly exaggerated versions of a familiar IRL action
- E.g. super high jumps in video games

## Interaction Use Cases

### GUI Interactions

- GUI = Graphical User Interface
- HUD = Heads Up Display
- HMD = Head Mounted Device

#### E.g. Meta Quest 2

-  An "all-in=one" VR HMD, where all selections and menu interactions are displayed in the VR display itself
- It uses Viewpoint Control & Hand Gestures 
- Creates a laser pointer ray, acting as an extension of the VR controllers, to click options in the menu with a trigger button

#### E.g. Google Cardboard

- Makes finger point at things by using Viewpoint Control, known as Gaze Control (because there are no controllers)
- Clicks in menus are done by staring at menu options long enough [Editor's Note: THAT'S HILARIOUS.]

### Locomotion Interactions

- Locomotion Interactions: "the ability to perform spatial navigation in the virtual environment"
- Can be pretty tricky to get right, especially with IRL spatial constraints (the room you're in can only be so big before bumping into stuff)
- Can be done by combining Viewpoint Control, Hand Gestures and Body Gestures
- Alternatively, users can move around with just teleporting from place to place instead, but that hampers Immersion a lot

# End  

Link: [Developing Immersive Applications: Interaction (youtube.com)](https://www.youtube.com/watch?v=dKRWH7O81yk)

# Menti Quiz

## Q1) Which interaction mechanic is commonly deemed to be the most important in immersive AR, VR and MR experiences?

- Viewport Control
- Hand Gestures
- Body (Excluding hands gestures)
- All mechanics are equally important

__Answer__
> Viewport Control

## For Q2, Q3 & Q4

![VR Bioreactor Training](/images/w8-01.png)

## Q2) In the VR Bioreactor Training system, what interaction mechanics were implemented?

- Viewport Control
- Hand Gestures
- Body (Excluding hands gestures)
- All of the above

__Answer__
> Viewport Control
> Hand Gestures

## Q3) In the VR Bioreactor Training system, is viewport control a passive or active interaction mechanics?

- Passive
- Active

__Answer__
> Passive

## Q4) In the VR Bioreactor Training system, are hand gestures a passive or active interaction mechanic?

- Passive
- Active

__Answer__
> Active

## For Q5, Q6 & Q7

![360 Video Lecture](/images/w8-02.png)

## Q5) In the 360 Video Lecture, what interaction mechanics were implemented?

- Viewport Control
- Hand Gestures
- Body (Excluding hands gestures)
- All of the above

__Answer__
> Viewport Control
> Hand Gestures

## Q6) In the 360 Video Lecture, is viewport control a passive or active interaction mechanics?

- Passive
- Active

__Answer__
> Passive
> Active

## Q7) In the 360 Video Lecture, what form of interaction authenticity is the eye-gaze point-and-click mechanic?

- Natural interaction
- Artificial magical interaction
- Artificial augmented natural interaction

__Answer__
> Artificial augmented natural interaction

## Q8) Many users tend to route their hands behind the virtual saw blade when asked to place their hands in the target position? What is the primary reason?

- Limited field of view in the VR headset affecting depth perception
- The saw blade simply looks hyper-realistic
- High embodiment via realistic hand representation and precise tracking
- Difficult in accurately perceiving the virtual saw blade's position

__Answer__
> High embodiment via realistic hand representation and precise tracking

## Q9) What interaction authenticity is optimal?

> You are tasked to build a VR application to allow kids to learn physics in a classroom. Kids will be able to throw virtual balls to hit cans placed at different distances and heights. What form of interaction authenticity is optimal for this use case?

- Natural interaction
- Artificial magical interaction
- Artificial augmented natural interaction

__Answer__
> Natural interaction

## Q10) What interaction authenticity is optimal?

> You are tasked to build an MR application for people to practice taking care of a virtual pet dog in their house, to aid them with the decision of actually getting a real pet dog in the future. What form of interaction authenticity is optimal for this use case?

- Natural interaction
- Artificial magical interaction
- Artificial augmented natural interaction

__Answer__
> Natural interaction

## Q11) Which device platform is the most appropriate here?

> You are tasked to build a VR training system to train aircraft maintenance engineers to repair various aircraft parts on a virtual plane. If we are aiming for maximum immersion with natural interactions around a life-sized virtual aircraft, what device is optimal for this use case?

- Desktop
- Google Cardboard
- Meta Quest 2 (Wireless)
- HTC Vive Pro (Wired)
- Microsoft Hololens

__Answer__
> Meta Quest 2 (Wireless)

## Q12) Which device platform is the most appropriate here?

> You are tasked to build a VR cycling game that can be played on a real bike on a stationary trainer, that places you on equal standing against elite cycling professionals in a virtual Tour de France. If we are aiming for maximum immersion with augmented natural interactons, what device is optimal for this use case (assuming sweat is not a consideration)?

- Desktop
- Google Cardboard
- Meta Quest 2 (Wireless)
- HTC Vive Pro (Wired)
- Microsoft Hololens

__Answer__
> HTC Vive Pro (Wired)

## Q13) What form of GUI implementation is best suited for this use case?

> You are tasked to build a VR virtual sightseeing experience for hotel guests and the client wants to obtain feedback after each virtual trips. The client can only provide the users with Google Cardboards. What form of GUI implementation is best suited for this use case?

- GUI on a virtual paper (using a virtual pen)
- GUI on a 3D plane anchored in virtual world locations
- Real-world quiz on real paper (take off HMD when interacting)

__Answer__
> GUI on a 3D plane anchored in virtual world locations
> Real-world quiz on real paper (take off HMD when interacting)

## Q14) What form of GUI implementation is best suited for this use case?

> You are tasked to build a VR training simulation for aircraft maintenance engineers with a quizzing system to evaluate their performance during tasks. The immersion goal is to provide realistic training for typical maintenance operations. What form of GUI implementation is best suited for this use case?

- GUI on a virtual paper (using a virtual pen)
- GUI on a 3D plane anchored in virtual world locations
- Real-world quiz on real paper (take off HMD when interacting)

__Answer__
> GUI on a 3D plane anchored in virtual world locations

## Q15) You are tasked to build a VR game for persons on wheelchairs to explore famous mountains in the world. What locomotion technique is best suited for this use case?

- Teleportation
- Joystick-based
- Walking-in-place (WIP) with KatVR 360 slidemill
- Walking-in-place (WIP) with HTC Vive HMD and trackers
- Tracking real movement in physical space

__Answer__
> Teleportation

## Q16) You are tasked to build a VR escape room experience targetted at able-bodied users. Naturally, an escape room experience aims to provide maximum immersion from all aspects. What locomotion techniques is best suited for this use case?

- Teleportation
- Joystick-based
- Walking-in-place (WIP) with KatVR 360 slidemill
- Walking-in-place (WIP) with HTC Vive HMD and trackers
- Tracking real movement in physical space

__Answer__
> Tracking real movement in physical space

## Q17) As a lead developer for a new VR action-adventure game, players will engage in a series of quests across varying terrain, from dense forests to steep mountains. Movement in the game needs to be intuitive and contribute to near-realistic interactions with the environment for tasks like trekking and light stealth. To encourage sustained play without causing disorientation, what locomotion technique should you integrate into your game design?

- Teleportation
- Joystick-based
- Walking-in-place (WIP) with KatVR 360 slidemill
- Walking-in-place (WIP) with HTC Vive HMD and trackers
- Tracking real movement in physical space

__Answer__
> Walking-in-place (WIP) with HTC Vive HMD and trackers