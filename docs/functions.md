---
sidebar_position: 2
---

# Functions

[//]: # (😅 😉 😜 😝 🤭 🤔 🤫 🤨 😒 😬 😮‍💨 😌 😔 🥶 😎 🧐 😕 🥺 😯 😓 🙈 🙊 👌 👆 🤞 👍 👊 👏 🕺 💃)

`Kotlin` has a very powerful support for functional programming. Having that in mind, it is important to know functions really well :wink: and I guess that's why you're here.

### Basic
_How do I write a `kotlin` function?_
```kotlin
fun hello(){
    println("Hello!")
}
```

:::info
- we use the `fun` keyword to declare a function, isn't it funny and fun 🕺 💃
- this is followed by the function name which in this case is `hello`
- adding _brackets_ `()` to encase our parameters and
- finally adding _curly brackets_ `{}` for our function body
:::

_But what about using it?_
```kotlin
hello()
// Prints > Hello!
```

_Another thing, you've mention parameters in the info section there, what are they?_

### Parameters
> **<mark>Parameters</mark>** are placeholders declared in a function, __*they don't have concrete values*__

> **<mark>Arguments</mark>** on the other hand are now the actual values passed to a function when it is being used

_Umm okay_ 🤨 _do you have an example?_
```kotlin
fun hello(name: String){ // name here is a PARAMETER
    println("Hello $name!")
}

hello("Kotlin") // "Kotlin" is an argument
// Prints > Hello Kotlin!
```
:::info
- `name` is declared as a parameter
- `"Kotlin"` is now an argument for the name parameter
- parameters are declared by specifiying the name of the parameter followed by the type
- you can declare more than one parameter for any function, just specify the name and type followed by a comma
:::

_What if I want to add more than one parameter?_
```kotlin
fun hello(greeting: String, name: String){
    println("$greeting $name!")
}

hello("Jambo", "Kotlin")
// Prints > Jambo Kotlin!
```

