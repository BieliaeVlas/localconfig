Install zsh plugins:
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
1. Install ITerm2
2. Install oh-my-zsh
3. Clone **localconfig** https://github.com/BieliaeVlas/localconfig
4. Run the following commands: 

```bash
cd localconfig && cp ./.zshrc ~/.zshrc
```
5. Restart ITerm2
6. Install the fonts in **localconfig**
7. Import json configuration profile in ITerm2 Settings
8. (Optional) Configure nvim:
    - git clone https://github.com/BieliaeVlas/nvim.git
    - Follow the steps mentioned in README.md
