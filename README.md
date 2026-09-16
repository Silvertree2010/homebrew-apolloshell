# homebrew-apolloshell

Homebrew tap for [ApolloShell](https://github.com/Silvertree2010/ApolloShell), a Caelestia-inspired desktop shell for macOS 26 Tahoe.

```sh
brew trust --tap Silvertree2010/apolloshell
brew tap Silvertree2010/apolloshell
brew install apolloshell
```

Homebrew 7 loads formulae from third-party taps only after `brew trust`. On older Homebrew versions, skip that line.

The formula builds ApolloShell from source with the Command Line Tools and installs `ApolloShell.app` into the Homebrew prefix. `brew info apolloshell` explains how to link it into `~/Applications` and how to keep the Accessibility permission across upgrades.

Prefer a prebuilt app? Download the disk image from the [latest release](https://github.com/Silvertree2010/ApolloShell/releases/latest).

Issues belong in the [ApolloShell repository](https://github.com/Silvertree2010/ApolloShell/issues).
