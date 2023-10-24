## Automated Rust Releases

This repository contains the configuration files for fully automating Rust releases via utilizing the following tools:

| **Tool**                                               | **Description**                                 | **Function**                                                           |
| ------------------------------------------------------ | ----------------------------------------------- | ---------------------------------------------------------------------- |
| [`git-cliff`](https://git-cliff.org)                   | A highly customizable Changelog Generator.      | Automates the changelog generation.                                    |
| [`release-plz`](https://release-plz.ieni.dev)          | Publish Rust crates from CI with a Release PR.  | Handles dependency updates, version management, and crates.io release. |
| [`cargo-dist`](https://opensource.axo.dev/cargo-dist/) | Shippable application packaging for Rust.       | Creates GitHub releases and packaging for various platforms.           |
| [`Dependabot`](https://github.com/dependabot)          | Automated dependency updates built into GitHub. | Updates the Rust and GitHub Actions dependencies.                      |
| [`Mergify`](https://mergify.com/)                      | Automated CI/CD tool for optimization.          | Automatically merges the `Dependabot` pull requests.                   |

For more information, read the blog post: <https://blog.orhun.dev/automated-rust-releases>
