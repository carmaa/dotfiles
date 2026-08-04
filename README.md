Using `stow` to sync symlinks between the repo and the home directory.

1. Install Xcode Command Line Tools by running `xcode-select --install`.
2. Create a SSH key and copy/paste to Github: `ssh-keygen` and `pbcopy < ~/.ssh/id_rsa [...].pub`
3. Clone repo: `git clone git@github.com:carmaa/dotfiles.git ~/.dotfiles`
4. Install homebrew: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
5. Install apps by going to the homebrew folder with the Brewfile and issue: `brew bundle`
6. Install configs by using stow: `stow bash` and `stow git` for instance
