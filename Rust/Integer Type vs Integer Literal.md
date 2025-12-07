
**Integer Literal**
Raw number. Literal integer written in code. No type may be defined.

(Defaulted to i32)

The complier can decide which type it belongs to


**Integer Type**
The rules that govern how the integer can be stored and used.

They can be signed or unsigned, but the type is defined on creation. 

**Signed:** can be negative or positive
**Unsigned:** can only be positive
![[integer-types-rust.png]]

What can be an integer type?
![[integers-rust.png]]
u8 can only hold a maximum of 255
If it exceeds it will wrap around to the minimum values e.g. 256 = 0, 257 = 1


#### Summary

Literals can be used directly in expressions:
``` rust
let sum = 5 + 10;  // both are literals, result is i32
```

Once assigned, they become values of a specific type:
``` rust
let a: u8 = 5;     // literal 5 coerced into type u8
let b = 5u64;      // literal 5 explicitly typed as u64
let c = a + 1;     // works fine, c is u8
```
Types are **fixed** once chosen — you can’t mix them without explicit conversion
``` rust
let a: u8 = 5;
let b: u32 = 10;
let c = a + b; // error: mismatched types
let c = (a as u32) + b; // explicit conversion
```

