# compute-float
![status](https://img.shields.io/badge/status-Active-brightgreen?style=flat-square)
[![crates.io](https://img.shields.io/crates/v/compute-float?style=flat-square)](https://crates.io/crates/compute-float)
[![Downloads](https://img.shields.io/crates/d/compute-float?style=flat-square)](https://crates.io/crates/compute-float)
[![Downloads (latest)](https://img.shields.io/crates/dv/compute-float?style=flat-square)](https://crates.io/crates/compute-float)
[![License](https://img.shields.io/crates/l/compute-float?style=flat-square)](https://github.com/watcol/compute-float/blob/main/LICENSE)
![Lint](https://img.shields.io/github/workflow/status/watcol/compute-float/Lint?label=lint&style=flat-square)
![Test](https://img.shields.io/github/workflow/status/watcol/compute-float/Test?label=test&style=flat-square)

Computes floating point numbers using eisel-lemire algorithm.

## Usage
Add to your `Cargo.toml`:
```toml
[dependencies]
compute-float = "0.1.0"
```

If you are in the `no_std` environment:
```toml
[dependencies.compute-float]
version = "0.1.0"
features = ["no-std"]
```

## Documentation
API Documentations are available on [here](https://docs.rs/compute-float).

## Reference implementations
- [strconv (Go)](https://github.com/golang/go/blob/master/src/strconv/eisel_lemire.go)
- [Rust standard library](https://doc.rust-lang.org/stable/src/core/num/dec2flt/lemire.rs.html)

## License
This program is licensed under the MIT license.
See [LICENSE](https://github.com/watcol/compute-float/blob/main/LICENSE) for details.
