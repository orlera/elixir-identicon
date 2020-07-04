# Identicon

Simple Github-like identicon generator.
It generates a 250x250 monocromatic image given a string as input.


## Installation

This implementation relies on Erlang's `egd` for image plotting. You'll need to install `rebar` for it to work:
```
mix local.rebar --force
mix deps.get
```

## Run
From the `iex` console (`iex -S mix`):
```
Identicon.generate("orlera")
```

Will generate an image `identicons/orlera.png` based on the input string.
