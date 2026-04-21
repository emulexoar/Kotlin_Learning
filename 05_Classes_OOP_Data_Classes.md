# Lesson 05 - Classes, OOP, and Data Classes

Goal:
Model real-world objects with Kotlin classes.

## Basic Class

class User(val name: String, var age: Int) {
    fun intro() {
        println("I am $name, age $age")
    }
}

fun main() {
    val user = User("Marvin", 25)
    user.intro()
}

## Inheritance

open class Animal(val name: String) {
    open fun sound() = "Unknown"
}

class Dog(name: String) : Animal(name) {
    override fun sound() = "Woof"
}

## Data Class

data class Product(
    val id: Int,
    val name: String,
    val price: Double
)

Why use data class:
- Auto equals
- Auto hashCode
- Auto toString
- Auto copy

## Exercises

1. Create data class Student(id, name, grade).
2. Create class BankAccount with deposit and withdraw methods.
3. Create base class Vehicle and subclass Car.
