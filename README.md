<div align="center">
    <h1>ThesChain</h1>
    <h3>An Interactive Offline Thesaurus CLI Tool</h3>
    <h2>⮎ <kbd>Search</kbd> › <kbd>Select</kbd> › <kbd>Repeat</kbd> ⮌ </h2>
    <h3>forming a continuous chain of lookups</h3>
    <img src="./demo.gif" alt="demo" width="90%" />
    <h6>built on <a href="https://github.com/grantshandy/thes">github.com/grantshandy/thes</a></h6>
</div>

## Requirements

- [github.com/grantshandy/thes](https://github.com/grantshandy/thes)
- [github.com/charmbracelet/gum](https://github.com/charmbracelet/gum)

### Thes

```bash
# Native
cargo install thes

# Arch Linux (btw)
yay -S thes-git
```

### Gum

```bash
# Gum

# macOS or Linux
brew install gum

# Arch Linux (btw)
pacman -S gum

# Nix
nix-env -iA nixpkgs.gum

# Flox
flox install gum

# Windows (via WinGet or Scoop)
winget install charmbracelet.gum
scoop install charm-gum
```

## Installation

```bash
# Clone the repo
git clone git@github.com:metaory/theschain.git

# Navigate to repo
cd theschain

# Give execution permissions
chmod +x theschain

# Link it somewhere in your PATH
ln -svf $PWD/theschain /usr/bin/theschain

# Use it anywhere
theschain void
```

## License

[GNU GPLv3](LICENSE)

