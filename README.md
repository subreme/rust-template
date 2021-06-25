# {{project-name}}

[![Template](https://img.shields.io/badge/Template-subreme%2Frust--template-orange)](https://github.com/subreme/rust-template/)
[![License](https://img.shields.io/badge/License-MIT%2FApache--2.0-green)](https://github.com/{{username}}/{{project-name}}/#license)
[![Release](https://img.shields.io/github/v/release/{{username}}/{{project-name}}?label=Release&color=blue&sort=semver)](https://github.com/{{username}}/{{project-name}}/releases/latest/)

## Introduction

This is a project template intended to be used with the `cargo generate` command
to simplify the process of publishing a repository written in
[Rust](https://www.rust-lang.org/).

## Installation

There are two main ways to install `{{project-name}}`, as explained below:

### Cargo

The project can be installed using Cargo through the following steps:

* Install the Rust toolchain using the [official
  guide](https://www.rust-lang.org/tools/install).
* Run `cargo install --git https://github.com/{{username}}/{{project-name}}
  --branch main`

### Releases

Alternatively, the compiled binaries can be found in the [Releases
page](https://github.com/{{username}}/{{project-name}}/releases/latest).

## Usage

### Generation

Assuming you have [Cargo installed](#cargo), the simplest way to use the
template is to use the following command:

```console
cargo generate --git https://github.com/subreme/rust-template
```

### Customization

Once the first command is run, a prompt will appear asking for the project's
name. Once a name is selected, all placeholders in the project's files, outlined
by double curly brackets, will be automatically replaced by their
corresponding values.

## License

Licensed under either of

* Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  <http://www.apache.org/licenses/LICENSE-2.0>)
* MIT license ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

See [CONTRIBUTING.md](CONTRIBUTING.md).
