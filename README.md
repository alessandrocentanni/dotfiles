Manage your dotfiles across multiple diverse machines, securely.
chezmoi's documentation is at [chezmoi.io](https://chezmoi.io/).

## Setup a new machine (supposing that you have already installed brew)

```sh
brew install chezmoi

chezmoi init --apply git@github.com:$GITHUB_USERNAME/dotfiles.git
```

## Useful commands (what you'll mostly use)

```sh
# Add a file to the source state
chezmoi add ~/.bashrc

# Apply the source state to the destination directory
chezmoi apply

# Show the difference between the source state and the destination directory
chezmoi diff

# Re-add a file to the source state, if you've edited the file locally and you want to keep it in sync
chezmoi re-add
```

## Generate a brew dump

```sh
brew bundle dump

# optionally you can specify the output path
brew bundle dump --file=~/dotfiles/brew/Brewfile
```
