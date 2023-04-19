# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

Project testing started (for me) in April 2023.

## Startup Procedures - as in Original Docs

But a bit tweaked here:

Make a backup of your current Neovim files:

```
# required
mv ~/.config/nvim ~/.config/nvim.bak-$(date -I)
  
# optional but recommended
mv ~/.local/share/nvim ~/.local/share/nvim.bak-$(date -I)
mv ~/.local/state/nvim ~/.local/state/nvim.bak-$(date -I)
mv ~/.cache/nvim ~/.cache/nvim.bak-$(date -I)
```

Clone the starter

```
git clone git@github.com:joebrandes/lazyvim-config ~/.config/nvim
```

**Don't** Remove the .git folder, so you can add it to your own repo later

```
# rm -rf ~/.config/nvim/.git
```

Start Neovim!

```
nvim
```

Refer to the comments in the files on how to customize LazyVim.

tip

It is recommended to run ``:checkhealth`` after installation

