# Identicon

A small Elixir command line utility that takes a string and creates an identicon based on that string. The output should always be identical, given the same input. An identicon is a grid of 5 x 5 squares, with each square 50 x 50 pixels, and the total grid is 250 x 250 pixels. The grids are colored according to the identicon algorithm, and each identicon is symmetrical along its vertical center axis.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).
