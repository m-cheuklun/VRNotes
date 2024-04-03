# Implementing Interaction

[Discussion Link](https://github.com/orgs/sit-dia/discussions/17)

## Behaviors

- Predefined, reusable interactions w/o needing to customize
- Ex. Dragging, Scaling, Following, etc

## ActionManager

- Property changes triggered by pre-defined events
- Customizable interaction parameters 
    - Ex. Duration, Conditions, Triggers

## Observables

- General Code Construct for observer pattern
- Subscribe and receive notifications to events
- Fully customizable interactions

## Gizmo Manager

- Uses Gizmo to easily manipulate position, rotation and scale

# Menti Quiz

## Q1) Implement a jump action in your Babylon.js scene when the user presses the keyboard spacebar. Which trigger should you use in the ActionManager?

- OnPickTrigger
- OnInteractionEnterTrigger
- OnKeyUpTrigger
- NothingTrigger

__Answer__
> OnKeyUpTrigger

## Q2) Which implementation is the most straightforward, i.e, without reinventing the wheel?

> You want to create a button in your Babylon.js scene that, when touched, makes a door open with a creaking sound that lasts 0.5 seconds.

- Behaviors
- ActionManager
- Observables

__Answer__
> ActionManager

## Q3) In your babylon.js, you need to periodically track changes in the position of the dog object and automatically show updates on the HUD based on its proximity to different objects. Which implementation is the most straightforward, i.e, without reinventing the wheel?

- Behaviors
- ActionManager
- Observables

__Answer__
> Observables

## Q4) In your babylon.js, you need to periodically track changes in the position of the dog object and automatically show updates on the HUD based on its proximity to different objects. Which implementation is the most straightforward, i.e, without reinventing the wheel?

> In your Babylon.js scene, when a pen mesh and a paper mesh touch each other (i.e, intersect), you want to show virtual ink appearing.

- Behaviors
- ActionManager
- Observables

__Answer__
> Observables

## Q5) In your babylon.js, you need to periodically track changes in the position of the dog object and automatically show updates on the HUD based on its proximity to different objects. Which implementation is the most straightforward, i.e, without reinventing the wheel?

> In your Babylon.js scene, you want to make a dog object constantly follow your camera's movement at a set distance beside you.

- Behaviors
- ActionManager
- Observables

__Answer__
> ActionManager

## Q6) In your babylon.js, you need to periodically track changes in the position of the dog object and automatically show updates on the HUD based on its proximity to different objects. Which implementation is the most straightforward, i.e, without reinventing the wheel?

>   const onDistanceChangeObservable = new Observable<number>();
>   
>   let previousDistance: number;
>   scene.onBeforeRenderObservable.add(() => {
>       const currentDistance = Vector3.Distance( sphere.position, Vector3.Zero());
>   
>       if (currentDistance !== previousDistance) {
>           previousDistance = currentDistance;
>           onDistanceChangeObservable.notifyObservers(currentDistance);
>       }
>   });

- Behaviors
- ActionManager
- Observables

__Answer__
> Behaviors

## Q7) In total, how many observers were used here?

>   const onDistanceChangeObservable = new Observable<number>();
>   
>   let previousDistance: number;
>   scene.onBeforeRenderObservable.add(() => {
>       const currentDistance = Vector3.Distance( sphere.position, Vector3.Zero());
>   
>       if (currentDistance !== previousDistance) {
>           previousDistance = currentDistance;
>           onDistanceChangeObservable.notifyObservers(currentDistance);
>       }
>   });
>   
>   onDistanceChangeObservable.add(distance => {
>       helloText.text = ``d: ${distance.toFixed(2)}``;
>   })

- 0
- 1
- 2
- 3
- 4
- 5

__Answer__
> 2

## Q8) In total, how many observers were used here?

>   const onDistanceChangeObservable = new Observable<number>();
>   
>   let previousDistance: number;
>   scene.onBeforeRenderObservable.add(() => {
>       const currentDistance = Vector3.Distance( sphere.position, Vector3.Zero());
>   
>       if (currentDistance !== previousDistance) {
>           previousDistance = currentDistance;
>           onDistanceChangeObservable.notifyObservers(currentDistance);
>       }
>   });
>   
>   onDistanceChangeObservable.add(distance => {
>       helloText.text = ``d: ${distance.toFixed(2)}``;
>   })

- 0
- 1
- 2
- 3
- 4
- 5

__Answer__
> 2

## Q9) In total, how many observers were used here?

>   pointerDragBehavior.onDragObservable.add(eventData => {
>       console.log(sphere.position);
>   })

- 0
- 1
- 2
- 3
- 4
- 5

__Answer__
> 1

## Q10) What is the mechanics of the following code?

>   pointerDragBehavior.onDragObservable.add(eventData => {
>       console.log(sphere.position);
>   })

- It adds an Observable to pointerDragBehavior of the sphere
- It adds an Observer to the sphere
- It adds an Observer to onDragObservable of the pointerDragBehavior
- It adds and Observable to the sphere

__Answer__
> It adds an Observer to onDragObservable of the pointerDragBehavior

## Q11) Which API class in Babylon.js will allow you to easily add UI controls to easily manipulate the position, rotation, and scale of meshes in your scene?

- MultiPointerScaleBehavior
- GizmoManager
- PointerDragBehavior
- WebXRFeaturesManager

__Answer__
> GizmoManager

## Q12) What does ToTeleport do in the following Babylon.js code?

>   const teleportation = featureManager.enableFeature(
>       WebXRFeatureName.TELEPORTATION,
>       "stable",
>       {
>           xrInput: xr.input,
>           floorMeshes: [ground],
>           timeToTeleport: 2000,
>           useMainComponentOnly: true,
>           defaultTargetMeshOptions: {
>               teleportationFillColor: "#55FF99",
>               teleportationBorderColor: "blue",
>               torusArrowMaterial: ground.material,
>           },
>       },
>       true,
>       true
>   ) as WebXRMotionControllerTeleportation;

- Sets the duration of the teleportation animation
- Sets the maximum time to complete the teleportation
- Sets the minimum delay between each teleportation trigger
- Sets the time in to hold the button before teleportation triggers

__Answer__
> Sets the time in to hold the button before teleportation triggers