# cspell-cesium

[cSpell](https://cspell.org) library for the [Cesium programming language](https://cesiumlang.org)

## Usage

It is recommended to add this repo as a submodule to your existing project:

```bash
git submodule add https://github.com/cesiumlang/cspell-cesium.git .cspell/cesium
```

Then, ensure you import the config file in your existing project `.cspell.json` or equivalent file:

```json
{
    "version": "0.2",
    "import": [
        ".cspell/cesium/cspell-ext.json"
    ]
}
```
