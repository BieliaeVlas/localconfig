## Prerequisites:
List of CLis to be installed beforehand:
- kubectl
- git
- ITerm2
- oh-my-zsh

## Configuration steps:
1. Install zsh plugins:
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
2. Clone **localconfig** https://github.com/BieliaeVlas/localconfig
3. Run the following commands: 
```bash
cd localconfig && cp ./.zshrc ~/.zshrc
```
4. Restart **ITerm2**
5. Install the fonts in **localconfig**
6. Import json configuration profile in **ITerm2** Settings
7. (Optional) Configure nvim:
    - Clone the repo: ```git clone https://github.com/BieliaeVlas/nvim.git```
    - Follow the steps mentioned in **README.md**
