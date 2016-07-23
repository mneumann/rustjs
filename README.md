# rustjs
Experiment with compiling a subset of the Rust language to Javascript

## Difficulties

* Rust uses no GC, while objects in Javascript are GCed.

## Examples

Rust:

```rust
let mut sum: i32 = 0;
for i in 1..10 {
  sum += i;
}
```

Javascript:

```javascript
let sum = 0;
for (let i = 1; i <= 10; i++) {
  sum += i;
}
```
