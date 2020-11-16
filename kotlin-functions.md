## Functions

```kotlin
fun generateAnswerString(countThreshold: Int): String {
    return if (count > countThreshold) {
        "I have the answer."
    } else {
        "The answer eludes me."
    }
}
```
generateAnswerString() is a fairly simple function. The function declares a variable and then immediately returns. When the result of a single expression
is returned from a function, you can skip declaring a local variable by directly returning the result of the if-else expression contained in the function
Here countThreshold is a varialbe of type int.

## Anonymous functions
```kotlin
val stringLengthFunc: (String) -> Int = { input ->
    input.length
}
```
Here stringLengthFunc takes an arguement of type String and returns of type int.



## references
https://developer.android.com/kotlin/learn
