# Lesson 06 - Collections and Lambdas

Goal:
Work with lists/maps and process data quickly.

## Lists

val numbers = listOf(1, 2, 3, 4)
val mutableNumbers = mutableListOf(1, 2)
mutableNumbers.add(3)

## Maps

val ages = mapOf(
    "Marvin" to 25,
    "Ana" to 22
)

## Common Collection Operations

val scores = listOf(60, 80, 90, 50)
val passed = scores.filter { it >= 75 }
val boosted = scores.map { it + 5 }
val total = scores.sum()

println(passed)
println(boosted)
println(total)

## Lambdas

val multiply = { a: Int, b: Int -> a * b }
println(multiply(3, 4))

## forEach

val names = listOf("Kai", "Liam", "Noah")
names.forEach { println(it) }

## Exercises

1. Create list of 10 numbers and print only odd numbers.
2. Create list of names and print uppercase version.
3. Create product list and compute total cart amount.
4. Use map + filter on student score data.
