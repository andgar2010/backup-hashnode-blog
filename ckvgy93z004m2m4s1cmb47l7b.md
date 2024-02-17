---
title: "Dart - En lo posible utilice la asignación tardía"
datePublished: Fri Oct 29 2021 00:00:00 GMT+0000 (Coordinated Universal Time)
cuid: ckvgy93z004m2m4s1cmb47l7b
slug: dart-late-keyword-1

---

Dart v2.9 añadió el modificador **late** en las variables.

Cuando Null Safety está activado, en algunas ocasiones es necesario indicar explícitamente que inicializaremos una variable no nula posteriormente. Dart no siempre puede asumir que una variable será inicializada más adelante, como en el caso de las variables de alto nivel. El siguiente ejemplo arrojaría un error en Dart.

Esto puede ser usado en los siguientes dos casos.

* Late assign: promesa de asignación más tarde
    
* Late lazy: Inicializando una variable será más adelante
    

## Late assign

### Promesa de asignación tardía para en la migración de su proyecto a Null Safey (seguridad de nulos)

Algunas ocasiones es necesario indicar explícitamente que inicializaremos una variable no nula posteriormente. Dart no siempre puede asumir que una variable será inicializada más adelante, como en el caso de las variables de alto nivel.

El siguiente ejemplo, Si la variable no es inicializada antes de utilizarla arrojaría un error en el proyecto con Null Safey en Dart:

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

En este caso, estamos seguros de que inicializaremos la variable, por lo cual podemos indicárselo a Dart con la palabra reserva late.

*Continúe este artículo en mi blog personal* [*aquí*](https://tech-andgar.me/es/posts/dart-late-keyword/)*.*