# cargo run <...>

```rust
// fn main...
// cargo run pwd
let args: Vec<_> = std::env::args().collect();
if &args[1] == "pwd" {
    println!("pwd");
}
```