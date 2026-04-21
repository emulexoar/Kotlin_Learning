# Kotlin Beginner Cheat Sheet

## Syntax Basics

Program entry:
fun main() { }

Print:
println("text")

## Variables

Read only: val
Mutable: var

## Null Safety

Nullable type: String?
Safe call: value?.length
Fallback: value?.length ?: 0

## Conditions

if / else
when

## Loops

for (i in 1..10)
while (condition)

## Functions

fun greet(name: String): String { return "Hi $name" }
fun add(a: Int, b: Int) = a + b

## Classes

class User(val name: String)
data class Product(val id: Int, val name: String)

## Collections

listOf, mutableListOf, mapOf
filter, map, forEach, sum

## Coroutines

runBlocking
launch
async/await
delay

## Beginner Best Practices

1. Use val by default
2. Keep functions small and focused
3. Handle null safely
4. Name variables clearly
5. Write one small test case for key logic
6. Refactor repeated code early

## Next Learning Path

1. Kotlin official docs: https://kotlinlang.org/docs/home.html
2. Kotlin Koans: https://kotlinlang.org/docs/koans.html
3. Android Kotlin basics: https://developer.android.com/kotlin
4. Coroutines guide: https://kotlinlang.org/docs/coroutines-overview.html
