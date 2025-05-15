<div align="center">
    <h1>thesi</h1>
    <h4>An Interactive Offline Thesaurus CLI Tool</h4>
    <h3>Chase Synonyms!</h3>
    <img src="./demo.gif" alt="demo" width="90%" />
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
git clone git@github.com:metaory/thesi.git

# Navigate to repo
cd thesi

# Give execution permissions
chmod +x thesi

# Link it somewhere in your PATH
ln -svf $PWD/thesi /usr/bin/thesi

# Use it anywhere
thesi void
```

