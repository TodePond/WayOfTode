This is a work-in-progress!

# Way of Tode

This is the Way of Tode!<br>
It's how true todes write code.<br>
Are you a total tode 🐸? or a rigid robot 🤖?<br>

## Style
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

## Scope
🐸 **Todes make what they need!**<br>
Make what you need (nothing more, nothing less).
```js
// We need to add two numbers together!
const add = (a, b) => a + b
```

🤖 **Robots make what they might need!**<br>
Don't spend time making what you might never need.
```js
// We need to add two numbers together! We MIGHT need to add together more than two numbers!
const add = (...ns) => ns.reduce((a, b) => a + b, 0)
```

## Thinking
🐸 **Frogs prototype ideas!**<br>
If you have an idea, make it NOW! You will learn something from it!
```js
// This is my idea for adding two numbers together!
const add = (a, b) => a + b
```

🤖 **Robots think about their ideas!**<br>
If you have an idea, don't just think about it. You will learn more from trying to make it!
```js
// I have an idea for adding two numbers together... but I haven't made it yet!
```

## Attachment
🐸 **Frogs delete their old code!**<br>
Delete your code if you need to! Every line of code is temporary! Every line of code is waiting to be replaced by something better!
```js
// I deleted my old bad code and replaced it with this new good code!
const add = (a, b) => a + b
```

🤖 **Robots keep their old code!**<br>
Don't grow attached to your code! If you want to improve it, delete it!
```js
// This is my old code! I don't want to delete it!
const add = (...ns) => ns.reduce((a, b) => a + b, 0)

// This is my new code!
const addTwoNumbers = (a, b) => a + b
```

## TO BE CONTINUED
Notes:<br>
🐸 **Try to write code that can be understood by a kid.**<br>
No object-oriented.<br>
Use the fewest language features possible.<br>
Only make optimizations if you measure.<br>
JS specific rules.<br>
