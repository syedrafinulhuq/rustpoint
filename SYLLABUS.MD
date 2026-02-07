# RUST syllabus

## 1. Setup & Tooling

* Installing Rust (rustup)
* Rust toolchain (stable, beta, nightly)
* Cargo (build system & package manager)
* Project structure
* rustfmt
* clippy
* Documentation (rustdoc)
* IDE / Editor setup (VS Code, rust-analyzer)

---

## 2. Basic Language Syntax

* `fn` and function definitions
* `let` bindings
* Mutability (`mut`)
* Shadowing
* Comments
* Whitespace & formatting rules
* Keywords

---

## 3. Primitive Data Types

* Integer types (`i8`–`i128`, `u8`–`u128`, `isize`, `usize`)
* Floating point types (`f32`, `f64`)
* Boolean (`bool`)
* Character (`char`)
* Unit type (`()`)

---

## 4. Variables, Scope & Lifetime Basics

* Variable scope
* Block expressions
* Statement vs expression
* Stack vs heap (conceptual)
* Ownership scope rules

---

## 5. Control Flow

* `if`, `else if`, `else`
* `loop`
* `while`
* `for`
* `break` and `continue`
* Labels in loops
* `match` (basic)

---

## 6. Ownership System (Core Rust)

* Ownership rules
* Move semantics
* Copy types
* Drop behavior
* Shallow vs deep copy

---

## 7. Borrowing & References

* Immutable references (`&T`)
* Mutable references (`&mut T`)
* Borrowing rules
* Reference scope
* Dangling references (compile-time prevention)

---

## 8. Lifetimes (Foundational)

* Lifetime concept
* Lifetime annotations
* Lifetime elision rules
* Lifetimes in functions
* Lifetimes in structs
* `'static` lifetime

---

## 9. Compound Data Types

* Tuples
* Arrays
* Slices
* Strings vs string literals
* `String` vs `&str`

---

## 10. Structs

* Struct definition
* Tuple structs
* Unit structs
* Field access
* Struct update syntax
* Ownership in structs
* Methods (`impl`)
* Associated functions

---

## 11. Enums

* Enum definition
* Enum variants
* Enums with data
* `match` with enums
* `if let`
* `while let`

---

## 12. Pattern Matching

* Match patterns
* Destructuring
* `_` wildcard
* Guards
* Binding with `@`

---

## 13. Error Handling

* `panic!`
* `Result<T, E>`
* `Option<T>`
* `unwrap`, `expect`
* `?` operator
* Custom error types
* Error propagation
* `thiserror` (later)
* `anyhow` (later)

---

## 14. Collections (Standard Library)

* `Vec<T>`
* `HashMap<K, V>`
* `HashSet<T>`
* `VecDeque<T>`
* Iteration over collections
* Ownership in collections

---

## 15. Modules & Crates

* Module system
* `mod`
* `pub`
* `use`
* Crate structure
* Library crate vs binary crate
* `Cargo.toml`
* Dependencies
* Workspaces (intro)

---

## 16. Traits

* Defining traits
* Implementing traits
* Trait bounds
* `impl Trait`
* Default implementations
* Trait objects (`dyn`)
* Static vs dynamic dispatch

---

## 17. Generics

* Generic functions
* Generic structs
* Generic enums
* Trait bounds on generics
* Where clauses
* Monomorphization (concept)

---

## 18. Iterators & Closures

* Closures (`||`)
* Closure capture rules
* `Fn`, `FnMut`, `FnOnce`
* Iterator trait
* `map`, `filter`, `fold`
* Lazy evaluation
* Custom iterators

---

## 19. Smart Pointers

* `Box<T>`
* `Rc<T>`
* `Arc<T>`
* `RefCell<T>`
* Interior mutability
* `Cell<T>`
* Reference cycles (intro)

---

## 20. Memory Management Concepts

* Stack vs heap in Rust
* RAII
* Drop trait
* Deterministic destruction
* Zero-cost abstractions (conceptual)

---

## 21. Concurrency Basics

* Threads (`std::thread`)
* Message passing (`mpsc`)
* Mutex
* RwLock
* Atomic types
* `Send` and `Sync`
* Data races (compile-time guarantees)

---

## 22. Async Rust (Intro)

* `async` / `await`
* Futures
* Async runtimes (Tokio overview)
* Async functions
* Async error handling
* Blocking vs non-blocking

---

## 23. File I/O & OS Interaction

* Reading files
* Writing files
* Paths (`Path`, `PathBuf`)
* Environment variables
* Command line arguments
* `std::fs`
* `std::env`

---

## 24. Testing

* Unit tests
* Integration tests
* `#[test]`
* `assert!`, `assert_eq!`
* Test modules
* Ignored tests
* Benchmarking (intro)

---

## 25. Documentation & Style

* Doc comments (`///`)
* Markdown in docs
* Examples in docs
* Public API design
* Rust API guidelines (awareness)

---

## 26. Unsafe Rust (Awareness Level)

* `unsafe` keyword
* Raw pointers
* Unsafe functions
* Unsafe traits
* Why unsafe exists
* When to avoid unsafe

---

## 27. Build, Release & Distribution

* Debug vs release builds
* Cargo profiles
* Feature flags
* Versioning
* Publishing crates
* SemVer basics

---

## 28. Ecosystem Awareness (Not Mastery)

* crates.io
* docs.rs
* Popular crates (serde, tokio, reqwest)
* FFI overview (C/C++ interop)

---
