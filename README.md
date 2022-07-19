This is a work-in-progress!

# Way of Tode

This is the **Way of Tode**!<br>
It's the approach I like to use when I code my hobby projects.<br>

Here is a haiku explaining my thoughts and feelings on the matter:
<p align="center">
	<i>sometimes I write code<br>
	like I'm a rigid robot 🤖<br>
	it works pretty well<br>
<br>
	but I much prefer<br>
	to write my code like a tode 🐸<br>
	it's a lot more fun<br></i>
</p>

# Contents 
**Part 1**: [Mindset](#part-1-mindset)<br>
**Part 2**: [Style](#part-2-style)<br>

# Part 1: Mindset
## Need
🐸 **Todes make what they need!**
```js
// We need to add two numbers together!
const add = (a, b) => a + b
```

🤖 <b>Robots make what they might need!</b><br>
```js
// We need to add two numbers together! We MIGHT need to add together more than two numbers!
const add = (...ns) => ns.reduce((a, b) => a + b, 0)
```
	
## Ideas
🐸 **Todes make ideas!**<br>
```js
// This is my idea for adding two numbers together!
const add = (a, b) => a + b
```

🤖 **Robots think about ideas!**<br>
```js
// I have an idea for adding two numbers together... but I haven't made it yet!
```

## Delete
🐸 **Todes delete old code!**<br>
```js
// I deleted my old code and replaced it with this new code!
const add = (a, b) => a + b
```

🤖 **Robots keep old code!**<br>
```js
// This is my old code! I don't want to delete it!
const add = (...ns) => ns.reduce((a, b) => a + b, 0)

// This is my new code!
const addTwoNumbers = (a, b) => a + b
```

## Help
🐸 **Todes accept help!**<br>
```js
// Credit to Magnogen for this fix!
const add = (a, b, c = 0) => a + b + c
```

🤖 **Robots reject help!**<br>
```js
const add = (a, b) => a + b
```

# Part 2: Style
## Consistency
🐸 **Todes mix styles!**<br>
```js
// This is fine!
const add = (a, b) => {
	return a + b
}

// This is also fine!
function subtract( a, b ) {
  return a-b;
}
```

🤖 **Robots make styles consistent!**<br>
```js
// This is correct!
const add = (a, b) => {
	return a + b
}

// This is also correct!
const subtract = (a, b) => {
	return a - b
}
```
