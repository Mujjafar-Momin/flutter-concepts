# Flutter Fundamentals

## 1. Core Flutter Concepts

* Difference between StatelessWidget vs StatefulWidget
* Widget lifecycle (initState → build → dispose)
* BuildContext (what it is, where it should/shouldn’t be used)
* Keys: GlobalKey, UniqueKey, ValueKey
* What is a widget? Element? RenderObject?
* Hot reload vs hot restart
* What happens during the Flutter render pipeline?
* What application lifecycle states (ACTIVE,RESUME,DETACHED)

## 2. State Management (Most Asked)

* setState() – when to use & its limitations
* Provider basics (ChangeNotifier)
* GetX (state, navigation)
* Dependency Injection (DI)
* When to choose which state management?
* What is architecture and basics

## 3. Navigation & Routing

* Navigator.push/pop
* Named routes
* Passing data between screens (IMP)
* Deep linking (web, mobile)

## 4. Dart Language Interview Topics

* OOP concepts in Dart
* Mixins, extensions, abstract classes
* async/await, Future, Stream
* isolates & compute()
* Null safety (required, late, !, ?)
* What is const,final,static / Difference between them

## 5. UI & Layout

* Difference between:
    * Row vs Column
    * Expanded vs Flexible
    * SizedBox vs Container
* What is LayoutBuilder?
* MediaQuery for responsiveness
* CustomPainter basics
* Stateless performance vs Stateful performance
* All most used widgets
* Future builder & Stream builder

## 6. Networking & API Handling

* http vs dio packages
* JSON serialization:
    * manual parsing
* REST principles
* Handling API errors:
    * Timeout
    * Bad network
    * Retry logic
    * Authentication

## 7. Persistence & Storage

* SharedPreferences (key-value)
* SQLite (sqflite)
* Hive (NoSQL)
* Secure Storage (token storage)

## 8. Performance & Optimization

* How to reduce widget rebuilds
* Using const correctly
* RepaintBoundary
* Avoiding large widget trees
* Why and when to use keys?

## 9. Advanced Flutter Topics

* Platform channels (how Flutter communicates with native) (MOST-IMP)
    * Method Channel
    * Event Channel
    * Binary Messenger
* Slivers (CustomScrollView, SliverAppBar)
* Animations (Tween, AnimationController, Hero)
* Handling background tasks

## 10. Firebase Topics (Go through it only needed in advance level)

* Firebase Auth workflows (email, Google auth)
* Firestore read/write
* Offline sync
* Push notifications (FCM)
* Firebase storage for files

## Flutter Common Interview questions :

1. What is state
2. What are methods for state management
3. Do u know difference in Obx builder and GetBuilder
4. What is difference in Expanded & flutter can you give an example
5. What is Singleton class
6. How do use native functionality in flutter What is method channel
7. Do u know Event channel/ Basic Message Channel
8. Have you learned any local database
9. What is difference in shared pref and local db when to use
10. Explain the widget tree in Flutter.
11. What is the purpose of the build() method in Flutter?
12. What are keys in Flutter? When would you use them? (Types)
13. Explain life cycle method of statefull widget
14. Explain app state & Ephemeral state
15. Explain AppLifecycle states(Resumed,Inactive,Paused,Detached)
16. What are const,static,final keywords in Flutter?
17. What is the purpose of the build() method in Flutter?
18. What is context/Buildcontext
19. What is DI
20. What is factory constructor
21. what are null aware operators 
