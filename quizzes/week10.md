# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The purpose of a namespace is to organize code and prevent naming conflicts.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A class is a reference type and a struct is a value type.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
I believe it is the constructor.
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
The access modifier is public.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
What is going to be returned.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
abstract is preventing the class from being instantiated. So you have to inherit from it.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
virtual is allowing the method to be overridden.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
the four access modifiers are public, private, protected, and internal.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It can only be accessed by the class it is in.
```