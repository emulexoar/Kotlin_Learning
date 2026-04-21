# Lesson 07 - Coroutines Basics

Goal:
Understand asynchronous programming in Kotlin.

## Why Coroutines

Apps freeze if long tasks run on main thread.
Coroutines help run tasks without blocking UI.

## Basic Example

import kotlinx.coroutines.*

fun main() = runBlocking {
    launch {
        delay(1000)
        println("Task finished")
    }
    println("Waiting...")
}

## Common Builders

- runBlocking: block current thread (mostly for demos/tests)
- launch: fire-and-forget job
- async: returns result with await

## async example

fun main() = runBlocking {
    val result = async {
        delay(500)
        40 + 2
    }
    println(result.await())
}

## Best Practice for Beginners

- Keep UI work on Main dispatcher.
- Run heavy work on IO or Default dispatcher.
- Avoid GlobalScope in production apps.

## Exercises

1. Launch two coroutines with different delays.
2. Use async to compute two values and add them.
3. Simulate API call with delay and print loading state.
