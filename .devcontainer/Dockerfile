FROM ocaml/opam:debian

RUN sudo apt-get update \
  && sudo apt-get -y install git curl unzip bubblewrap pkg-config

RUN opam install -y dune ocaml-lsp-server ocamlformat utop
