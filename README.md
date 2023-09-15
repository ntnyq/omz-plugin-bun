# omz-plugin-bun

oh-my-zsh aliases for common [bun](https://bun.sh) commands.

## Installation

- [Oh My Zsh](#oh-my-zsh)
- [Zinit](#zinit)

### Oh My Zsh

1. Clone the repository:

```zsh
git clone --depth=1 https://github.com/ntnyq/omz-plugin-bun.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/plugins/bun
```

2. Include it in your `~/.zshrc`:

```zsh
plugins=(... bun)
```

### Zinit

Add script bellow to your `~/.zshrc`

```shell
zinit light ntnyq/omz-plugin-bun
```

### Others

PRs are always welcome!

## Aliases

| Alias | Command                   | Description                                                 |
| ----- | ------------------------- | ----------------------------------------------------------- |
| b     | `bun`                     | The bun command                                             |
| bx    | `bun x`                   | Install and execute a package bin                           |
| ba    | `bun add`                 | Install a package in dependencies (`package.json`)          |
| bad   | `bun add --dev`           | Install a package in devDependencies (`package.json`)       |
| brm   | `bun remove`              | Remove a dependency from package.json                       |
| bls   | `bun pm ls`               | list the dependency tree according to the current lockfile  |
| bi    | `bun init`                | Start an empty Bun project from a blank template            |
| bin   | `bun install`             | Install dependencies for a package.json                     |
| biny  | `bun install --yarn`      | Install dependencies and save lock file in yarn@v1 style    |
| bga   | `bun add --global`        | Install packages globally on your operating system          |
| bgls  | `bun pm ls --global`      | List global installed packages                              |
| bgrm  | `bun remove --global`     | Remove global installed packages from your OS               |
| bgu   | `bun update --global`     | Upgrade packages installed globally to their latest version |
| br    | `bun run`                 | Run JavaScript with Bun, a package.json script, or a bin    |
| brun  | `bun run`                 | Run JavaScript with Bun, a package.json script, or a bin    |
| bst   | `bun run start`           | Run the start script defined in `package.json`              |
| bln   | `bun run lint`            | Run the lint script defined in `package.json`               |
| bdocs | `bun run docs`            | Run the docs script defined in `package.json`               |
| bfmt  | `bun run format`          | Run the format script defined in `package.json`             |
| bb    | `bun run build`           | Run the build script defined in `package.json`              |
| bd    | `bun run dev`             | Run the dev script defined in `package.json`                |
| bsv   | `bun run serve`           | Run the serve script defined in `package.json`              |
| bt    | `bun run test`            | Run the test script defined in `package.json`               |
| btc   | `bun run test --coverage` | Run the test script defined in `package.json` with coverage |
| bu    | `bun update`              | Update outdated dependencies & save to package.json         |
| bc    | `bun create`              | Create a new project from a template                        |
| bbd   | `bun build`               | Bundle TypeScript & JavaScript into a single file           |
