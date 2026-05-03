# Qt 6 Builder

Build Qt 6 from source using GitHub Actions.

## Features

- Build Qt from official Qt sources
- Minimal modules for desktop shell use
- Ubuntu 24.04 LTS build environment
- Outputs compressed tar.gz artifact

## Modules Built

- qtbase
- qtdeclarative
- qtwayland
- qtsvg
- qttools
- qtshadertools

## Usage

1. Go to [Actions](https://github.com/krishnak2c/qt6-builder/actions)
2. Run workflow
3. Download from Releases

## Download

```bash
wget https://github.com/krishnak2c/qt6-builder/releases/download/latest/qt6.8.3-minimal.tar.gz
tar -xzf qt6.8.3-minimal.tar.gz -C ~/Qt/
```

## Qt Version

Default: 6.8.3 (latest stable open source)

## License

Qt is licensed under LGPL 3. See [Qt.io](https://qt.io/licensing).