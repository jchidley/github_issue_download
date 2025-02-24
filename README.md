# rust_template

include this in `~/.cargo/config.toml`

```
[build]
rustflags = ["-C", "link-arg=-fuse-ld=mold","-C", "target-cpu=native"]
```

Consider adding a `Cargo.toml` in the examples directory.
