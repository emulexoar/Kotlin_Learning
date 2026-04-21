# Lesson 03 - Control Flow

Goal:
Control how code runs using conditions and loops.

## if / else

val score = 82
if (score >= 75) {
    println("Passed")
} else {
    println("Failed")
}

## when (Kotlin switch alternative)

val day = 3
when (day) {
    1 -> println("Monday")
    2 -> println("Tuesday")
    3 -> println("Wednesday")
    else -> println("Unknown day")
}

## for loop

for (i in 1..5) {
    println(i)
}

## while loop

var x = 1
while (x <= 3) {
    println("x = $x")
    x++
}

## Exercises

1. Print numbers from 1 to 20.
2. Print only even numbers from 1 to 20.
3. Use when to print letter grade for scores.
4. Build a simple login attempt counter with while.
