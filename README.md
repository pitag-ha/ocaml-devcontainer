# OCaml Dev Container

A template dev container for OCaml development, which is based on the latest stable versions of OCaml and Debian.
The current configuration supports:
- Editing code using [OCaml Platform VSCode extension](https://marketplace.visualstudio.com/items?itemName=ocamllabs.ocaml-platform)
- Package management using [opam](https://opam.ocaml.org)
- Building projects using [Dune](https://dune.build)
- Interactive REPL using [utop](https://opam.ocaml.org/blog/about-utop/)

## How to use it?

Dev Container is supported by [Visual Studio Code](https://code.visualstudio.com) and [GitHub Codespaces](https://github.com/features/codespaces).
Follow the steps below to setup an environment where you can work on your OCaml projects.

### VS Code
1. [Install Docker Desktop](https://www.docker.com/products/docker-desktop/)
2. [Install Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
3. Clone this repository.
4. Execute command `Dev Containers: Open Folder in Container...` and open previously cloned repository.
5. VS Code will run a Dev Container. This step may take time during the first execution because the container has to be built from scratch.

### GitHub Codespaces
Follow [Codespace quickstart guide](https://docs.github.com/en/codespaces/getting-started/quickstart)

## How to customize Dev Container?
Configuration is specified in files under `.devcontainer` directory, which can be edited to tailor Dev Container to your needs.

### `devcontainer.json`
Contains metadata and settings for Dev Container. [Specification](https://containers.dev/implementors/json_reference/)

### `Dockerfile`
Contains commands for building Dev Container docker image. [Specification](https://docs.docker.com/engine/reference/builder/)

## Creating your own Dev Container
This project can be used as a template for creating Dev Container for your own project. To do this, you need to copy `.devcontainer` directory into your project's root. It's a way to provide a shared dev environment for all contributors.

