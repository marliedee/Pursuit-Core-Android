# Classes and Objects
## Inheritance

---

## What you should know by now...
- How to print out using `System.out.println`.
- How to use primitive types, e.g. `int`, `char`, `boolean`, etc.
- How to use `String`s.
- How to read user input with `Scanner`.
- How to use `while` loops.
- How to use an `if` statement.
- How to use `for` loops
- How to create a `class` with `methods`
- How to instantiate a `class` and call its `methods`

---

## Warm Up Exercise

* Create a `Food` class with the fields `name`, `type` that are strings;
* Add three boolean fields `isEdible`, `isRipe` and `isSpicy`
* Add the method `getRegion()` that returns a `string` that represents food's origin
* Add the method `getIngredients()` that returns an array of strings that represents the ingredients used

---

## The `extend` Keyword

```
class A {
    String name;
    String getName() { 
        return name;
    }
}

====

class B extends A {
    String moreString;
}
```

Copies all the fields and methods in A into B (in the background)

---

## The `extend` Keyword contd.

Here is what B looks like (in the background)

```
class B(+A) {
    String name;
    String moreString;
    String getName() { 
        return name;
    }
}
```
???

Analogy: A child and its parents.
- same surname
- same genes in addition to his own genes
- impossible for father to inherit disease from child

---

* `extend` creates `super` and `base` classes.
* 

---

## The `abstract` keyword in `methods`

Used to defer the implementation of method to sub-classes.
Can be used to enforce *behavioral* rules in a hierachy of classes.

* An abstract method has only a signature and no body
* It is meant to be `@overriden` in sub-classes

---

## The `abstract` keyword in `classes`

* An abstract class may have methods that do not have a body
* An abstract class has to be sub-classed, at some level, to a non-abstract class before you can instantiate an object
* It is not legal to directly instantiate an object of an abstract class

---

## The School Letter Head

* It contains school logo, name, address and maybe a format
* All *official* letters issued from the school must have it
* The *body* of the letterhead is empty and *sender* gets to fill it
* *Anybody* can fill in the bod

see https://cseducators.stackexchange.com/a/525

---

# The `override` annotation

---

# The `static` modifier

---

# More on `super`, `instanceof`

---

# Enums

---

# Exam Review

---