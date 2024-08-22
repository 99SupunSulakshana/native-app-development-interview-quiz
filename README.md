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

