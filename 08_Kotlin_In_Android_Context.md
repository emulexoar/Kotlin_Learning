# Lesson 08 - Kotlin in Android Context

Goal:
Connect Kotlin basics to Android project work.

## Where Kotlin Is Used in Android

1. Activity/Fragment UI logic
2. ViewModel state handling
3. Repository/data source logic
4. Service/background logic
5. Utility/domain classes

## Example Mapping (From Typical Android App)

- MainActivity.kt handles button/toggle events
- MainViewModel.kt exposes LiveData state
- Data classes represent Room entities
- Services run long operations in background

## Kotlin Patterns You Will Use Daily

1. Data classes for models
2. Nullable safety with ? and ?:
3. Collection operations for transforming UI lists
4. Coroutines for async work

## Mini Android Example

class UserViewModel : ViewModel() {
    private val _name = MutableLiveData("Guest")
    val name: LiveData<String> = _name

    fun updateName(newName: String) {
        _name.value = newName
    }
}

## Exercises

1. Create simple User data class for profile screen.
2. Create function to validate email input.
3. Convert a for loop to filter/map style collection code.
