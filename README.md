# ⭕Native-app-development-interview-quiz
Native Mobile Application Development Interview Quiz

Q1. Native Vs Flutter Vs React Native❓

  - ✔ Native
    * 🌟 iOS 
        - Languages: Swift, Objective-C
        - IDE: Xcode
        - UI Framework: UIKit, SwiftUI
        - Native apps typically offer the best performance because they are compiled to the native binary and can leverage all the platform's capabilities.
        - Immediate access to the latest platform features and updates.
        - Native components and interactions provide a seamless user experience.
        - Strong support from Apple’s ecosystem with comprehensive development tools and resources.
        - Native iOS apps typically have smaller initial app sizes because they rely on the platform's built-in libraries and components.
        - Apple’s App Store guidelines restrict dynamic code updates. Any code changes require a new app submission and review process.
        - Native apps offer the best performance as they are directly compiled into platform-specific code. They have direct access to device hardware and platform-specific features.
        - Developing separate codebases for iOS and Android can be time-consuming.
        - Higher development and maintenance costs due to the need for separate teams or skill sets.
    * 🌟 Android
        - Language: Kotlin, Java
        - IDE: Android Studio
        - UI Framework: Android Jetpack Compose
        - Direct access to Android hardware and features.
        - Extensive documentation and support from the Android community.
        - Similarly, native Android apps also tend to have smaller sizes as they leverage built-in Android libraries and components.
        - Allows some degree of dynamic updates (e.g., using Google Play’s in-app updates API) but is also generally restrictive.
        - Optimal performance, best use of hardware capabilities, seamless integration with platform features.
        - Separate development for Android and iOS leads to increased time and effort.
        - Managing different device specifications and screen sizes can add complexity.
          
  - ✔ React Native
    - React Native is a cross-platform framework created by Facebook.
    - It's based on the JavaScript programming language. Java script is a widely used programming language for web development.
    - It uses the native UI components for both Android and iOS. It provides the native look which means different UI on Android and iOS, Android Native UI on Android, and iOS Native UI on iOS.
    - UI and business logic code (that we write in JavaScript for React Native Apps) can be updated simply through HTTP requests from the app directly.
    - React Native Apps are relatively smaller as compared to Flutter.
    - React Native uses a bridge to communicate JavaScript and native components, which is an overhead. It can have performance issues due to the bridge between JavaScript and native components. React Native is comparatively slower than Flutter.
    - It's supported by a large community as it has been for so long time.
    - It has a wide range of third-party library support.
    - Web developers can start quickly.
    - Platform support: iOS, Android.
      
 - ✔ Flutter
    - Flutter is a cross-platform framework created by Google.
    - Flutter is based on the Dart programming language, developed by Google specifically for building mobile and web apps.
    - It uses its rendering engine to create its UI components. So, it replaces the native platform UI components It provides the same look on all the platforms.
    - Code pushes not supported. This is a major disadvantage of Flutter.
    - Flutter apps are relatively large as compared to React native apps.
    - Flutter is comparatively faster than React Native as it uses a rendering engine that directly renders to the platform leading to fast and smooth animations.
    - A smaller community supports it as compared to others. But It's growing rapidly.
    - It has a learning curve as developers need to learn the Dart Language.
    - Platform support: iOS, Android, Web, Desktop, embedded systems.

q2. Kotlin Scoped Functions❓

  Kotlin provides a set of powerful functions known as scope functions to help write concise, readable, and expressive code. These functions allow you to execute a block of code in the context of an object, reducing the need for repetitive code and enabling more fluent programming patterns. The primary scope functions in Kotlin are let, run, with, apply, and also. Each of these functions has its unique behaviour and use case, and they are distinguished mainly by how they access the object (this or it) and what they return.

<a href="#"><img width="90%" height="500px" src="https://github.com/user-attachments/assets/49a5e26a-34ab-491c-bcf5-4303774b91a5"/></a>
  
let

The let function is a versatile Kotlin tool useful for null safety, scoping, and chaining operations. It helps write more readable and safe code, especially when dealing with nullable types and transformations. By utilizing let, you can ensure that certain operations are only performed when an object is non-null, and you can keep your code concise and expressive.

run

The run function in Kotlin is a versatile tool that can be used to execute a block of code on an object with this as the context or without a receiver as a standalone lambda. It's especially useful for avoiding repetition of the object name when accessing its properties and methods. The use of run makes code more concise and readable, and it's commonly used for object initialization, transformations, and computing results based on object properties.

with

In Kotlin, the with function is a scope function used to work with an object within a block of code, providing a context where the object is accessed via this keyword. Unlike let, run, apply, and with, it is not an extension function but is instead used as a regular function. It is typically used for performing operations on an object, especially when you want to perform multiple actions and avoid repeating the object reference.

apply

Kotlin, the apply function is a scope function that operates on an object and returns that object itself after applying a series of operations to it. The object is accessed inside the block using this keyword, and because the object itself is returned, apply is often used for object configuration and initialization.

also

In Kotlin, also is a scope function that is used to perform additional operations on an object. Like apply, it allows you to work with an object within a block of code. However, the key difference is that also provides the object as an argument (it) to the lambda block, rather than using this reference. This function returns the object itself, making it useful for chaining operations where you want to perform some side effects (like logging or validation) without altering the object.

  
q3. What is the Kotlin❓
  
Kotlin is a statically typed programming language running on the JVM fully interoperable with Java. As such, it is robust and secure in addition to being concise and expressive hence effective for numerous types of development with a special edge rooted in Android app development.

q4. Kotlin Features❓

⭐ Kotlin is 100% compatible with Java, as a result calling Java from Kotlin and vice-versa is seamless. This allows developers to migrate their Java codebase to Kotlin gradually or mix Kotlin and Java in the same project.

⭐ Kotlin eliminates boilerplate codes and enables developers to write concise, more readable codes versus Java. For example, data classes can make your code much more concise along with features like Type inference and smart casts.

⭐ Kotlin by nature reduces the possibility of null pointer exceptions with built-in support. Variables are non-nullable by default, and the language offers various operators to handle nullable types safely.

⭐ Kotlin supports modern programming paradigms, including object-oriented programming, functional programming, and procedural programming. It provides features like higher-order functions, lambdas, and extension functions, making the language highly expressive and flexible.

⭐ Since Kotlin was developed by JetBrains, it has excellent support in JetBrains’ IntelliJ IDEA IDE, which is also the basis for Android Studio. Kotlin is also supported by major build tools like Gradle and Maven.

⭐ Kotlin offers coroutines, which are a powerful feature for handling asynchronous programming simply and efficiently. Coroutines allow developers to write asynchronous code that is almost as straightforward as synchronous code.


q5. Use Cases For Kotlin❓

⭐ Kotlin is the preferred language when it comes to Android development. Kotlin is the new official language for writing Android Apps by Google from 2017 and it has been supported by Google to develop Android apps since May 2019.

⭐ Kotlin is also good for server-side applications with frameworks like Ktor or Spring and offers a modern alternative to Java on the backend.

⭐ Kotlin Multiplatform allows developers to write code that can run on multiple platforms (e.g., iOS, Android, Web) with a single codebase, enabling code reuse across different environments.

⭐ Kotlin can be used as a scripting language, using its concise and expressive syntax for writing small scripts or automating tasks.


q6. Kotlin features, but not in Java❓

Null Safety
Data Classes
Extension Functions
Smart Casts
Higher-Order Functions and Lambdas
Coroutines
Type Inference
Named and Default Arguments
Delegated Properties
Sealed Classes
Operator Overloading
Range expressions...etc.

q7. Difference between var and val❓

Both var and val are used for the declaration of variables. A variable declared var is mutable, meaning that its value can be changed after it has been initialized. Use var when you need to reassign a new value to the variable at some point in your code.

    var name = "Kotlin"
    println(name) // Outputs: Kotlin
    
    name = "Java"
    println(name)

A variable declared with val is immutable, meaning that once it has been assigned a value, it cannot be reassigned. Use val when you want to create a read-only reference, ensuring that the variable's value remains constant after initialization.

    val language = "Kotlin"
    println(language)

q8. Types of Constructors in Kotlin❓

Primary Constructor
  The primary constructor is a concise way to declare and initialize properties in a class. It is defined in the class header after the class name and can have optional parameters. The primary constructor cannot contain any code. The initialization code can be placed in the init block.

    class Person(val name: String, var age: Int) {
      init {
          println("Person's name is $name and age is $age")
      }
  }
  
    val person = Person("John", 26) // Output: Person's name is John and age is 26

Secondary Constructor
  A secondary constructor is defined inside the class body using the constructor keyword. A class can have multiple secondary constructors. Secondary constructors are useful when you need to add additional logic or when you want to offer different ways to initialize an object. If the class has a primary constructor, the secondary constructor must delegate to the primary constructor using this().

    class Person(val name: String) {
      var age: Int = 0
  
      constructor(name: String, age: Int) : this(name) {
          this.age = age
          println("Person's name is $name and age is $age")
      }
  }

    val person = Person("John", 26) // Output: Person's name is John and age is 26

q9. When in Kotlin❓

when can be used as both an expression and a statement. This means it can return a value and be assigned to a variable, which makes it more versatile. switch in Java is only a statement and cannot return a value directly.

    val result = when (x) {
        1 -> "One"
        2 -> "Two"
        else -> "Unknown"
    }

when can work with a wide range of types, including integers, strings, enums, booleans, and even objects. This makes it more versatile compared to, which traditionally works with a limited set of types like integers, enums, and strings.

    when (x) {
        is Int -> println("x is an integer")
        is String -> println("x is a string")
        else -> println("x is of some other type")
    }

when automatically breaks after a match is found, so you don't need to include break statements to prevent fall-through behaviour, unlike switch.

when allows you to use ranges, conditions, or multiple values in a single branch, making it more expressive.

when supports smart casting, meaning that once you check a type, you can use that type directly in the corresponding block without needing to cast explicitly.

    when (val obj = someObject) {
        is String -> println("Length of the string is ${obj.length}")
        is Int -> println("The number is $obj")
        else -> println("Unknown type")
    }

In when, if all possible cases are covered (especially with enums or sealed classes), you don't need an else block.

    enum class Direction { NORTH, SOUTH, EAST, WEST }
    
    fun navigate(dir: Direction) = when (dir) {
        Direction.NORTH -> println("Going north")
        Direction.SOUTH -> println("Going south")
        Direction.EAST -> println("Going east")
        Direction.WEST -> println("Going west")
    }

when allows you to group multiple values into a single branch, making the code cleaner and reducing redundancy.

    when (x) {
        1, 2, 3 -> println("x is 1, 2, or 3")
        else -> println("x is something else")
    }

q10. Kotlin Range Expression❓

In Kotlin, range expressions provide a way to create sequences of values in a defined range. Ranges are used to loop through values, check if a value falls within a particular range, or generate sequences.

Basic Range Expression — A basic range is created using the .. operator. This creates a range that includes the start and end values.

    val range = 1..5  // Represents the range 1, 2, 3, 4, 5
    for (i in range) {
        println(i)  // Output: 1 2 3 4 5
    }

Descending Ranges — To create a range in descending order, use the downTo keyword.

    val descendingRange = 5 downTo 1  // Represents the range 5, 4, 3, 2, 1
    for (i in descendingRange) {
        println(i)  // Output: 5 4 3 2 1
    }

Range with Step — You can define a step for a range using the step keyword, which allows you to skip elements in the range.

    val stepRange = 1..10 step 2  // Represents the range 1, 3, 5, 7, 9
    for (i in stepRange) {
        println(i)  // Output: 1 3 5 7 9
    }

Check if a Value is in a Range — The in keyword can be used to check if a value lies within a range.

    val x = 3
    if (x in 1..5) {
        println("$x is in the range 1 to 5")  // Output: 3 is in the range 1 to 5
    }

Range with Characters — Ranges can also be created with characters.

    val charRange = 'a'..'d'  // Represents the range 'a', 'b', 'c', 'd'
    for (ch in charRange) {
        println(ch)  // Output: a b c d
    }

Until — The until the keyword can be used to create a range that is exclusive of the end value.

    val untilRange = 1 until 5  // Represents the range 1, 2, 3, 4 (excluding 5)
    for (i in untilRange) {
        println(i)  // Output: 1 2 3 4
    }

Range Functions — Ranges in Kotlin come with built-in functions like reversed(), contains(), and first/last, which can be very useful.

    val range = 1..5
    println(range.reversed())  // Output: 5, 4, 3, 2, 1
    println(range.contains(3))  // Output: true
    println(range.first)  // Output: 1
    println(range.last)  // Output: 5

q11. Data Classes❓

Data classes in Kotlin provide a concise way to create classes that are used for holding data. They automatically generate useful methods like equals(), hashCode(), toString(), copy(), and componentN() functions, which simplify the handling of data in your code. Data classes are especially useful for models, DTOs (Data Transfer Objects), and other objects where the primary concern is to store and manage state.

requirements:

The primary constructor needs to have at least one parameter.
The parameters of the primary constructor should be marked as val or var.
Data classes cannot be abstract, open, sealed, or inner classes.

Automatic Generation of Methods:

equals(): Compares two instances for equality based on their properties.
hashCode(): Generates a hash code for the object based on its properties.
toString(): Returns a string representation of the object, listing its properties.
copy(): Creates a copy of the object with the ability to modify some of its properties.
componentN(): Functions that allow destructuring declarations.

q12. Null Safety❓

Null safety in Kotlin is a key feature that helps prevent the common null pointer exceptions (NPEs), which are a common source of runtime errors in many programming languages. Kotlin’s type system is designed to eliminate null references from code, making applications more robust and safer. Kotlin’s null safety features significantly reduce the chances of encountering null pointer exceptions by making the type system aware of nullability. With nullable types, safe calls, Elvis operators, non-null assertions, and smart casts, Kotlin provides a robust framework for handling null values, leading to safer and more reliable code.

👉 Nullable and Non-Nullable Types
By default, all types in Kotlin are non-nullable, meaning you cannot assign null to a variable unless explicitly declared as nullable. You can declare a nullable type by appending a ? to the type.

    var nonNullableString: String = "Hello"  // Non-nullable type
    // nonNullableString = null  // This would cause a compile-time error
    
    var nullableString: String? = "Hello"  // Nullable type
    nullableString = null  // This is allowed

👉 Safe Calls (?.)
The safe call operator ?. is used to access properties or methods of a nullable type without throwing an NPE. If the object is null, the call returns null instead of throwing an exception.

    val length: Int? = nullableString?.length  // Returns null if nullableString is null

👉 Elvis Operator (?:)
The Elvis operator is used to provide a default value when a nullable expression evaluates to null.

    val length = nullableString?.length ?: 0  // Returns 0 if nullableString is null

👉 Non-Null Assertion (!!)
The non-null assertion operator !! can be used to assert that a value is non-null. If the value is actually null, it will throw an NPE at runtime.

    val length = nullableString!!.length  // Throws NPE if nullableString is null

👉 Smart Casts
Kotlin’s compiler automatically performs smart casts when it can guarantee that a nullable variable is not null. This is usually done after a null check.

    if (nullableString != null) {
        println(nullableString.length)  // Smart cast to non-nullable type
    }

👉 Let Function
The let function is often used with safe calls to execute a block of code only if the object is non-null.

    nullableString?.let {
        println("The length of the string is ${it.length}")
    }

👉 lateinit and Null Safety
The lateinit keyword allows you to declare a non-nullable variable without initializing it at the time of declaration. However, if you try to access it before it is initialized, an UninitializedPropertyAccessException is thrown.

    lateinit var name: String
    name = "Kotlin"
    println(name)

👉 Nullable Collections
You can have collections of nullable types, which means the collection itself is non-null, but it can contain null elements.

    val nullableList: List<String?> = listOf("Kotlin", null, "Java")


q13. Object Keyword in Kotlin❓

In Kotlin, the object keyword is a versatile feature that can be used in different contexts to define singletons, companion objects, and anonymous objects. It provides a way to create objects without needing to explicitly declare a class. It simplifies the design of classes that should have only one instance or require static-like behaviour and allows for flexible, one-time-use objects. Whether used for organizing code, managing global state, or implementing interfaces on the fly, the object keyword is a cornerstone of Kotlin’s object-oriented programming features.

👉 Singletons

  The object keyword is used to define a singleton, a class with only one instance. This is useful for classes that don’t need multiple instances, such as utility classes or managers. A singleton object is created when accessed for the first time and globally accessible.

    object DatabaseConnection {
        val url = "jdbc:mysql://localhost:3306/mydb"
        fun connect() {
            println("Connecting to the database at $url")
        }
    }
    
    fun main() {
        DatabaseConnection.connect()  // Output: Connecting to the database at jdbc:mysql://localhost:3306/mydb
    }

👉 Companion

  Companion objects are used to define members of a class that belong to the class itself, rather than to instances of the class. This is similar to static members in Java. A class can have only one companion object, and it is defined inside the class using the companion object keyword. Companion objects can be named or anonymous. If unnamed, they can be accessed using the class name.

    class MyClass {
        companion object {
            val CONSTANT = 42
            fun show() {
                println("Hello from the companion object!")
            }
        }
    }
    
    fun main() {
        println(MyClass.CONSTANT)  // Output: 42
        MyClass.show()  // Output: Hello from the companion object!
    }


👉 Anonymous Objects

The object keyword can also be used to create anonymous objects, which are objects without a named class. This is particularly useful when you need a one-time-use object with certain properties or methods. Anonymous objects can be used for implementing interfaces or abstract classes on the fly.

    val myObject = object {
        val x = 10
        val y = 20
        fun printValues() {
            println("x = $x, y = $y")
        }
    }
    
    fun main() {
        myObject.printValues()  // Output: x = 10, y = 20
    }

👉 Object Inheritance

Singleton objects can extend classes or implement interfaces. This allows them to inherit properties and methods, just like regular classes.

    open class BaseClass(val name: String) {
        open fun greet() {
            println("Hello from BaseClass")
        }
    }
    
    object DerivedSingleton : BaseClass("DerivedClass") {
        override fun greet() {
            println("Hello from DerivedSingleton")
        }
    }
    
    fun main() {
        DerivedSingleton.greet()  // Output: Hello from DerivedSingleton
    }


q14. Sealed Classes❓

In Kotlin, sealed classes are a special type of class that allows you to represent restricted class hierarchies. A sealed class can have a limited set of subclasses, which are known and defined at compile time. This feature is particularly useful when you want to model data types with a fixed number of possible states.

👉 Restricted Class Hierarchy

  Sealed classes restrict the subclasses that can inherit from them. All the subclasses must be defined in the same file as the sealed class. This makes the class hierarchy more controlled and predictable.

    sealed class Result
    data class Success(val data: String) : Result()
    data class Error(val message: String) : Result()
    object Loading : Result()

👉 Exhaustive when Expressions

  When you use a when expression with a sealed class, the compiler knows all possible subclasses, so it can ensure that all cases are handled. If you forget to handle a subclass, the compiler will give you a warning or error.

    fun handleResult(result: Result) {
      when (result) {
          is Success -> println("Success: ${result.data}")
          is Error -> println("Error: ${result.message}")
          Loading -> println("Loading...")
          // No need for an `else` branch since all cases are covered
      }
    }

👉 Immutability and Data Classes

  Sealed classes often work well with data classes to represent different states or results.

    sealed class Operation
    data class Addition(val x: Int, val y: Int) : Operation()
    data class Subtraction(val x: Int, val y: Int) : Operation()


👉 Sealed Interfaces

  Starting with Kotlin 1.5, you can also use sealed interfaces, which allow you to define a sealed hierarchy that includes both classes and interfaces.

    sealed interface Operation
    data class Addition(val x: Int, val y: Int) : Operation
    data class Subtraction(val x: Int, val y: Int) : Operation


👉 Advantages Over Enum Classes

  Sealed classes are more flexible than enum classes because each subclass of a sealed class can have its properties and methods. Enum constants, by contrast, are single instances that cannot have different types or properties.

    enum class Direction {
        NORTH, SOUTH, EAST, WEST
    }
    
    // vs.
    
    sealed class Direction
    object North : Direction()
    object South : Direction()
    object East : Direction()
    object West : Direction()

👉 Object Subclasses

  You can define subclasses of a sealed class as objects if they don’t need to hold any state. This is useful for representing a fixed number of singleton states.

    sealed class UserAction
    object Login : UserAction()
    object Logout : UserAction()

👉 Sealed Class Visibility

  Sealed classes and their subclasses can be public or have other visibility modifiers. The subclasses don’t have to be nested inside the sealed class, but they must be in the same file.

    sealed class Response
    internal data class Success(val data: String) : Response()
    private object Failure : Response()

👉 Type Safety

  Sealed classes enhance type safety by ensuring that all possible states are considered, reducing the likelihood of runtime errors and making your code more reliable.


q15 . @JvmStatic, @JvmOverloads, and @JvmField annotations in Kotlin❓

👉 @JvmStatic

The @JvmStatic annotation is used to make a method or property in a companion object or object accessible as a static method or field in Java. In Kotlin, there is no concept of static members, so this annotation helps when you need to expose Kotlin code to Java, which expects static members.

    class MyClass {
        companion object {
            @JvmStatic
            fun staticMethod() {
                println("This is a static method")
            }
    
            fun regularMethod() {
                println("This is a regular method")
            }
        }
    }

  usage java:

    public class Main {
        public static void main(String[] args) {
            MyClass.staticMethod(); // Works because of @JvmStatic
            MyClass.Companion.regularMethod(); // Without @JvmStatic, you'd need to access via Companion
        }
    }


👉 @JvmOverloads

The @JvmOverloads annotation is used to generate overloaded versions of a Kotlin function that has default parameter values. In Kotlin, you can provide default values for function parameters, but in Java, this isn’t directly supported. The @JvmOverloads annotation automatically generates all possible overloaded versions of the function for use in Java.

    class MyClass {
        @JvmOverloads
        fun greet(name: String = "Guest", age: Int = 18) {
            println("Hello $name, you are $age years old")
        }
    }

 usage java:

 
    public class Main {
        public static void main(String[] args) {
            MyClass myClass = new MyClass();
            myClass.greet();              // Hello Guest, you are 18 years old
            myClass.greet("Alice");       // Hello Alice, you are 18 years old
            myClass.greet("Bob", 25);     // Hello Bob, you are 25 years old
        }
    }


👉 @JvmField

The @JvmField annotation is used to expose a Kotlin property as a public field in Java. By default, Kotlin properties generate getter and setter methods, but @JvmField removes these and exposes the property directly as a field. This can be useful for interoperability when using Kotlin properties from Java or when you need to work with libraries that expect fields instead of methods.

    class MyClass {
        @JvmField
        var name: String = "Kotlin"
    
        companion object {
            @JvmField
            val version = "1.5"
        }
    }


 q16 . Inline Function❓

In Kotlin, inline functions are a powerful feature that can improve performance by reducing the overhead of function calls, particularly in higher-order functions. When you mark a function as inline, the compiler replaces the function call with the actual code of the function at compile time. This can lead to more efficient code, especially in performance-critical situations.

    inline fun <T> performOperation(value: T, operation: (T) -> Unit) {
        operation(value)
    }
    
    fun main() {
        performOperation(5) { println(it * 2) }
    }


👉 Why Use Them?

Performance: By lowering the overhead of function calls, inline functions can enhance performance, particularly when a function is called repeatedly or inside tight loops.

Lambda and Higher-Order Functions: when passed from a lambda or anonymous function to a higher-order function, it prevents the construction of extra objects and reduces memory allocations.


👉 Important Points:

Code Size: Because the function’s body is duplicated to each call site, inlining functions results in larger produced code.

Recursion: Recursive functions cannot be inlined since doing so would lead to an endless inlining operation. Therefore, inline functions cannot be recursive.

Non-local Returns: You can return from the caller function inside the inline function since inline functions enable non-local returns. On the other hand, this may make the code more difficult to read and update.


 q17 . Extension Function❓

Extension functions in Kotlin allow developers to add new functions to existing classes without modifying their source code. These functions are defined outside of the class but can be called as if they were a part of the class. This is particularly useful when you want to add utility methods to a class that you don’t own or don’t want to extend through inheritance.

    fun TypeName.extensionFunctionName(parameters): ReturnType {
        // function body
    } 

Example:

    fun String.addExclamation(): String {
        return this + "!"
    }
    
    fun main() {
        val myString = "Hello"
        println(myString.addExclamation())  // Output: Hello!
    }

Extension functions do not override member functions. The extension function to be called is determined by the type of the expression at compile time, not the runtime type of the object.


q18 . Non-line Functions❓

A non-inline function is simply a regular function that doesn’t use the inline keyword. Assume that we do not want all of the lamdas passed to an inline function to be inlined, in this case, We can mark those function parameters with the non-line modifier. Unlike inline functions, these functions are not inlined at the call site by the compiler.

    fun addNumbers(a: Int, b: Int): Int {
        return a + b
    }
    
    fun main() {
        val result = addNumbers(3, 5)
        println("The sum is: $result")  // Output: The sum is: 8
    }

  Non-inline functions are executed with a normal function call. The function’s code is not copied to the call site, so there’s no increase in the code size.
  
  Non-inline functions may have some overhead associated with the function call, especially in the case of high-order functions where lambdas or function references are passed.
  
  Unlike inline functions, non-inline functions can be recursive because there’s no concern about copying the function code to the call site.
  
  In cases where performance optimization isn’t critical, and you’re dealing with straightforward operations, non-inline functions are typically sufficient.


q18 . Higher-Order Functions❓

A higher-order function is a function that takes functions as parameters or returns a function or both.

  Can take functions as parameters.
  Can return a function.

    fun performOperation(a: Int, b: Int, operation: (Int, Int) -> Int): Int {
        return operation(a, b)
    }
    
    fun add(x: Int, y: Int): Int = x + y
    fun multiply(x: Int, y: Int): Int = x * y

    fun main() {
        val sum = performOperation(5, 3, ::add)  // Passing the 'add' function
        println("Sum: $sum")  // Output: Sum: 8
    
        val product = performOperation(5, 3, ::multiply)  // Passing the 'multiply' function
        println("Product: $product")  // Output: Product: 15
    }

q19 . Crossinline Functions❓

Crossinline in Kotlin is used to avoid non-local returns. When we add the crossline, it will not allow us to put the return inside that lambda. It ensures that the lambda passed to the inline function cannot be non-locally returned from.

    inline fun performAction(crossinline action: () -> Unit) {
        // Some other code...
        someOtherFunction {
            action()  // Since `action` is `crossinline`, it cannot cause a non-local return.
        }
    }
    
    fun someOtherFunction(callback: () -> Unit) {
        callback()
    }
    
    fun main() {
        performAction {
            println("Action performed")
            // return // This would cause a compiler error due to `crossinline`
        }
    }


q20 . Scoped Functions❓

The Kotlin standard library contains several functions whose sole purpose is to execute a block of code within the context of an object. When you call such a function on an object with a lambda expression provided, it forms a temporary scope. In this scope, You can access the object without their name. Therefore, These functions are called scoped functions. Mainly there are five scoped functions: let, run, with, apply, and also.


q21 . init block❓

In Kotlin init block is used to initialize an object, when an instance of a class is created. init block is executed immediately after the primary constructor of the class is called, in addition to performing additional initialization logic. The init block is a powerful tool and it can be used to improve the design and maintainability of our code.

    class Person(val name: String, val age: Int) {
        val isAdult: Boolean
    
        init {
            isAdult = age >= 18
            println("Person's name is $name and age is $age")
        }
    
        init {
            println("Is $name an adult? $isAdult")
        }
    }
    
    fun main() {
        val person = Person("John", 25)
    }

q22 . lateinit keyword❓

In Kotlin lateinit is used if we don’t want to initialize a variable at the time of the declaration and want to initialize it at a late point in time. Especially, we need to make sure that initialize it before use. We can notice that the lateinit variable needs to be non-nullable.

👉 when we use the lateinit property things to consider:

  used with the var keyword.
  used with the non-nullable variable.
  can be initialized later.
  this variable is mutable.
  make sure this variable is initialised before use.


     lateinit var name: String
    
        fun initializeName() {
            name = "John Doe"
        }


q23 . lazy keyword❓

The lazy in Kotin is used when we want to create a property that is initialized only when it is first accessed, that is known as lazy initialization. It’s useful when we defer the initialization of a property until it’s needed, potentially saving resources or improving performance.

👉 when we use the lazy property things to consider:

  used only with the val keyword, it’s a read-only property.
  we want the variable to be initialized only if we need it for the first time.
  lazy property only creates the object when we access it for the very first time, then in the subsequent access, it returns the same object.
  

     class Example {
        val heavyComputation: String by lazy {
            println("Computing the value...")
            "Result of heavy computation"
        }
    }
    
    fun main() {
        val example = Example()
    
        println("Before accessing heavyComputation")
        println(example.heavyComputation)  // Computation happens here
        println(example.heavyComputation)  // This time, it doesn't recompute
    }

q24 . const keyword❓

The const keyword is used to declare a constant in compile-time. As a result, no values may be assigned at runtime to const variables. That is immutable (read-only) and at the time of declaration must be initialized with a value. In addition to them, the const keyword is used with the val keyword.

👉 when we use the const keyword things to consider:

  const can be used at the top level or as a member of an object or a companion object only.
  const can be applied with primitive data types and the string type only.
  No custom getter. The variable will be initialized at runtime. Therefore you cannot assign a const variable to a function or a class.

    const val PI = 3.14159
    const val APP_NAME = "MyKotlinApp"
    
    object Constants {
        const val MAX_USERS = 100
        const val BASE_URL = "https://example.com"
    }
    
    fun main() {
        println("PI value: $PI")
        println("App name: $APP_NAME")
        println("Max users: ${Constants.MAX_USERS}")
        println("Base URL: ${Constants.BASE_URL}")
    }


q25 . open keyword❓

The open keyword is used to allow a class, variable or function to be extended or overridden. In Kotlin, all classes and members are final. as a result, they cannot be inherited or overridden unless explicitly marked as open. The open keyword allows for inheritance, which is a core principle in object-oriented programming, enabling polymorphism and code reuse.

    open class Animal {
        open fun sound() {
            println("Animal makes a sound")
        }
    
        open val name: String = "Animal"
    }
    
    class Dog : Animal() {
        override fun sound() {
            println("Dog barks")
        }
    
        override val name: String = "Dog"
    }
    
    fun main() {
        val myDog = Dog()
        myDog.sound()  // Prints: Dog barks
        println("Animal name: ${myDog.name}")  // Prints: Animal name: Dog
    }

q26 . Companion Object❓

Developers can call the method without creating the object of the class in Java with the use of a static keyword. In Kotlin, We do not have a static keyword. Therefore, It’s a way to define static members in Kotlin.

👉 Important points to keep in mind while defining a companion object or using it:

  A companion object must be defined inside a class using a companion object. It gets a default name as a Companion when we do not enter a name.
  Developers can skip the name when calling a method or accessing a value.
  It is the same as the static keyword in Java.
  The companion object is instantiated for the first time after the containing class is loaded.
  without creating an instance of the class, members of a companion object can be accessed.
  if you define properties inside of your companion object. These properties act as static properties.

    class MyClass {
        companion object {
            fun myStaticFunction() {
                println("This is a static function")
            }
        }
    }

    
q27 . Infix Notations❓

Infix notation in Kotlin allows a function to be called without the use of the dot and parentheses. It allows us to call functions in a more readable way. As we have read above the functions marked with the infix keyword can also be called using the infix notation. It means that We can omit the dot and the parentheses. As a result, This makes your code more expressive and closer to natural language.

Example:

    class Person(val name: String) {
        infix fun greet(other: Person) {
            println("$name says hello to ${other.name}")
        }
    }

Usage:

    val alice = Person("Alice")
    val bob = Person("Bob")
    
    alice greet bob  // Output: Alice says hello to Bob

Common Usage:

    val pair = "one" to 1  // Creates a Pair<String, Int>

q28 . associateBy❓

The associateBy function is used as an extension function to convert a collection into a map. It creates a map from a collection by applying a function to each element to generate the keys.

    data class Person(val name: String, val age: Int)
    
    val people = listOf(
        Person("Alice", 30),
        Person("Bob", 25),
        Person("Charlie", 35)
    )
    
    val mapByName = people.associateBy { it.name }
    
    println(mapByName)
    // Output: {Alice=Person(name=Alice, age=30), Bob=Person(name=Bob, age=25), Charlie=Person(name=Charlie, age=35)}

q29 . partition❓

The partition in Kotlin is used to split a collection into two lists based on a given predication. The first list contains those that match the prediction, and the second one includes those that do not.

    val numbers = listOf(1, 2, 3, 4, 5, 6)
    
    val (even, odd) = numbers.partition { it % 2 == 0 }
    
    println(even)  // Output: [2, 4, 6]
    println(odd)   // Output: [1, 3, 5]

q30 . Kotlin Coroutines❓

Coroutines stand for cooperating functions. Co means cooperation, and Routines means functions. When functions cooperate, we can call it a coroutine. Kotlin Coroutines are a powerful feature for managing asynchronous programming and concurrency in Kotlin. They provide a simple, efficient way to handle tasks like making network requests, reading data from a database, or performing background processing without blocking the main thread in a sequential style. Coroutines are lightweight threads that help manage background tasks by providing a structured way to handle concurrency while avoiding callback hell and complex threading code.

Coroutines can execute a few lines of one function and then they will execute a few lines of another function. Then again a few lines of the previous function and so on. In this case, it can take full advantage of the thread. It will be helpful when a thread is sitting idle and not doing anything. In addition to them, It will synchronously enable writing asynchronous code. I can say, that coroutine makes multitasking very easy. Coroutines do not replace threads, It's like a framework to manage them as well. It's lightweight. But it has a powerful environment that uses cooperative native functions. Therefore, It's an optimized framework written over the threading using cooperative native functions. It means it does not map on the native thread, thus it does not require context switching on the processor.

Two types of coroutines.
    1. Stackless
    2. Stackful
    
Kotlin is used by stackless coroutines. In Kotlin, the coroutine does not have its stack. Therefore they do not map on the thread.

Features of Coroutines

  Light Weight
  A coroutine has a collection of threads that can be used when required. When the task is done, the thread is returned to the collection and reused when needed.     Coroutines allow you to run many coroutines concurrently without consuming too many resources. Because of the support for suspension, you can run many coroutines on a single thread, which does not block the thread where the coroutine is running, which is why it is called lightweight.
  
  Fewer memory leaks
  Kotlin coroutines follow structured concurrency, which is why there are very less memory leaks in Kotlin. It means, it can only launch the new coroutine in a particular coroutine scope, which sets the lifetime of the coroutine. If we implement a large number of coroutines, the structured concurrency takes responsibility for it. Therefore, there are no leaks or losses.
  
  Built-in cancellation support
  Coroutines are cooperative when it comes to cancellations. cancellation in the coroutine is interactive. Coroutines automatically check for cancellation and stop execution when cancelled. You can cancel a coroutine by calling cancel() on its Job or CoroutineScope.

  Jetpack Integrations
  There are many libraries for Jetpack that provide support for coroutines.
  
  Non-Blocking
  Coroutines allow you to write asynchronous code without callback or complex thread management. Functions like suspend make it easier to suspend the execution of a coroutine without blocking the main thread, resuming only when the task is complete.

  Efficient Resource Management
Coroutines are lightweight and use fewer resources compared to traditional threads. They are suspended when not in use and resumed only when needed, reducing memory and CPU overhead.

Basic standard use case of coroutine in Android application.
- fetch the user from the server & show the user in the UI

      fun main() {
          fun fetchUser(){
              GlobalScope.launch(Dispatcher.Main){
                  val user = fetchUserDetails()
                  showUser(user)
              }
          }
          
          suspend func fetchUserData(): User{
              return withContext(Dispatcher.IO){
                  //make network call on IO thread.
                  // return User.
              }
          }
      }

When we call the fetchAndShowUser function without using coroutines, it will throw the NetworkOnMainThreadException. Therefore the network call is not allowed on the main thread directly.

Dispatchers

  We can use coroutines to perform certain tasks efficiently. Therefore, we should coroutines run the task on a particular thread. Therefore, This is the time when the Dispatchers come into play. Dispatchers help coroutines in deciding the thread on which the work has to be done.
  
  There are 4 types of Dispatchers in Kotlin Coroutines
  
  Dispatchers.Default : used to perform CPU-intensive tasks. ex: sorting, filtering, searching large lists…etc.
  Dispatchers.IO : used to perform disk or network I/O-related tasks. ex: network requests, downloading files from the server…etc.
  Dispatchers.Main : used to run on the main thread of Android. ex: UI-related tasks, small tasks…etc.
  Dispatchers.Unconfined : used to not be confined to any specific thread where the coroutine will be executed.

Suspending Function

Suspending functions can be started, paused and resumed at a later time without blocking the thread. It’s only allowed to be called from a coroutine or another suspend function.

    suspend fun doLongRunningTask(){
            return withContext(Dispatcher.IO){
                delay(2000)
            }
        }


Coroutine Builders

launch

launch is a function that is used to start the coroutines in Kotlin. It will fire and forget. It will return a job and does not return any result value. Therefore, we can use it to get a job’s status or to cancel it. In addition, If any exception comes inside the launch block, it crashes the application if we have not handled it.

    import kotlinx.coroutines.*

    fun main() = runBlocking {
        val job = launch {
            delay(1000)
            println("Coroutine finished")
        }
        println("Waiting for coroutine...")
        job.join()  // Waits for the coroutine to finish
    }


async

async is a function that is used to start the coroutines in Kotlin. It will concurrent task with a result. It’s designed for tasks that run concurrently. It will return a Deferred<T> object which represents a future result that can be obtained using await(). In async also, We can get a job’s status or cancel it using the Deferred job object. Therefore, when we need to results back, we need to use async. Such as making an API call or performing a computation. In addition, If any exception comes inside the async block, it will stored inside the resulting Deffered and it will get dropped unless we handle it.

    import kotlinx.coroutines.*
    
    fun main() = runBlocking {
        val deferred = async {
            delay(1000)
            "Result from coroutine"
        }
        println("Waiting for result...")
        val result = deferred.await()  // Waits for the result
        println(result)
    }

runBlocking

runBlocking is used in blocking coroutine. It means that while the coroutines running on the current thread, that current thread is blocked. It is often used at the entry point of the application. It will return the result of the coroutine execution. Ex: if we write sequential code inside a coroutine in the situation.

    import kotlinx.coroutines.*
    
    fun main() = runBlocking {
        println("Coroutine starts")
        delay(1000)  // Suspension inside runBlocking
        println("Coroutine ends")
    }

withContext

withContext is used to switch context. It will switch the coroutine to a different thread or a dispatcher. It returns the result of the code block. For example, It performs tasks on specific dispatchers, like moving from Dispatchers.IO for background work to Dispatchers.Main for UI updates.

    import kotlinx.coroutines.*
    
    fun main() = runBlocking {
        withContext(Dispatchers.IO) {
            delay(1000)
            println("Running in IO context")
        }
    }



Scopes in Kotlin Coroutines

Coroutine scopes control how coroutines are launched, cancelled them, and manage their execution within a specific context. coroutine scope provides structured concurrency, ensuring that coroutines are managed and cleaned up when no longer needed. It defines the lifecycle of coroutines.

GlobalScope

The GlobalScope is used to launch coroutines that live until the application does. It is not bound to any specific lifecycle. They run independently of the whole application. Therefore, It can lead to memory leaks or unstructured concurrency. Because there is no defined boundary for when the coroutine should be cancelled.

    import kotlinx.coroutines.*
    
    fun main() {
        GlobalScope.launch {
            delay(1000)
            println("GlobalScope coroutine")
        }
        println("Main function continues...")
        Thread.sleep(2000)  // Wait to see coroutine result
    }


CoroutineScope

CoroutineScope allows to creation of a scope that is bound to a particular job or lifecycle while ensuring structured concurrency. When we launch coroutines in a structured way, especially in long-running operations, we can use it.

    import kotlinx.coroutines.*
    
    fun main() = runBlocking {
        val myScope = CoroutineScope(Dispatchers.Default)
    
        myScope.launch {
            delay(1000)
            println("Coroutine in myScope")
        }
        
        println("Main function continues...")
        delay(2000)  // Wait to see coroutine result
    }


lifecycleScope

LifecycleScope is a coroutine scope tied with the Android Life Cycle of activities or fragments. Assuming that our activity is the Scope, the background task should get cancelled as soon as the activity is destroyed. Therefore in this case we should use lifeCycleScope to launch a coroutine.

    class MyActivity : AppCompatActivity() {
        override fun onCreate(savedInstanceState: Bundle?) {
            super.onCreate(savedInstanceState)
            lifecycleScope.launch {
                delay(1000)
                println("Coroutine inside lifecycleScope")
            }
        }
    }

    
viewModelScope

viewModelScope is a coroutine scope tied with the ViewModel Life Cycle. It is provided by the Jetpack libraries. It is all the coroutines in this scope automatically cancelled when the ViewModel is cleared.

    class MyViewModel : ViewModel() {
        fun fetchData() {
            viewModelScope.launch {
                delay(1000)
                println("Fetching data in viewModelScope")
            }
        }
    }

    
supervisorScope

supervisorScope is used if the failure of a child coroutine does not cancel the parent or other sibling coroutine. Only failed coroutine is cancelled from them. When we want some coroutines to fail independently without affecting other coroutines, we can use supervisorScope.

    import kotlinx.coroutines.*
    
    fun main() = runBlocking {
        supervisorScope {
            launch {
                delay(500)
                println("This will run")
            }
    
            launch {
                throw RuntimeException("Failed coroutine")
            }
    
            println("SupervisorScope is still running")
        }
    }

    
custom Scope

You can create a custom CoroutineScope using a Job and a specific dispatcher to control the lifecycle and behaviour of coroutines.

    import kotlinx.coroutines.*
    
    fun main() = runBlocking {
        val job = Job()  // Creating a custom Job
        val customScope = CoroutineScope(Dispatchers.Default + job)
    
        customScope.launch {
            delay(1000)
            println("Custom coroutine")
        }
    
        // Cancel the custom scope
        job.cancel()
        println("Custom scope canceled")
    }


q31 . Kotlin Flows❓

Kotlin Flows are part of the Koltin Coroutines library. It provides a powerful and flexible way to handle asynchronous data streams in a reactive programming style. That emits values to the collector and gets completed with or without an exception. In addition, Flows can emit multiple values over time, making them a natural fit for scenarios like handling data streams or events.

Features of Flows

  👉 Kotlin Flows are cold. No data will be produced until the flow is actively collected. This contrasts with hot streams, Like RxJava’s observables, which begin emitting values as soon as created.
  
  👉 Flows can emit values without blocking the calling thread and operate them asynchronously.
  
  👉 Flows can handle slow consumers efficiently. In this case, They can suspend their execution until the downstream is ready to collect more data.
  
  👉 Flows respect structured concurrency and can be cancelled when necessary. Because They are tightly integrated with Kotlin Coroutines.
  
  👉 Flows provide a variety of operators for transforming data (ex: mao, fileterm reduce…etc).
  
  👉 Flows can handle exceptions gracefully using operators like catch and onCompletion.
  
  The major components of flow are as below:
  
  👉 Flow builder (Speaker)
  
  👉 Operator (Translator)
  
  👉 Collector (Listener)

Flow Builder

Flow builder mainly helps in creating a flow (doing a task) and multiple values emitting items asynchronously. It provides a simple way to define a stream of data that will be produced and collected over time. Sometimes it is just required to emit the items without doing any task, for example, just emit a few numbers(1,2,3). Here, The flow builder helps us do so. We can think of this as a speaker. The Speaker will think (do a task) and speak(emit the items). The flow builder is part of Kotlin’s Coroutines library and allows for emitting values using the emit function.

    flow {
        // Inside this block, you can emit values using emit()
        emit(value)
        // Perform suspending operations, such as delays or network requests
    }

    import kotlinx.coroutines.*
    import kotlinx.coroutines.flow.*
    
    fun main() = runBlocking {
        // Creating a flow using flow builder
        val numberFlow: Flow<Int> = flow {
            for (i in 1..5) {
                delay(100) // Simulate a time-consuming operation
                emit(i) // Emit each number
            }
        }
    
        // Collecting the flow
        numberFlow.collect { value ->
            println("Received: $value")
        }
    }

Operator

The Operator is used to transform the data from one format to another format. It acts as a translator. Assume that the speaker is speaking in French and the collector(Listner) understands English only. In this case, We need to translate French into English using the translator. That translator is an Operator. In addition, using the operator we can also provide the thread on which the task will be done.

Collector

The collector collects the items emitted using the flow builder which are transformed by the operators. It acts as a listener. The collector is a terminal operator. It comes under the operator.

Types of flow builders

  👉 flowOf() — It’s used to create a flow that emits a given fixed set of values.
    
    flowOf(1,2,3,4,5,6)
      .collect {
         Log.d(TAG, it.toString())
    }
  👉 asFlow() — It’s an extension function that allows conversion other collections into flows.
    
    (1..5).asFlow()
      .collect{
         Log.d(TAG, it.toString())
    }
  👉flow{} — It is used to emit multiple values asynchronously and perform complex operations using suspending functions.
    
    flow {
      (0..10).forEach {
        emit(it)
    }.collect {
      Log.d(TAG, it.toString())
      }
    }
  👉channelFlow{} — This builder is more advanced and is used to create a flow that can handle concurrent emits. It is suitable for flows with multiple concurrent and allows you to launch coroutines within the block.
    
    channelFlow {
      (0..10).forEach {
        send(it)
    }.collect {
      Log.d(TAG, it.toString())
      }
    }

flowOn operator

  flowOn is a convenient way to control the thread on which the task will be done. Generally, in Android, we do tasks on a background thread and show the result on the UI thread.
    
    flow {
        emit(someData)
        // Upstream logic here
    }.flowOn(Dispatchers.IO) // Shifts the flow's upstream emission to the IO dispatcher
    import kotlinx.coroutines.*
    import kotlinx.coroutines.flow.*
    
    fun main() = runBlocking {
        // Flow that emits values on a different dispatcher
        val numberFlow = flow {
            for (i in 1..5) {
                delay(100) // Simulating a time-consuming task
                println("Emitting on: ${Thread.currentThread().name}")
                emit(i)
            }
        }.flowOn(Dispatchers.IO) // Moves flow emission to IO dispatcher
    
        // Collecting the flow on the main thread
        numberFlow.collect { value ->
            println("Collected on: ${Thread.currentThread().name}, value: $value")
        }
    }


Long-running tasks in parallel

  Zip Operator
  
  zip operator
  The zip operator is an operator that emits a single value, combining the emission of two collections using a specified function. For example, when we need to run a couple of tasks in parallel, then if we need the results of both functions in a single callback when both tasks are completed, we can use the zip operation.
  
  Advantages of zip operator of Kotlin flow:
  
  👉 Runs tasks in parallel
  
  👉 Return the results of tasks in a single callback when all the tasks are completed.
  
    val zippedFlow = flow1.zip(flow2) { value1, value2 ->
        // Combine or transform value1 and value2
        transformedResult
    }
    import kotlinx.coroutines.*
    import kotlinx.coroutines.flow.*
    
    fun main() = runBlocking {
        val numbersFlow = flowOf(1, 2, 3)
        val stringsFlow = flowOf("A", "B", "C")
    
        // Zipping two flows together
        val zippedFlow = numbersFlow.zip(stringsFlow) { number, letter ->
            "$number -> $letter"
        }
    
        // Collect and print the results
        zippedFlow.collect { result ->
            println(result)
        }
    }

Retry Operators

retry

The retry() operator re-executes the flow when an error occurs. It will keep returning until the task gets completed successfully. We can set the optional conditions for limiting retries. We can mention the number of retries and an optional predicate to control whether a retry should happen based on the exception.

    import kotlinx.coroutines.*
    import kotlinx.coroutines.flow.*
    
    fun main() = runBlocking {
        var attempt = 0
    
        val flow = flow {
            attempt++
            if (attempt < 3) {
                println("Flow execution failed, attempt: $attempt")
                throw RuntimeException("Error on attempt: $attempt")
            } else {
                emit("Success on attempt: $attempt")
            }
        }.retry(2) // Retry up to 2 times on failure
    
        flow.collect { result ->
            println(result)
        }
    }

retryWhen

The retryWhen is used for more control over retry logic. They allow to us define custom conditions based on both the exception and the number of attempts. Therefore, we can decide whether to retry based on these parameters.

    import kotlinx.coroutines.*
    import kotlinx.coroutines.flow.*
    
    fun main() = runBlocking {
        val flow = flow {
            emit("Attempting to emit")
            throw RuntimeException("Failed to emit")
        }.retryWhen { cause, attempt ->
            println("Attempt $attempt failed with: $cause")
            attempt < 2 // Retry only twice
        }
    
        flow.collect { value ->
            println(value)
        }
    }


StateFlow

StateFlow is a type of flow created to hold and emit the current state of a value, that can be observed and updated over time. It emits values as soon as the collector starts collecting. StateFlow is hot. This means it always has an initial value and emits the latest value to all collectors. Therefore, It always holds a single item/value, up-to-date value. when we start a new collector, it immediately receives the latest value. StateFlow doesn’t emit consecutive repeated values. It emits the value only when it is distinct from the previous value. Similar to LiveData except for the LifeCycle awareness of the Android component. We can use repeatOnLIfeCycle scope with StateFlow to add the LifeCycle awareness to it, then it will become exactly like LiveData. StateFlow is suitable for representing state in UI components (like viewModels), where the UI needs to react to changes in state. It retains the last emitted state, which is essential for use cases like UI state in Android apps. In addition, StateFlow is thread-safe. It can be shared across multiple threads without issues.

basic example

    import kotlinx.coroutines.*
    import kotlinx.coroutines.flow.*
    
    fun main() = runBlocking {
        // Create a MutableStateFlow with an initial value
        val stateFlow = MutableStateFlow(0)
    
        // Launch a coroutine to collect the StateFlow
        val job = launch {
            stateFlow.collect { value ->
                println("Collected: $value")
            }
        }
    
        // Update the state
        stateFlow.value = 1
        delay(100)
        stateFlow.value = 2
        delay(100)
        stateFlow.value = 3
    
        job.cancel() // Cancel the collector
    }

    
StateFlow in a viewModel

    import kotlinx.coroutines.flow.MutableStateFlow
    import kotlinx.coroutines.flow.StateFlow
    import androidx.lifecycle.ViewModel
    
    class MyViewModel : ViewModel() {
        // Private mutable state flow
        private val _uiState = MutableStateFlow("Initial State")
    
        // Publicly exposed as read-only StateFlow
        val uiState: StateFlow<String> = _uiState
    
        // Function to update the state
        fun updateState(newState: String) {
            _uiState.value = newState
        }
    }
    
Collecting StateFlow a UI

    @Composable
    fun MyComposable(viewModel: MyViewModel) {
        val uiState by viewModel.uiState.collectAsState()
    
        Text(text = uiState) // Automatically updates when uiState changes
    }

SharedFlow

SharedFlow is used to manage a stream of values that can be observed by multiple collectors simultaneously without losing events event if no collector is present at the time of emission. It is designed for scenarios where you, share the stream of data. It is a hot flow. SharedFlow can emit multiple values and It doesn’t retain the last state unless configured with a buffer. By the way, You can configure how many past events should be replayed to new collectors.

example:

    import kotlinx.coroutines.*
    import kotlinx.coroutines.flow.*
    
    fun main() = runBlocking {
        // Create a MutableSharedFlow
        val sharedFlow = MutableSharedFlow<Int>()
    
        // Launch two collectors
        val job1 = launch {
            sharedFlow.collect { value ->
                println("Collector 1 received: $value")
            }
        }
    
        val job2 = launch {
            sharedFlow.collect { value ->
                println("Collector 2 received: $value")
            }
        }
    
        // Emit values to the SharedFlow
        sharedFlow.emit(1)
        sharedFlow.emit(2)
        sharedFlow.emit(3)
    
        delay(100)
    
        job1.cancel()
        job2.cancel()
    }


replay feature

    val sharedFlow = MutableSharedFlow<Int>(replay = 2) // Replays the last 2 values
    
    // Emit values to SharedFlow
    sharedFlow.emit(1)
    sharedFlow.emit(2)
    sharedFlow.emit(3)
    
    // New collector receives the last 2 emitted values (2 and 3)
    sharedFlow.collect { value ->
        println("Collector received: $value")
    }


Buffer Feature

The buffer feature allows it to hold a certain number of values that are waiting to be collected. This feature ensures that if collectors are slow or if the producer is emitting values too quickly, they don’t get dropped.

    val sharedFlow = MutableSharedFlow<Int>(extraBufferCapacity = 2) // 2 extra buffer slots
    
    // Emit values to SharedFlow
    sharedFlow.emit(1)
    sharedFlow.emit(2)
    sharedFlow.emit(3) // This is buffered if no collector is active
    
    // Collect all values
    sharedFlow.collect { value ->
        println("Collector received: $value")
    }


SharedFlow in Android ViewModel and UI Components

    import kotlinx.coroutines.flow.MutableSharedFlow
    import kotlinx.coroutines.flow.SharedFlow
    import androidx.lifecycle.ViewModel

    class MyViewModel : ViewModel() {
        private val _eventsFlow = MutableSharedFlow<String>()
        val eventsFlow: SharedFlow<String> = _eventsFlow
    
        fun triggerEvent(eventMessage: String) {
            _eventsFlow.tryEmit(eventMessage) // Trigger an event
        }
    }
    @Composable
    fun MyComposable(viewModel: MyViewModel) {
        LaunchedEffect(Unit) {
            viewModel.eventsFlow.collect { event ->
                println("Event received: $event")
            }
        }
    }


Combining StateFlow and SharedFlow

StateFlow: Used to represent the UI state (e.g., loading, content).
SharedFlow: Used to emit UI events like showing a snack bar or navigating to another screen.

    class MyViewModel : ViewModel() {
        // UI State (e.g., loading, content)
        private val _uiState = MutableStateFlow("Initial State")
        val uiState: StateFlow<String> = _uiState
    
        // UI events (e.g., navigation, showing messages)
        private val _uiEvents = MutableSharedFlow<String>()
        val uiEvents: SharedFlow<String> = _uiEvents
    
        fun updateState(newState: String) {
            _uiState.value = newState
        }
    
        fun triggerEvent(eventMessage: String) {
            _uiEvents.tryEmit(eventMessage)
        }
    }

Cold Flows

Cold flow does not produce or emit values until it is collected. In other words, cold flows are lazy. It means they do not perform any work or execute any code until a consumer starts collecting them. It does not store the data. This means that when the flow is collected, the values are consumed and are not retained by future collectors. The complete flow will begin from the beginning for each one of the collectors. It is like 1 to 1 mapping. This means a cold flow cannot have multiple collectors. It will create a new flow for each collector.

    import kotlinx.coroutines.*
    import kotlinx.coroutines.flow.*
    
    fun main() = runBlocking {
        val coldFlow = flow {
            println("Flow is starting")
            emit(1)
            emit(2)
            emit(3)
            println("Flow has finished")
        }
    
        println("Calling collect first time:")
        coldFlow.collect { value -> println("Collected: $value") }
    
        println("Calling collect second time:")
        coldFlow.collect { value -> println("Collected: $value") }
    }


Hot Flows

Hot Flows are always active and that do not wait for collectors to start. It emits values whether collectors are present or not. They keep emitting values even if no one is collecting them at the moment. They are similar to “broadcasts”. In addition, hot flow will keep on emitting the values, collectors get the values from where they have started collecting. Hot Flows are like 1 to N mapping. It means 1 flow for N collectors. It means a hot flow can have multiple collectors and each collector might get the latest state or live events depending on when they join.

Type of hot flows: StateFlow, SharedFlow
