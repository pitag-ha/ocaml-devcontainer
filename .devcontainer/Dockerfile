FROM buildpack-deps:bullseye-curl

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
  && apt-get -y install opam git build-essential curl unzip bubblewrap pkg-config

RUN opam init -y --disable-sandboxing
RUN opam install -y dune ocaml-lsp-server opam-monorepo ocamlformat.0.24.1 dune-release odoc mdx
