# You can find the [thin-edge.io documentation here](https://thin-edge.github.io/thin-edge.io/html/).

# Thin Edge Documentation: Writer Guidelines

## How to generate the documentation
The documentation is generated using [`mdbook`](https://lib.rs/crates/mdbook).

To generate the documentation from [source](https://github.com/thin-edge/thin-edge.io/tree/main/docs/src),
you will have to run:
1) `cargo install mdbook mdbook-linkcheck mdbook-mermaid mdbook-admonish mdbook-cmdrun`
2) `git clone https://github.com/thin-edge/thin-edge.io`
3) `cd thin-edge.io/docs`
5) `mdbook serve`

The documentation is then published on `http://localhost:3000/`.

## Writing guide lines

This documentation is written along [the documentation system](https://documentation.divio.com/).


