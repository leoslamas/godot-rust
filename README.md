# godot-rust
## Minimal Configuration to Start a Godot Project Using Rust

This repository provides a minimal configuration to kickstart a Godot project using Rust as the game scripting language, following the tutorial from [godot-rust/gdext](http://github.com/godot-rust/gdext). 

You can access the book through the following link: [Book](https://godot-rust.github.io/book/).

## Prerequisites

1. Make sure you have the Godot Engine installed.
2. Install Rust on your system if you haven't done so already.
3. Follow the instructions in the book to set up the environment and necessary dependencies.

## Project Structure

Here's an overview of the project structure:

```
godot-rust
│
├── .git/
│
├── godot/
│   ├── .godot/
│   ├── godot-rust.gdextension
│   ├── icon.svg
│   ├── main.tscn
│   └── project.godot
│
└── rust/
    ├── Cargo.toml
    ├── src/
    │   └── lib.rs
    └── target/
        └── debug/
```

## Building and Running

1. Build the Rust project using the following command:

   ```bash
   cargo build
   ```

2. Open the Godot Engine and load the project.
3. Run the game in Godot to ensure everything is working correctly.
