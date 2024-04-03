# Evaluating Immersive Experiences
[Discussion Link](https://github.com/orgs/sit-dia/discussions/5)

## 1. Evaluation-first approach
Products are primarily built for the users, not to satisfy the developers. Thus, the quality of the product needs to be evaluated at an early stage in the development lifecycle.

Test Driven Development (TDD): Write test cases FIRST, then write code, refactor code, repeat until all test cases are satisfied.

### What is immersion?
Immersion: "a deep mental involvement in an activity"
Split into two categories: immersion as system properties & immersion in user experiences
Measuring Immersion: depends on the category 

## 2. Immersion as system properties
Immersion (as system properties): "the specifications of the system that produces immersive experiences"
Can be 'measured' by looking at the specs sheet/technical qualities of XR devices
Can also be 'measured' by the software itself - e.g. graphical fidelity, how realistic the AI is, interaction controls(like finger tracking)

## 3. Immersion as user experiences
Immersion (as user experiences): "mixture of psychological and physiological constructs"
Can be measured using experiential constructs like: Presence, Flow, Cybersickness

### 3.1 Presence
Presence: "the feeling of being there"

#### Dimensions of Presence:
- Physical Presence: "the sense of being physically relocated to the virtual space"
- Social Presence: "the sense of being around other virtual beings"
Presence can vary from person to person: having high degrees of openness and extroversion tends to lead to higher presence
- Perceptions of the degree of environmental interaction
- Perceived fidelity and realism of the simulated environment

#### Measuring Presence
- Subjective Data (used more):
	- Self reporting questionnaires
		- Igroup Presence Questionnaire (IPQ)
			- Segregates Presence into 3 parts:
				- Spatial Presence: "the feeling of physical existence in the virtual space"
				- Involvement: "how captivated one is in the virtual world"
				- Experienced Realism/Realness: "how real the virtual world feels compared to the real world"
	- Interviews
- Objective Data
- Mix of both

### 3.2 Flow
Flow: "the mental state of extreme positive engagement, such that a person loses their self-consciousness"

#### Dimensions of Flow:
1. Clear goals, with immediate feedback
	- Feedback as to how progress to those goals are going (e.g. cycling, every push of the pedals drives a person a fixed distance closer)
2. Challenges that match a person's skill level
3. Complete concentration
4. Loss of self consciousness
5. Sense of control
6. Effortlessness
7. Transformation of time
8. Autotelic experience (intrinsic motivation, doing something because the person wants to)

#### Measuring Flow
- Subjective Data
	- Questionnaires
		- Flow State Scale & Flow State Scale 2,
			- Flow Short Scale (for shorter experiences)
				- Consolidates 8 flow dimensions into 3
					- Overall Flow
					- Absorption by Activity
					- Fluency of Performance

### 3.3 Cybersickness
Cybersickness: "symptoms of sickness due to cyber activities"
Cybersickness symptoms: Nausea, Dizziness, Disorientation, more physical discomforts...
Reducing Cybersickness: try to match the interactions of the real world as much as possible to a person's view of the virtual environment in a device

#### Measuring Cybersickness
- Subjective Data
	- Questionnaires: Simulator Sickness Questionnaire (SSQ), Virtual Reality Sickness Questionnaire (VRSQ), Cybersickness Questionnaire (CSQ)
		- Grouped into categories
			- Oculomotor(Eyes) Symptoms
			- Disorientation Symptoms
	- Qualitative Think-Aloud Data
- Objective Data
	- Skin conductance sensors (measure sweat)
	- Heart rate sensors
	- Electromyography (EMG), for face muscles

## 4. Affordances
Affordances: "the relationship between the properties of an object and the capabilities of an agent that determines how the system is used"
E.g. humans have hands that can curl around stuff, door knobs have small rounds surfaces that are about the size of a human hand -> a human may tend to curl their hand around a door knob

With regards to XR, some objects have very well defined affordances in the real world (people generally know how to hold a cup), but in XR, it depends on for the system/object is implemented (perhaps the programmers did not allow for cups to be picked up)

# End
Link: [Developing Immersive Applications: Evaluating Immersive Experiences - YouTube](https://www.youtube.com/watch?v=zNpo3Ue2Ui0)

---

# Menti Quiz
## Q1) Which of the following describes immersion from a systems perspective?

- Wide FOV
- Higher spatial presence
- Higher place illusion
- 8K Resolution display
- Lower cybersickness
- 6-DOF inside-out tracking

__Answer__
> Wide FOV
> 8K Resolution display
> 6-DOF inside-out tracking

## Q2) Which of the following describes immersion from an experiential perspective?

- Wide FOV
- Higher spatial presence
- Higher place illusion
- 8K Resolution display
- Lower cybersickness
- 6-DOF inside-out tracking

__Answer__
> Higher spatial presence
> Higher place illusion
> Lower cybersickness

## Q3) What experiential constructs were analysed in the user study in the paper on "Exploring Gameplay Experiences on the Oculus Rift"?

- Flow
- Presence
- Place illusion
- Plausibility illusion
- Cybersickness

__Answer__
> Flow
> Cybersickness

## Q4) What quantitative data was analysed in the user study in the paper on "Exploring Gameplay Experiences on the Oculus Rift"?

- Flow
- Presence
- Cybersickness
- Physiological measures
- User behaviors

__Answer__
> Flow
> Physiological measures

## Q5) What quantitative data was analysed in the user study in the paper on "Understanding User Experiences Across VR Walking-in-place Locomotion Methods"?

- Flow
- Presence
- Cybersickness
- Physiological measures
- User behaviors

__Answer__
> Flow
> Presence
> Cybersickness

## Q6) What qualitative data was analysed in the user study in the paper on "Understanding User Experiences Across VR Walking-in-place Locomotion Methods"?

- Flow
- Presence
- Cybersickness
- Physiological measures
- User behaviors

__Answer__
> Flow
> Presence
> Cybersickness
> User behaviors

## Q7) What type of data allows us to answer this research question in the most direct and convincing fashion?

![Is the VR version more immersive than the desktop version of myApp?](/images/IsVRmoreImmersiveThanMyPC.png)

- Observations
- Think-aloud during the experience
- Validated Questionaires
- Post-experience interviews
- Physiological sensing
- Telemetry

__Answer__ 
> Validated Questionaires

## Q8) What is the best type of data to answer this research question?

![What user experiences does the VR classroom intervention afford during the class?](/images/UserExperienceDoesVRAffort.png)

- Observations
- Think-aloud during the experience
- Questionaires
- Post-experience interviews
- Physiological sensing
- Telemetry

__Answer__
> Observations
> Think-aloud during the experience
> Post-experience interviews

## Q9) Which of the following is NOT a symptom of cybersickness?

- Blurred vision
- Eyestrain
- Giddiness
- Loss of self-consciousness
- Vertigo

__Answer__
> Loss of self-consciousness

## Q10) "This one feels dizzier than the previous one." - What dimension of cybersickness is this?

- Disorientation
- Nausea
- Oculomotor
- Involvement
- Realness

__Answer__
> Disorientation

## Q11) "I find it very straining on my eyes to look at stuff in the scene after a short while" - What dimension of cybersickness is this?

- Disorientation
- Nausea
- Oculomotor
- Involvement
- Realness

__Answer__
> Oculomotor

## Q12) Which cybersickness questionnaire is best when I need to use the results to inform V2.0 development of my VR

- SSQ
- CSQ
- VRSQ

__Answer__
> CSQ
> VRSQ

## Q13) Which cybersickness questionnaire should I use when I need to compare my results with a pool of prior research studies from others?

- SSQ
- CSQ
- VRSQ

__Answer__
> SSQ

## Q14) What is the type of experience being described here?

![I was surprised that 30 minutes already passed after I took off the headset. I thought I only played the game for 5 minutes.](/images/FlowExperience.png)

- Presence
- Flow
- Cybersickness

__Answer__
> Flow

## Q15) What is the type of experience being described here?

> My head knocked into the (real) wall as I tried to dodge the (virtual) ball coming towards me. My mum was actually telling me how close I got to the wall but I was totally unaware that she was talking

- Presence
- Flow
- Cybersickness

__Answer__
> Presence

## Q16) What is the type of experience being described here?

> My friends were telling me how stupid I looked when I was playing the VR game. When I was in the game, I wasn't aware at all how I looked, I just wanted to conquer the challenges in there.

- Presence
- Flow
- Cybersickness

__Answer__
> Flow

## Q17) What is the main affordance on a haptic glove for an experienced VR user?

- Reach out to touch things in the virtual environment
- Pick up the VR controller to interact with the virtual environment
- Wave hand in the air
- Hug another character in the virtual environment

__Answer__
> Reach out to touch things in the virtual environment

## Q18) Which design provides the right affordance for a door that is meant to be pushed

- Door with a large handle
- Door with a small handle
- Door with no handle and a flat metal plate
- Door with a twist knob
- Door with a large sign that says "PUSH"

__Answer__
> Door with no handle and a flat metal plate