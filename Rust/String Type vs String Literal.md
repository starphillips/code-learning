
**String Literal**
Text written in code.

`let s = "string"`

This is fixed in size. It is stored as a binary.
This can be stored on the stack.
Immutable.

**String Type**
`let s = String::from("string")`

This is mutable. This can be stored on the heap.

When we declare a string type. Rust automatically declares memory on the heap for it. 

When scope is invalidates, Rust will automatically deallocate the memory on the heap for s. 



