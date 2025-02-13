# Data Race in Rust with Mutable References

This repository demonstrates a potential data race scenario in Rust when using mutable references.  Improper handling of mutable borrows can lead to unexpected behavior and program crashes.

The `bug.rs` file shows the buggy code. The `bugSolution.rs` file provides a solution demonstrating correct usage of mutable references.