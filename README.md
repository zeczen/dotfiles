## dotfiles
This repo maneges my config files.

# Configure
```bash
git clone https://github.com/zeczen/dotfiles.git ./.dotfiles
cd ./.dotfiles
find . -maxdepth 1 -type f -name '.*' -exec ln -s "$PWD/{}" "$HOME/{}" \;  # to create link to the config files from ~
