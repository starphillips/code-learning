Enums are for fixed values.

You can use an enum when you want a value in a struct to be fixed. 

Example: We define a enum and struct. The struct has an instance where we use the enum to provide the value of one of the params in the struct.

``` rust
enum IpAddrKind {
	V1(u8, u8, u8, u8),
	V2,
}

struct IpAddress {
	kind: IpAddrKind,
	address: String,
}

fn main() {
	let one = IpAddrKind:: V1,
	let two = IpAddrKind:: V2,
}

let localhost = IpAddress {
	kind: IpAddrKind::V4(127, 0, 0, 1),
	address: String::from("127.0.0.1")
};
```


over structs when they are fixed. If it can only be selected things, we go for enums. 

Struct would be 