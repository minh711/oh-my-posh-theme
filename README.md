# oh-my-posh theme
My customized theme for oh-my-posh

## Features

> **NOTE**: The styles and colors are not updated

1. Remove uneccessary segments, just keep **path** and **git**

![image](https://github.com/user-attachments/assets/44044fb3-456a-4abe-8b48-18a69be34b53)

2. Display `venv` name

![image](https://github.com/user-attachments/assets/0baf088a-acb1-486b-9536-8f4af47adc3c)

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
