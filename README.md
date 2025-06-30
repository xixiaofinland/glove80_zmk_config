# My Glove80 Keyboard Key Mapping

## Build by Github Action

Check `build.yml` in the repo.

## Build locally by Nix

```
git clone https://github.com/moergo-sc/zmk.git src
nix-build config -o combined
```

The glove80.uf2 is located in the `combined` folder
