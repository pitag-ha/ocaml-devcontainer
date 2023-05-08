# [Choice] OCaml version: 4.02, 4.03, 4.04, 4.05, 4.06, 4.07, 4.08, 4.09, 4.10, 4.11, 4.12, 4.13. 4.14, 5.0, 5.1, 5.2
ARG VERSION=5.0
FROM ocaml/opam:debian-ocaml-${VERSION}

# Basic packages:
# dune - build system
# utop - nicer REPL
# ocaml-lsp-server - backend for VSCode OCaml extension
# ocamlformat - code formatter, used by ocaml-lsp-server
RUN opam install -y dune utop ocaml-lsp-server ocamlformat
