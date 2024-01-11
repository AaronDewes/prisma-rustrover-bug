# RustRover bug PoC

This is an example of a wrong warning in RustRover.

## Usage

Generate the client:

```bash
cargo prisma generate
```

Then open the `src/main.rs` file and see the warning in the `select!` macro.