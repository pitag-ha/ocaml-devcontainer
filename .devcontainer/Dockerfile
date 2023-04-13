FROM ocaml/opam:debian

# Basic packages:
# dune - build system
# utop - nicer REPL
# ocaml-lsp-server - backend for VSCode OCaml extension
# ocamlformat - code formatter, used by ocaml-lsp-server
RUN opam install -y dune utop ocaml-lsp-server ocamlformat
