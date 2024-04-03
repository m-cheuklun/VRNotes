# Development Tools

[Discussion Link](https://github.com/orgs/sit-dia/discussions/7)

## The Tools

### 1. Unity

- Is a public company
- Uses a component-based architecture
- Easy to create high-quality simulations or games
- Can be deployed to nearly any platform
- Has project templates for AR and VR

### 2. Unreal Engine

- Massive, feature-heavy
- Private company
- Component-based
- Has visual scripting, but also supports C++
- Good for making high-quality content with large teams
- The goto software when high-quality graphics are desired

### 3. A-Frame

- Is a JavaScript library
- Designed to be highly accessible to new developers
- Extensible to allow experienced developers to create highly complex VR experiences
- Web-based, so only builds for the web
- Held back by the immersion that is limited by the system (web browsers)
- Anyone with a browser will be able to experience XR creations (accessibility to users & developers)
- Open source
- The library creates custom HTML tags to be used in code
 
### 4. BabylonJS

- Is a JavaScript library
- Has supporting tools like Playground to allow for quick testing
- Has in-built rendering and physics libraries, focuses on performance more than A-Frame
- Large and active community
- Open source, fully supports WebXR
- Typescript is the default, not JavaScript

### 5. WebXR

- Is a set of open APIs that standardizes how XR apps are made for the web
- has support for different devices, gamepads, AR and more

### 6. OpenXR

- Is a C++ library, made by Khronos (the OpenGL & Vulkan people)
- Basically what WebXR is doing, but for native platforms instead of the web
- Is more specific with regard to deployment platforms
- Usually only needed if unique, novel features are necessary

### 7. Choice Factors when Selecting Tools

- E.g clients have Meta Quest Pro systems, used in medical training environments -> Unreal Engine
- E.g. Crowdsource camera footage through an AR game -> have as many users as possible -> BabylonJS

#### Non Functional Considerations of Tools

- Cost 
- Stability
- Customizability/extensibility
- Community + Support
- Learning Opportunities (does the tool align with learning objectives as a developer?)

## Why WebXR + BabylonJS

- End products will be more accessible to users, accessibility leads to adoption, leads to more feedback, leads to a better product
- Large, active developer community
- Accessibility to developers, will give prototypes longevity
- Nuanced technicalities, can help in designing more unique experiences
- Applied learning experience
 
# End

Link: [Developing Immersive Applications: Development Tools (youtube.com)](https://www.youtube.com/watch?v=qxNUQVsZ9Rk)

# Menti Quiz

## Q1) I need to use a WebXR-compliant framework for my Team Project

- Yes
- No

__Answer__
> No

## Q2) I should build my Team Project on top of the existing UniverseSITy codebase

- Yes
- No

__Answer__
> No

## Q3) We will be assessed more favourably if we can demonstrate higher levels of immersion from our evaluation

- Yes
- No

__Answer__
> No

## Q4) We will be assessed more favourably if our project aligns with UniverseSITy theme better (e.g. use real SIT campus 3D model)

- Yes
- No

__Answer__
> No

## Q5) We will be assessed more favourable if we demonstrate implementation efforts that are clearly aligned with immersion goals

- Yes
- No

__Answer__
> Yes

## Q6) When I run console.log("debug"), where should I see this "debug" message?

- Mac terminal
- Windows Command Prompt
- Web browser's Javascript Console
- ADB's logcat

__Answer__
> Mac terminal
> Windows Command Prompt
> Web browser's Javascript Console

## Q7) When connecting the Meta Quest, there is no prompt to enable connection and I can't see developer options in the settings. What is the likely issue?

- Did not connect a USB data cable
- Headset low battery
- Did not tap the Build Number 7 times in the settings
- Did not enable Developer Mode on the Meta app on the phone

__Answer__
> Did not enable Developer Mode on the Meta app on the phone

## Q8) Where is createScene(...) normally defined?

- main.ts
- app.ts
- index.html
- package.json
- package-lock.json
- tsconfig.json

__Answer__
> app.ts

## Q9) You want to add a custom script as part of your BabylonJS project test workflow. Which file should you modify?

- main.ts
- app.ts
- index.html
- package.json
- package-lock.json
- tsconfig.json

__Answer__
> package.json

## Q10) Which file should you add to your team's version control if you want the project dependencies to have the same exact versions across your team?

- main.ts
- app.ts
- index.html
- package.json
- package-lock.json
- tsconfig.json

__Answer__
> package-lock.json

## Q11) What does the following Babylon.js snippet accomplish?

>   const xr = await scene.createDefaultXRExperienceAsync({
>       uiOptions: {
>           sessionMode: "immersive-vr",
>       },
>   });

- Initializes typical components for hybrid XR (AR & VR) experience
- Makes a non-blocking method call to initialize components
- Creates a default BabylonJS scene with a sphere
- Waits for all components to complete initialization before continuing

__Answer__
> Makes a non-blocking method call to initialize components

## Q12) What is the main reason for choosing WebXR as the core development stack?

- It provides the best immersion
- Our research is based on it
- It is open-source and meant for accessible cross-platform applications
- Most immersive applications are built with it
- It is a robust API and has little issues

__Answer__
> It is open-source and meant for accessible cross-platform applications

## Q13) What is the optimal development tool for this project?

> You are engaged by a mining company to build a VR system for training their own miners to operate in a coal mine. They have funds to purchase any necessary hardware you propose that is suitable and within reasonable budget. They need the working system delivered within a short 6 months time. Which tool is most suitable for you to base your development on?

- Unity
- OpenXR SDK in C++
- Babylon.js
- CoSpaces
- Blender

__Answer__
> Unity

## Q14) What is the optimal development tool for this project?

> You are building your own metaverse application, an immersive social network that aims to allow as many users as possible to participate in, using different platforms and devices. You have limited funds as an individual of course, and aim to spend as little as possible on development. Which tool is most suitable for you to base your development on?

- Unity
- OpenXR SDK in C++
- Babylon.js
- CoSpaces
- Blender

__Answer__
> Babylon.js

## Q15) What standard to focus on?

- OpenGL
- WebGL
- WebXR
- OpenXR
- OpenCL
- Vulkan

__Answer__
> OpenXR