
Workspace hold interrelated packages inside the space.

Package stores crate

Binary crate - code you can execute
library crate - cod used by other programmes

Creates contain modules that allow you to organise a chunk of code and control the privacy rules


Library crates that contains authentication module. You can make authentication module private but expose one public login method

if you want code outside of the authentication module in order to call the public login it would have to specify a path to that login method



If you have main.rs in n the root of your `src` directory then a binary crate with the same name as your package will be automatically created and main.rs will be the route

If `lib.rs` is in the root of your `src` directory then a library crate will be created and lib.rs will be the create route

Package rules:
- must have at least one crate
- must have 0 or 1 library crate
- any number of binary crates