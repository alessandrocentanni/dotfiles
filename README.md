Manage your dotfiles across multiple diverse machines, securely.
chezmoi's documentation is at [chezmoi.io](https://chezmoi.io/).

## Useful commands (what you'll mostly use)

```sh
chezmoi add ~/.bashrc # Add a file to the source state
chezmoi apply # Apply the source state to the destination directory
chezmoi diff # Show the difference between the source state and the destination directory
chezmoi re-add # Re-add a file to the source state, if you've edited the file locally and you want to keep it in sync
```
