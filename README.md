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
