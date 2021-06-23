# List of virally unsound crates

Some crates proudly promote code that aims at turning unsafe code
into unsound code.

Any crate that depends on the crates listed bellow are very likely to provide unsound
interface or to have undefined behavior.

Those crates and any of their dependencies (recursively) are best avoided.

You can verify if your crate is infected by running `cargo tree | grep transmute` to see if it depends
on those crates.

There are probably more crates that expose such an indecent behavior. If you find one, call the
911 or add them to the list bellow.

## Unsoundness promoting crate list

  - [safe-transmute](https://crates.io/crates/safe-transmute) \[[dependents](https://crates.io/crates/safe-transmute/reverse_dependencies)\]
  - [safe_transmute_2](https://crates.io/crates/safe_transmute_2) \[[dependents](https://crates.io/crates/safe_transmute_2/reverse_dependencies)\]
  - [totally-speedy-transmute](https://crates.io/crates/totally-speedy-transmute) \[[dependents](https://crates.io/crates/totally-speedy-transmute/reverse_dependencies)\]
  - [totally-safe-transmute](https://crates.io/crates/totally-safe-transmute) \[[dependents](https://crates.io/crates/totally-safe-transmute/reverse_dependencies)\]
