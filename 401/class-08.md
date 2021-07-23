# Day 8 Reading Notes
## Collections
- Collections provide a more flexible way to work with groups of objects. Unlike arrays, the group of objects may grow and shrink dynamically as needed
- A collection is a class the must be declared before you add elements
- If your collection contains elements of only one data tyoe, you can use one of the classes in the System.Collections.Generic namespace to enforce type safety
- You can iterate through a List

### System.Collections.Generic,Classes

**Dictionary<TKey,TValue>**	Represents a collection of key/value pairs that are organized based on the key.

**List<T>**	Represents a list of objects that can be accessed by index. Provides methods to search, sort, and modify lists.
  
**Queue<T>**	Represents a first in, first out (FIFO) collection of objects.
  
**SortedList<TKey,TValue>**	Represents a collection of key/value pairs that are sorted by key based on the associated IComparer<T> implementation.
  
**Stack<T>**	Represents a last in, first out (LIFO) collection of objects.
  
### Custom Collections
- You can define a collection by implementing the IEnumerable<T> or IEnumerable interface
- The IEnumerable interface requires that the GetEnumerator method be implemented
  
## Enumeration Types
- A value type defined by a set of named constants of the underlying intergral numeric type
- To define an enumeration type, use the enum keyword & specify the names of the enum members
- By default the constant values of enum members are type of int & start with 0
  
### Things I Want To Know More About:


### My Sources:
-https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/collections

[Back to Main](README.md)
