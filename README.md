# renovate

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit)](https://github.com/pre-commit/pre-commit)
[![renovate](https://img.shields.io/badge/enabled-brightgreen?logo=renovatebot&logoColor=%2373afae&label=renovate)](https://developer.mend.io/)

Renovate presets.

## Usage

1. Create a `renovate.json` file (e.g. [`.github/renovate.json`](./.github/renovate.json)) file in a project with the following:

   ```json
   {
       "$schema": "https://docs.renovatebot.com/renovate-schema.json",
       "extends": [
           "github>finleyfamily/renovate"
       ]
   }
   ```

1. **(optional)** Add presets from this repo that are not included in the default preset.
   See the files in [`presets/`](./presets/) for available presets.
