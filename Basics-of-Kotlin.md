## Basics
```kotlin
fun main() {
    println("Hello, world!")
}
```
fun is a word in the Kotlin programming language. fun stands for function. A function is a section of a program that performs a specific task. <br/>
`fun main`
main is the name of this function. Functions have names, so they can be distinguished from each other. This function is called main,
because it is the first, or main, function that is called when you run the program. Every Kotlin program needs a function named main.


```kotlin
println("Happy Birthday!")
```

This line of code prints the Happy Birthday! text.

println tells the system to print a line of text.
Inside the parentheses you put the text to be printed.

## Variables
`val`
A variable declared using the val keyword can only be set once. You cannot change its value later in the program.
`var`
You can declare a changeable variable with the var keyword

## functions

```kotlin
fun main() {
    printBorder()
    println("Happy Birthday, Jhansi!")
    printBorder()  //function call
}

fun printBorder() {
    println("=======================") //function definition
}
```
`fun printBorder() {}`

A word about naming functions.
Notice how the name of the `function printBorder` starts with a lower-case letter and a verb. 
Function names almost always start with a lowercase letter, and a verb, and the name should 
describe what the function does. Like: print() or here, printBorder().

## function with parameters

```kotlin
fun main() {
    val border = "%"
    printBorder(border)
    println("Happy Birthday, Jhansi!")
    printBorder(border)
}

fun printBorder(border: String) {
    repeat(23) {
        print(border)
    }
    println()
}
```
border is of string type, an arguement of the function.

More than one: <br/>
`fun printBorder(border: String, timesToRepeat: Int) {`

## repeat
```kotlin
repeat(23) {
        print("=")
    }
```
Repeat something some number of times
## Nested repeat

```kotlin
fun printCakeBottom(age: Int, layers: Int) {
    repeat(layers) {
        repeat(age + 2) {
            print("@")
        }
        println()
    }    
}
```

### references
https://developer.android.com/courses/android-basics-kotlin/android-basics-kotlin-vocab
