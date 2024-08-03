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

  https://github.com/user-attachments/assets/49a5e26a-34ab-491c-bcf5-4303774b91a5

  

  
