<p align="center">
<a href="https://rust-starter.github.io"><img src="https://raw.githubusercontent.com/rust-starter/rust-starter.github.io/master/docs/images/logo_color.png" height="100px"/></a>
 </p>
<h1 align="center">rust-cli-starter</h1>
<div align="center">
 <strong>
    A simple starter to build a Rust CLI Application
 </strong>
</div>
<br/>

[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/omarabid/rust-starter/blob/master/LICENSE)  [![Gitter](https://badges.gitter.im/rust-starter/community.svg)](https://gitter.im/rust-starter/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
![tests](https://github.com/omarabid/rust-starter/workflows/tests/badge.svg)
![build](https://github.com/omarabid/rust-starter/workflows/build/badge.svg)
[![codecov](https://codecov.io/gh/rust-starter/rust-starter/branch/master/graph/badge.svg)](https://codecov.io/gh/rust-starter/rust-starter)

`rust-starter` is a starter boilerplate to create a Rust CLI application. It comes with a battery of components like argument parsing and configuration. It also has different tooling to create your binary, or automate your build process.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**
- [Getting started](#getting-started)
- [About](#about)
- [FAQ](#faq)
- [Features](#features)
- [Quick Bootstrapping](#quick-bootstrapping)
- [How to Contribute](#how-to-contribute)
  - [Versioning](#versioning)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Getting Started

1. Create a project by clicking the [Rust template](https://github.com/gitpod-io/rust-cli-starter/generate).

2. Install Gitpod's [GitHub App](https://github.com/apps/gitpod-io/installations/new) on your account.<br/>
The app will install a webook on your project to get informed when branches are pushed or updated. Gitpod will then prebuild your dev environments ahead of time, so noone has to wait for dependency installation and initialization anymore.

3. Run your first prebuild by prefixing https://gitpod.io#prebuild/ to the URL of the repository.<br/>
The revised URL is: `https://gitpod.io/#prebuild/https://github.com/<orgname>/<projectname>/`.<br/>
Gitpod displays the prebuild logs by running the init commands in the `.gitpod.yml` file and starts a first workspace based on the results afterwards. Later, when you create a new workspace on a branch, or pull/merge request, for which a prebuild exists, the workspace loads much faster, because all dependencies are already downloaded and the code is compiled. For more information, see prebuilds.

4. Enjoy being ready-to-code and share with your team 🚀

[![Gitpod ready-to-code](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/from-referrer/)

## About

`rust-starter` is an empty Rust CLI application with libraries, and few defaults. The goal is to help you bootstrap your next CLI project as quickly as possible while ensuring you make use of the best tools and best-practices that are available today.

There is no configuration required (though we recommend you check all the possible configurations possible). An empty clone will compile, and has a few sample commands. You can start coding right away!

## FAQ

For the Full FAQ, check the [website](https://rust-starter.github.io/#faq)

## Features

- [Clap](https://github.com/clap-rs/clap) for Command Line Argument parsing.
- Error Chaining with [Failure](https://github.com/rust-lang-nursery/failure).
- Configuration management with [config-rs](https://github.com/mehcode/config-rs).
- Multi-Drain, async Logging with [slog](https://github.com/slog-rs/slog).
- Static binaries with [rust-musl-builder](https://github.com/emk/rust-musl-builder).
- CI/CD through Github actions.
- Code Coverage, Justfile, etc..
- MIT License.

## Quick Bootstrapping

`rust-starter` should compile and run as is. You just need to clone the repository. A `cargo-generate` template is also [available](https://github.com/rust-starter/rust-starter-generate). For a more detailed introduction, check the [Getting Started](https://rust-starter.github.io/#getting-started) guide.

## How to Contribute

Details on how to contribute can be found in the [CONTRIBUTING.md](.github/CONTRIBUTING.md) file.

### Versioning

Rust Starter stricltly adheres to the [SemVer](https://semver.org/) Semantic Versioning.

## License

`rust-starter` is licensed under the MIT license. Please read the [LICENSE](LICENSE) file in this repository for more information.

