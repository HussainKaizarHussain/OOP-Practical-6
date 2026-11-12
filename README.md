# OOP-Practical-6: Runtime Polymorphism and Abstract Classes

## Purpose & Aim
- **Aim**: To demonstrate how a base-class interface can be used to call the correct derived-class function at runtime[cite: 1].
- **Question**: Create an abstract Shape class and implement Circle, Rectangle and Triangle with an area() function[cite: 1].

---

## What to Do
- Declare a Shape base class with a pure virtual area() function and a virtual destructor[cite: 1].
- Derive Circle, Rectangle and Triangle from Shape and implement area() for each shape[cite: 1].
- Store or refer to the derived objects through Shape pointers or references[cite: 1].
- Call area() through the base-class interface and display each calculated area[cite: 1].
- Use valid dimensions and explain why Shape itself cannot be instantiated when it is abstract[cite: 1].
