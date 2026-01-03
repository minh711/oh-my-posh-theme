# oh-my-posh theme

My customized theme for oh-my-posh

## Features

1. Remove uneccessary segments
2. Display `venv` name

<img width="480" height="196" alt="image" src="https://github.com/user-attachments/assets/8b611d07-419d-4819-861f-b96d7606149b" />

## Installation

### On Windows

Go to this location:

```bash
C:\Users\{username}\AppData\Local\Programs\oh-my-posh\themes
```

Then paste the json there.

Put this theme in the profile ([How to create a profile?](https://ohmyposh.dev/docs/installation/prompt)):

```bash
oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH/custom.omp.json" | Invoke-Expression
```

### On Linux

In my case, I add this to the end of `~/.bashrc`:

```bash
export PATH="$PATH:$HOME/.local/bin"

eval "$(oh-my-posh init bash --config /home/<username>/.cache/oh-my-posh/themes/custom.omp.json)"
```
