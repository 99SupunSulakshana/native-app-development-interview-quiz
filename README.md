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
    - It's supported by a smaller community as compared to others. But It's growing rapidly.
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
  

  
