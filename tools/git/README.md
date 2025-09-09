# Git Cheatsheet

## Repository Access

```zsh
git clone <https|git://...git>
```

## Development Cycle

### Pull Requests (GitHub)

```zsh
git status
# be sure to start from main branch
git fetch <repo-name> <repo-branch-name>
git pull <repo-name> <repo-branch-name>

git checkout -b features/<identificador-nombre-descriptivo>
```

```zsh
git add .
git commit -m '<pref>: <descripcion de cambios>'
# <pref>: <feat|doc:test:chore>
```

```zsh
git fetch <repo-name> features/<identificador-nombre-descriptivo>
git pull <repo-name> features/<identificador-nombre-descriptivo>
# if no conflicts, push
git push <repo-name> features/<identificador-nombre-descriptivo>
```

```zsh
gh pr create --fill --web
```

## Branch Management

### Switch between branches

```zsh
git checkout <branch-name>
```

### Get the repository name

```zsh
git remote -v
```
