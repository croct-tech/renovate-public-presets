<p align="center">
    <a href="https://croct.com">
        <img src="https://cdn.croct.io/brand/logo/repo-icon-green.svg" alt="Croct" height="80"/>
    </a>
    <br />
    <strong>Renovate Public Presets</strong>
    <br />
    Croct's public configuration presets for <a href="https://renovatebot.com">Renovate</a>.
</p>
<p align="center">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-lightgrey" />
    <br />
    <br />
    <a href="https://github.com/croct-tech/renovate-public-presets/releases">📦 Releases</a>
    ·
    <a href="https://github.com/croct-tech/renovate-public-presets/issues/new?assignees=&labels=bug&template=bug-report.md">🐞 Report Bug</a>
    ·
    <a href="https://github.com/croct-tech/renovate-public-presets/issues/new?assignees=&labels=enhancement&template=feature-request.md">✨ Request Feature</a>
</p>

## Usage

To use this preset, add a `renovate.json` file to the project's directory:

```json
{
  "extends": [
    "github>croct-tech/renovate-public-presets:language"
  ]
}
```

Replace the `language` placeholder with the project's language, i.e., `java`.

## Contributing

Contributions to the module are always welcome!

- Report any bugs or issues on the [issue tracker](https://github.com/croct-tech/renovate-public-presets/issues).
- For major changes, please [open an issue](https://github.com/croct-tech/renovate-public-presets/issues) first to discuss what you would like to change.
- Please make sure to update tests as appropriate.

If you cannot find the renovate docs on their website (it is there, just not easy to find), it is [here](https://docs.renovatebot.com/).

## Copyright Notice

Copyright © 2015-2022 Croct Limited, All Rights Reserved.

All information contained herein is, and remains the property of Croct Limited. The intellectual, design and technical concepts contained herein are proprietary to Croct Limited s and may be covered by U.S. and Foreign Patents, patents in process, and are protected by trade secret or copyright law. Dissemination of this information or reproduction of this material is strictly forbidden unless prior written permission is obtained from Croct Limited.

