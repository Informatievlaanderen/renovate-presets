# Renovate Presets

This repository contains presets for [Renovate](https://renovate.whitesourcesoftware.com/) that can be used in Informatie Vlaanderen repositories. This configuration makes sure that major updates will always go through a pull request, while
other update will be automatically merged.

## Usage

To use it, create a `renovate.json` in the repository with the following contents:
```
{
    "extends" : [
        "github>informatievlaanderen/renovate-presets:presets"
    ]
}
```
