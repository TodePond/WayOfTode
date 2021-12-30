This is a work-in-progress!

# Way of Tode

This is the **Way of Tode**!<br>
It's the approach I like to use when I code creative hobby projects.<br>
I don't always follow the Way of Tode. But when I do, it helps me to do two things:<br>
🐸 Have fun!<br>
🐸 Be fast!<br>

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
## Scope
<details>
<summary>
	🐸 <b>Todes make what they need!</b>
</summary>

Make what you need (nothing more, nothing less).
```js
// We need to add two numbers together!
const add = (a, b) => a + b
```

</details>

<details><summary>🤖 <b>Robots make what they might need!</b></summary>

Don't spend time making what you might never need.
```js
// We need to add two numbers together! We MIGHT need to add together more than two numbers!
const add = (...ns) => ns.reduce((a, b) => a + b, 0)
```

</details>
	
## Ideas
🐸 **Todes prototype ideas!**<br>
If you have an idea, make it NOW. You will learn something from it.
```js
// This is my idea for adding two numbers together!
const add = (a, b) => a + b
```

🤖 **Robots think about ideas!**<br>
If you have an idea, don't just think about it. You will learn more from trying to make it.
```js
// I have an idea for adding two numbers together... but I haven't made it yet!
```

## Attachment
🐸 **Todes delete old code!**<br>
Delete code if you need to.
```js
// I deleted my old code and replaced it with this new code!
const add = (a, b) => a + b
```

🤖 **Robots keep old code!**<br>
Don't grow attached to code. Every line of code is temporary. Every line of code is waiting to be replaced by something better.
```js
// This is my old code! I don't want to delete it!
const add = (...ns) => ns.reduce((a, b) => a + b, 0)

// This is my new code!
const addTwoNumbers = (a, b) => a + b
```

## Help
🐸 **Todes accept contributions!**<br>
Accept other people's code, even if it's not something you would make. It's more fun this way.
```js
// Credit to Magnogen for this fix!
const add = (a, b, c = 0) => a + b + c
```

🤖 **Robots reject contributions!**<br>
Don't be too picky over contributions. It'll be a more lonely experience.
```js
const add = (a, b) => a + b
```

# Part 2: Style
## Consistency
🐸 **Todes mix styles!**<br>
You can mix different styles together, such as tabs and spaces.

```js
// This is good!
const add = (a, b) => {
	return a + b
}

// This is also good!
function subtract( a, b ) {
  return a-b;
}
```

🤖 **Robots make styles consistent!**<br>
Don't spend time trying to make everyone's code the same style. It's like trying to make everyone's handwriting the same.

```js
// This is good!
const add = (a, b) => {
	return a + b
}

// This is also good, but some personality was lost!
const subtract = (a, b) => {
	return a - b
}
```

## TO BE CONTINUED
Notes:<br>
🐸 **Try to write code that can be understood by a kid.**<br>
No object-oriented.<br>
Use the fewest language features possible.<br>
Only make optimizations if you measure.<br>
JS specific rules.<br>
style -> minimum cleverness. repeat of language feature rule?<br>
