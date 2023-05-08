# [Choice] OCaml version: 4.02, 4.03, 4.04, 4.05, 4.06, 4.07, 4.08, 4.09, 4.10, 4.11, 4.12, 4.13. 4.14, 5.0, 5.1, 5.2
ARG VERSION=5.0
FROM ocaml/opam:debian-ocaml-${VERSION}

# Install dev tools via ocaml-platform installer
SHELL ["/bin/bash", "-ec"]
RUN bash < <(curl -sL https://github.com/tarides/ocaml-platform-installer/releases/latest/download/installer.sh)
RUN ocaml-platform

