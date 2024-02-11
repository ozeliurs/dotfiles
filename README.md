# ChezMoi dotfiles manager

## Quick Installation

```sh
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply ozeliurs
```

## Routine Usage

### Adding a file
```sh
chezmoi add .bashrc
```

### Editing a file
```sh
chezmoi edit .bashrc
```

### Pushing changes
```sh
chezmoi cd
git add .
git commit -m "Add .bashrc"
git push
```

### Pulling changes
```sh
chezmoi update
```
