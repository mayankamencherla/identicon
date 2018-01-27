# Identicon

This module creates an identicon image for a given input string. The resultant identicon has a one-to-one mapping with the input string. 

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

## Example uses

Simply use `Identicon.main("any random string here")` to be able to make the identicon for the string `"any random string here"`.