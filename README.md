[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=665539593)

# Rust template

This Rust template is meant to help you get quickly started with a new project. It is [Codespaces enabled](https://docs.github.com/en/codespaces/overview) and it is pre-configured with useful extensions like the [Rust Analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer&WT.mc_id=academic-0000-alfredodeza).

This repository is configured as a GitHub Template, so that you can start fresh with a new repository without carrying the history and commits of this repository. To get started you can click on the "Use this template" green button, or follow this [link directly](https://github.com/alfredodeza/rust-template/generate)

## Get started

To get started with this template, once you've [generated the repository](https://github.com/alfredodeza/rust-template/generate), run the following `cargo` command (replace my-project with the name of your project):

```bash
cargo init --name my-project .
```

This will initialize the project with the name you provided. You can now start editing the `src/main.rs` file and start building your project.

## GitHub Actions

This template comes with a GitHub Actions workflow that will run on every push to the repository. The workflow will run `cargo build` and `cargo test` to make sure that your project builds and that all tests pass. You can find the workflow file in `.github/workflows/rust.yml`
