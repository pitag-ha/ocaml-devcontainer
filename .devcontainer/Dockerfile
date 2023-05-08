FROM ocaml/opam:debian

# Install dev tools via ocaml-platform installer
SHELL ["/bin/bash", "-ec"]
RUN bash < <(curl -sL https://github.com/tarides/ocaml-platform-installer/releases/latest/download/installer.sh)
RUN ocaml-platform

