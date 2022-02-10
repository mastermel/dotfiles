# dotfiles
My dotfiles, primarily used on OS X with zsh

## OS X Setup

### Install the following apps:
* (Rectangle)[https://rectangleapp.com]
* (iTerm2)[https://iterm2.com/]
* (Homebrew)[https://brew.sh/]

### Setup terminal:
1. (Create a new SSH key and add it to Github)phttps://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent[
2. Clone this repo to `~/dotfiles`
4. Install (oh-my-zsh)[https://ohmyz.sh/#install]
5. Install (powerlevel10k theme)[https://github.com/romkatv/powerlevel10k#getting-started]
6. Install (zsh-autosuggestions)[https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh]
7. Install (zsh-syntax-highlighting)[https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md]
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/tools/zsh-syntax-highlighting
```
7. Install (asdf)[https://github.com/kiurchv/asdf.plugin.zsh#as-an-oh-my-zsh-custom-plugin]
8. Install (asdf zsh plugin)[https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/asdf]
9. Symlink the appropriate dotfils (removing where necessary)
  ```
  ln -s ~/dotfiles/.asdfrc ~/.asdfrc
  ln -s ~/dotfiles/.tool-versions ~/.tool-versions
  ln -s ~/dotfiles/.zshrc ~/.zshrc
  ln -s ~/dotfiles/Library/Preferences/com.googlecode.iterm2.plist ~/Library/Preferences/com.googlecode.iterm2.plist  
  ```

### Setup (vimconfig)[https://github.com/mastermel/vimconfig]
