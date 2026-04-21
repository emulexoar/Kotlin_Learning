# Lesson 02 - Variables, Types, and Operators

Goal:
Understand how Kotlin stores and manipulates data.

## Variables

Read-only variable:
val name = "Marvin"

Mutable variable:
var age = 25
age = 26

Rule:
- Use val by default.
- Use var only when value must change.

## Common Types

val text: String = "Kotlin"
val count: Int = 10
val price: Double = 19.99
val isActive: Boolean = true
val letter: Char = 'A'

## String Templates

val username = "Marvin"
val level = 1
println("User: $username, Level: $level")

## Operators

Arithmetic:
+, -, *, /, %

Comparison:
==, !=, >, <, >=, <=

Logical:
&&, ||, !

## Example

fun main() {
    val a = 10
    val b = 3
    println(a + b)
    println(a % b)
    println(a > b)
}

## Exercises

1. Create val for firstName, lastName, age.
2. Print a sentence using string templates.
3. Calculate total price from quantity and item price.
4. Print whether user is adult (age >= 18).
