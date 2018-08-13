# ubuntu-config
Etapes de configuration de mon ubuntu

* installation de gnome-tweak-tools pour activer le capslock -> ctrl
* installer enpass
* installation de chrome (plus rapide pour aller sur gmail, mais c'est tout ;-))
* ajouter my clef publique à github (https://github.com/settings/keys)
* install git : sudo apt install git
* configurer git : 

git config --global user.email "mickael.kurmann@gmail.com"
git config --global user.name "Mickael Kurmann"


* installer powerline font : sudo apt-get install fonts-powerline
* cloner https://github.com/elbouillon/nvim dans mon home : git clone git@github.com:elbouillon/nvim.git ~/.nvim

* installer tmux : sudo apt install tmux
* installer curl : sudo apt install curl
* installer yarn : https://yarnpkg.com/lang/en/docs/install/#debian-stable
* installer oh-my-zsh : sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

* linker la config zsh/tmux et vim : 

ln -s .config/nvim/.zshrc .zshrc

ln -s .config/nvim/.tmux.conf .tmux.conf

ln -s .config/nvim/.tmux.conf.local .tmux.conf.local

* faire de zsh le terminal par défaut : chsh -s `which zsh`
* installer zsh : sudo apt install zsh
* installer pip3 : sudo apt install python3-pip
* mettre à jour neovim-python : sudo pip3 install --upgrade neovim
* sortir de la session et se reconnecter
* lancer vim et installer les plugins : plugInstall
* installer autojump : sudo apt install autojump
* installer nvim : sudo apt install neovim
* installer tmux
* installer docker : https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-docker-ce
