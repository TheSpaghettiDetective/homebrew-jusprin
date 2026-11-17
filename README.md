# JusPrin for Homebrew

This is the [Homebrew](https://brew.sh) tap for [JusPrin](https://github.com/TheSpaghettiDetective/JusPrin), the AI-assisted slicer for 3D printers, on macOS.

## Install

```bash
brew install --cask thespaghettidetective/jusprin/jusprin
```

If you already installed JusPrin from the disk image, Homebrew stops with "It seems there is already an App at '/Applications/JusPrin.app'". When the installed copy is the same version, add `--adopt` and Homebrew takes it over:

```bash
brew install --cask --adopt thespaghettidetective/jusprin/jusprin
```

When it is an older version, move `/Applications/JusPrin.app` to the Trash first. Your projects and settings are kept.

## Update

```bash
brew upgrade --cask jusprin
```

## Uninstall

```bash
brew uninstall --cask jusprin
```

To also delete JusPrin's settings, projects and caches, use `brew uninstall --cask --zap jusprin`.

## Problems

Report problems with JusPrin itself at [TheSpaghettiDetective/JusPrin](https://github.com/TheSpaghettiDetective/JusPrin/issues), and problems with installing through Homebrew in this repository's issues.
