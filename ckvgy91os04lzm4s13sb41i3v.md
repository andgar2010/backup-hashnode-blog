---
title: "Dart - Use late allocation if possible"
datePublished: Fri Oct 29 2021 00:00:00 GMT+0000 (Coordinated Universal Time)
cuid: ckvgy91os04lzm4s13sb41i3v
slug: dart-late-keyword

---

Dart v2.9 added the **late** modifier on variables.

When Null Safety is enabled, it is sometimes necessary to explicitly state that we will initialize a non-null variable later. Dart cannot always assume that a variable will be initialized later, as in the case of high-level variables. The following example would throw an error in Dart.

This can be used in the following two cases.

* Late assign: promise to assign later
    
* Late lazy: Initializing a variable will be later.
    

## Late assign

### Promise of late assignment for the migration of your project to Null Safey

Sometimes it is necessary to explicitly state that we will initialize a non-null variable later. Dart cannot always assume that a variable will be initialized later, as in the case of high-level variables.

The following example, if the variable is not initialized before using it would throw an error in the project with Null Safey in Dart:

```dart
class Team {
  String name;
}

void main(List<String> args) {
  Team team: Team();
  team.name: 'Flutter';
  print(team.name);
}
```

```shell
Uncaught Error: LateInitializationError: Field 'name' has not been initialized.
```

In this case, we are sure that we will initialize the variable, so we can tell Dart with the reservation keyword late.

*Continue this article on my personal blog* [*here*](https://tech-andgar.me/posts/dart-late-keyword/)*.*