FROM rust:latest

RUN apt-get update && apt-get install -y pkg-config libssl-dev perl make \
  && cargo install dioxus-cli --locked && rustup target add wasm32-unknown-unknown
