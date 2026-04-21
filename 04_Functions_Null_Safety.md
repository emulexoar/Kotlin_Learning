# Lesson 04 - Functions and Null Safety

Goal:
Create reusable functions and avoid null crashes.

## Functions

fun greet(name: String): String {
    return "Hello, $name"
}

fun main() {
    println(greet("Marvin"))
}

Short form:

fun add(a: Int, b: Int) = a + b

## Default Parameters

fun welcome(name: String = "Developer") {
    println("Welcome, $name")
}

## Null Safety

Nullable type:
var middleName: String? = null

Safe call:
println(middleName?.length)

Elvis operator:
val length = middleName?.length ?: 0

Not-null assertion (avoid unless necessary):
println(middleName!!.length)

## Why Null Safety Matters

In many languages, null causes runtime crashes.
Kotlin forces you to handle nullable values safely.

## Exercises

1. Create function area(width, height).
2. Create function isEven(number).
3. Create nullable email variable and print fallback text if null.
4. Create function formatName(first, middle, last) using nullable middle.
