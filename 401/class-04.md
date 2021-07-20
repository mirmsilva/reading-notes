# Day 4 Reading Notes
## Classes
- Classes are a reference type
- At run time when you declare a variable of a reference type, the variable contains null until you explicitly creat an instance of that class by using the **new** operator
- When an object is created enough memory is allocated for the heap for that specific object
- Types on the managed heap require overhead when they are being allocated and or reclaimed
- Classes are declared by using the **class** Keyword
- The name of the class follows the keyword
- A class defines a type of object but not the object itself
- Classes support inheritance
- Whn a class declares a base class, it inherits all the members of the base class **except** for constructors

## Constructors
- whenever a class or struct is created its constructor is called
- They may have multiple constructors that take different arguments. They allow the programmer to set default values, limit instatiation and write code that is easy to read
- Static constructors are parameterless, the compiler initializes static fields to their defualt

## Properties
- A property is a member that provides a flexible mechanism to read, write or compute the value os a private fields
- Properties enable a class to expose a public away of getting and setting values while hiding the implementation or verification code
- a value keyword is used to define the value being assigned by the set or init accessor

## Stack & Heap
- Stack is responsible for keeping track of what is executing in our code
- Heap is responsible for keeping track of our objects
- Think of heap as boxes stacked on top of each other, we keep track of what's going on in our application by stacking another box on top when we call a method
- The Stack is like a stack of shoe boxes were we have to take off the top box to get to the one underneath
- The Stack is self maintaining meaning it takes care of its own memory management
- The Heap has to worry about Garbage collection

## Garbage Collection
- the GC (Garbage Collector) serves as an automatic memory manager
- It manages the allocation and release of memory for an application
Benefits:
- Frees Developers from having to manually release memory
- Allocates objects on the managed heap efficiently
- Reclaims objects that are no longer being used, clears their memory and keeps the memory available for future allocation
- Provides memory safety by making sure that an object cannot use the content of another object

### Things I Want To Know More About:


### My Sources:
- https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/classes
- https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/constructors
- https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/properties
- https://www.c-sharpcorner.com/article/C-Sharp-heaping-vs-stacking-in-net-part-i/
- https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/fundamentals

[Back to Main](README.md)
