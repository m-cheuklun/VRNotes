# Creating Virtual Environments

# Menti Quiz

## Q1) Why do we need the following code?

>   // This is usually done for skybox materials
>   skyboxMaterial.backFaceCulling = false;

- User is outside the skybox mesh viewing the back face of the textures
- User is inside the skybox mesh viewing the back face of the textures
- Skybox is a cube that is meant to be visible from all sides
- Removing backface culling is a graphics programming good practice

> User is inside the skybox mesh viewing the back face of the textures

## Q2) Which line of code makes the skybox feel like it is part of the background surrounding the user?

-   skybox = MeshBuilder.CreateBox("skyBox",{size:1000.0},scene)
-   skyboxMat.backFaceCulling = false
-   skybox.reflectionTexture.coordinatesMode = Texture.SKYBOX_MODE
-   skyboxMat = new StandardMaterial("skyBox", scene)
-   skybox.material = skyboxMaterial

>   skybox = MeshBuilder.CreateBox("skyBox",{size:1000.0},scene)

## Q3) What will the following code do?

>   Btn.onPointerUpObservable.add((evtData) => {
>       alert("Hello Button at:\n x: "
>           + evtData.x
>           + " y: "
>           + evtData.y);
>   });

- After "click" is released on Btn, show location of pointer
- After "click" down on Btn, show location of pointer
- After "click" is released on Btn, show location of Btn
- After "click" down on Btn, show location of Btn
- Compile error

> After "click" is released on Btn, show location of Btn

## Q4) This code has a runtime error. Which line is the offending line that causes this?

>   async loadModelQuiz(scene: Scene) {
>       const meshes = await SceneLoader.ImportMeshAsync(
>           "", "assets/models/", "H20.glb", scene);
>       meshes[0].position.y = -1;
>   }

- 1
- 2
- 3
- 4
- 5

> 4

## Q5) What is the function of the debugLayer in the Scene class of Babylon.js?

- Provides visual UI overlays to inspect and manipulate scene live
- Optimizes display of complex meshes during debugging step-through
- Provides debug console to run live debug script
- Shows console.log outputs overlaid on the scene

> Provides visual UI overlays to inspect and manipulate scene live

## Q6) What is the optimal approach?

> You are tasked to build a VR application to provide a virtual tour of an art gallery. The goal is to provide potential bidders with a sense of scale and depth close to viewing the real thing. What is the optimal approach for creating the virtual environment?

- Model-based
- Image-based

> Image-based

## Q7) What is the optimal approach?

> You are tasked to build a VR application for caregivers to empathise with patients suffering from dementia. The experience is intended to be primarily audio-visual with the main interaction being navigating around a house. Realism should be the focus of the immersion. What is the optimal approach for creating the virtual environment?

- Model-based
- Image-based

> Image-based

## Q8) What is the optimal approach?

> You are tasked to build a VR application to teach physics in a classroom. Kids will be able to throw virtual balls to hit cans placed at different distances and heights. Plausible interactions should be the main focus of the immersion. What is the optimal approach for creating the virtual environment?

- Model-based
- Image-based

> Model-based