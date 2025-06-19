# go-interfaces

This repository contains concise and focused examples demonstrating the use of **interfaces** in Go. Each example is placed in a separate folder and illustrates a specific concept.

---

## 📁 01. Interface Implementation

**Path:** `interface implementation/01.interface_implementation/main.go`

This example demonstrates:

- How concrete types implement interfaces.
- The difference between value and pointer receivers.
- Assigning values to interface variables.

### Key Concepts:
- `Abser` interface
- Struct `Vertex` and custom type `MyFloat`
- Pointer receiver vs value receiver behavior

## 📁 02. Geometry Interface & Type Assertion

**Path:** `geometry interface/01.geometry_type_assertion/main.go`

This example shows:

- Defining and implementing a `geometry` interface.
- Implementations for `rect` and `circle` types.
- Using **type assertions** to detect the underlying type at runtime.

### Key Concepts:
- Interface polymorphism
- Practical use of `type assertion`
- Struct-based interface design


## 🧠 Why These Examples Matter

Interfaces are one of Go’s most powerful features. These examples help to:

- Understand how interfaces enable abstraction and flexibility.
- See how method sets affect interface satisfaction.
- Learn how to inspect and extract concrete types from interface values.

---

## 🚀 Getting Started

Clone the repository and run each example:

```bash
go run path/to/example/main.go
```
## 📚 Resources & References

 This project is part of my learning path in understanding **interfaces in Go**. The examples are built upon key official resources and practical experimentation.

[YouTube URL](https://www.youtube.com/watch?v=qJKQZKGZgf0) — Video tutorial that explains in simple language how the interface works with interesting examples.

[YouTube URL](https://www.youtube.com/watch?v=lh_Uv2imp14) — Video tutorial with simple explanations of how interfaces work, using clear examples. Suitable for those who prefer a classic presentation of the material.

[Go.dev Blog - Effective Go](https://go.dev/doc/effective_go#interfaces) — The official website of the programming language is aimed at in-depth study of this topic with the smallest details.

[Go.dev A Tour of Go - Interfaces](https://go.dev/tour/methods/9) —   Introduction to interface types in Go as a set of method signatures.  
Shows how values implement interfaces through method sets. 

## 📝 License
This project is open-source and free to use for educational purposes.