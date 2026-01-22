# supcik/homebrew-tap

A Homebrew tap for distributing macOS apps and tools.

## Prerequisites

- Homebrew installed on macOS: https://brew.sh

## Add the Tap

```bash
brew tap supcik/tap
```

## Install Packages

After tapping, install formulas or casks:

```bash
# Install a formula (CLI/tool)
brew install <formula-name>

# Install a cask (GUI app)
brew install --cask <cask-name>
```

## Install Without Tapping

You can also install directly without adding the tap first:

```bash
brew install supcik/tap/<formula-name>
brew install --cask supcik/tap/<cask-name>
```

## Discover Packages

List what's available or get details:

```bash
brew search supcik/tap
brew info supcik/tap/<name>
```

## Upgrade

Keep Homebrew and installed casks up to date:

```bash
brew update
brew upgrade <formula-name>
brew upgrade --cask <cask-name>
```

## Uninstall

Remove a cask:

```bash
brew uninstall <formula-name>
brew uninstall --cask <cask-name>
```

Remove the tap:

```bash
brew untap supcik/tap
```

## Troubleshooting

- If a package isn't found, run `brew update` and retry.
- Ensure the tap is present: `brew tap | grep supcik/tap`.
- Use `brew doctor` to diagnose common issues.
