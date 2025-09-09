# Node Cheatsheet

## NVM

### Installation

```zsh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
nvm --version
```

Optionally, add the following commands to your ~/.zshrc or ~/.bashrc file

```zsh
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
```

### Usage

1. Check required node version from app
2. List nvm available versions using `nvm list`
3. Cretae .nvmrc file in the root of the app/project and store the required node version
4. Run `nvm use`

### Usage

1. Check required node version from app
2. List nvm available versions using `nvm list`
3. Cretae .nvmrc file in the root of the app/project and store the required node version
4. Run `nvm use`

#### Install node packages

We can use Yarn or Bun package managers to install packages

##### YARN

```zsh
npm install --global yarn
yarn --version
```

##### BUN

```zsh
curl -fsSL https://bun.sh/install | bash
```

##### Usage

```zsh
yarn create slidev
```

```zsh
bun create slidev
```

