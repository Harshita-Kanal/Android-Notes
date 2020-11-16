## other declarations
In the example below, count is a variable of type Int that is assigned an initial value of 10:
```kotlin
var count: Int = 10
```

Int is a type that represents an integer, one of the many numerical types that can be represented in Kotlin. 
Similar to other languages, you can also use Byte, Short, Long, Float, and Double depending on your numerical data.

The var keyword means that you can reassign values to count as needed. For example, you can change the value of count from 10 to 15:

var count: Int = 10
count = 15

## Conditionals

```kotlin
if (count == 42) {
    println("I have the answer.")
} else {
    println("The answer eludes me.")
}
```
Kotlin features several mechanisms for implementing conditional logic. The most common of these is an if-else statement.
If an expression wrapped in parentheses next to an if keyword evaluates to true, 
then code within that branch (i.e. the immediately-following code that is wrapped in curly braces) is executed.
Otherwise, the code within the else branch is executed.

## if-else-if

```kotlin
var answer: String = if(num == 0){
"you have not scored well"
}
else if(num > 50){
"bad"
}
else{
"good"
}
```
The string value gets assigned to answer variable which is declared of type string


## When
As the complexity of the if-else-if statement grows, consider using the when statement
```kotlin
val answerString = when {
    count == 42 -> "I have the answer."
    count > 35 -> "The answer is close."
    else -> "The answer eludes me."
}

println(answerString)
```
`->` represents a condition, if the condition on the left-hand side of the arrow evaluates to true,
then the result of the expression on the right-hand side is returned.

