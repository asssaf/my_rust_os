FROM rustlang/rust:nightly

RUN cargo install cargo-xbuild
RUN rustup component add rust-src
RUN cargo install bootimage
RUN rustup component add llvm-tools-preview

RUN apt-get update
RUN apt-get install -y qemu-system-x86
