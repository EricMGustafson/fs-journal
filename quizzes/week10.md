# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
To keep classes and methods contained to the single 'namespace' and its classes.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A class is used for reference types and a struct is for value types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
'public'
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
It is a variable declaration so it expects the output of the Start() method to be a string.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The instantiation of itself
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Allows the class that inherits it to modify it.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, internal, protected, private
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It is only assessable from within the file that created it.
```