# List of virally unsound crates

Some crates promotes codes that aims at turning unsafe code
into unsound code.

Any crate that depends on the crates listed bellow are very likely to provide unsound
interface or to have undefined behavior.

The crates listed bellow and any of their dependencies (recursively) are best avoided.

Check the crate you maintain with `cargo tree | grep transmute` to see if it is infected.

## Unsoundness promoting crate list

  - [safe-transmute](https://crates.io/crates/safe-transmute) \[[dependents](https://crates.io/crates/safe-transmute/reverse_dependencies)\]
  - [safe_transmute2](https://crates.io/crates/safe_transmute_2) \[[dependents](https://crates.io/crates/safe_transmute_2/reverse_dependencies)\]
  - [totally-speedy-transmute](https://crates.io/crates/totally-speedy-transmute) \[[dependents](https://crates.io/crates/totally-speedy-transmute/reverse_dependencies)\]
  - [totally-safe-transmute](https://crates.io/crates/totally-safe-transmute) \[[dependents](https://crates.io/crates/totally-safe-transmute/reverse_dependencies)\]
