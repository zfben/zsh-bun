# zsh-bun

![Version](https://img.shields.io/badge/version-1.0.0-brightgreen)
![License](https://img.shields.io/github/license/zfben/zsh-bun)

A zsh plugin for using `b` as [`bun`](https://bun.sh/) aliases and more.

| Alias | Command
| --- | ---
| `b` | `bun`
| `br` | `bun run`
| `bi` | `bun install`
| `ba` | `bun add`
| `bu` | `bun update`
| `bp` | `bun pm`
| `bx` | `bunx`
| `bd` | `bun dev`
| `bb` | `bun build`
| `bt` | `bun test`
| `bs` | `bun start`
| `bl` | `bun lint`

## Install

### Manual

```zsh
git clone --depth=1 https://github.com/zfben/zsh-bun.git ~/.zsh-bun
echo 'source ~/.zsh-bun/bun.plugin.zsh' >>~/.zshrc
```

### Using [oh-my-zsh](https://github.com/ohmyzsh/oh-my-zsh)

Execute `git clone https://github.com/zfben/zsh-bun ~/.oh-my-zsh/custom/plugins/zsh-bun`. Add `zsh-bun` into plugins array in `.zshrc`

### Using [zpm](https://github.com/zpm-zsh/zpm)

Add `zpm load zfben/zsh-bun` into .zshrc
