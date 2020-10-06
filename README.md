# My [Neovim](https://neovim.io/) setup.

## This setup is based of of the setup in this [video](https://www.youtube.com/watch?v=gnupOrSEikQ) by Ben Awad. The differences between his and mine will be stated later.

  This vim setup includes the following plugins:
    - Vim-NERDTree-Syntax-Highliting
    - Vim-Devicons
    - NERDCommenter
    - Vim-GitGutter
    - Gruvbox (Theme)
    - NERDTree 
    - CtrlP.vim
    - NERDTree-Git-Plugin
    - CoC.nvim
    - Emmet.vim
    - Yats.vim

## Differences

  So far, the only two difference is that I use Ctrl+H, J, K, L 
  to navigate splits (such as NERDTree), aswell as Emmet, which is a
  script for HTML.

## Installation

  If you are using one of the following package managers, skip
  the next paragraph.

    - Pacman 
    - Apt-get/Apt
    - Dnf
    - Yum 

  If you are not using a distro using one of those, you will
  have to manually install Neovim either using the package manager
  of you're distro, otherwise you can try installing the flatpak,
  snap, or appimage application.

  Now you have Neovim installed, you can run the script. Open a
  terminal and write the following command.
  
  ```
  git clone https://github.com/coreytl-github/nvimSetup.git
  ```

  After this, type this command.

  ```
  cd nvimSetup/
  ```

  Now, type this command.

  ```
  ./nvimSetup.sh
  ```

  Now it should be installed!

##Extra info

  If you find any errors, make an issue on my github.
  If you want to change my setup, the init.vim is located at
  ~/.config/nvim/init.vim 

  I hope you enjoy this setup!
