# unity-learning

## What is a Sprite?
A sprite is a 2D graphic object obtained from a bitmap image

![image](https://user-images.githubusercontent.com/36237628/184505377-b38a6399-89ab-4cc0-9f45-d89cd283571f.png)

## Adjusting layer order (similar to z-index)
First select your sprite and then go to the component properties and there you will see the *Additional Settings* section and the *Order in Layer* field which is the one that we want to modify

![image](https://user-images.githubusercontent.com/36237628/184505560-b94ef897-a079-4aad-8881-05a33fa06afa.png)

---

## Naming scripts convention
Use came case, e.g:
*MyFirstScript*

---

## C# basics
* Variables
* If statements
* Methods
* Triggers
* Colliders
* References


### What are methods?
Methods (also called functions) execute blocks of code that makes our game do things
#### We can:
* use the methods already available in Unity
* Create our own methods

#### Initial unity methods
##### Start method
`void Start(){}`
This method will be executed once you run your game, it is called before the first frame update
##### Update method
`void Update(){}`
This methods will be executed once per frame

### transform.Rotate(x, y, z)
Used to rotate objects

### transform.Translate(x, y, z)
Used to move objects

---
## Variable types
* *int* - whole numbers
* *float* - fractional numbers (up to 6 decimal places)
* *double* - fractional numbers (up to 15 decimal places)
* *bool* - true or false
* *string* - sequence of characters

---
## Accesing variables from the inspector
Use the keyword `[SerializeField]` at the beginning of the variable that you want to make visible from the inspector.
e.g.
`[SerializeField] float steerSpeed = 0.1f;`
`[SerializeField] float moveSpeed = 0.01f;`

![image](https://user-images.githubusercontent.com/36237628/184704736-dc11bf23-8c9e-4fe1-9c6d-da261621e300.png)

---
## Input system
Converting the player's physical action (tg. button press, key press) into information for the game

*Route to access Input manager:* Edit > Project settings > Input Manager

### Input.GetAxis()
Returns the value of the virtual axis identified by axisName.

### Time.deltaTime()
Unity can tell us how long each frame took to execute.

When we multiply something by *Time.deltaTime* it makes our game "frame rate independent" that means that the game behaves the same on fast and slow computers.

![image](https://user-images.githubusercontent.com/36237628/184795169-36f0f6e2-98fb-4577-b9e1-48761787eba6.png)

---
## Colliders & Rigidbodies
