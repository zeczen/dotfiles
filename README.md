# dotfiles
```
git clone https://github.com/zeczen/dotfiles.git
find . -maxdepth 1 -type f -name '.*' -exec ln -s "$PWD/{}" "$HOME/{}" \;  # to create link to the config files from ~
