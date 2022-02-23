# Enable the subsequent settings only in interactive sessions
case $- in
  *i*) ;;
    *) return;;
esac

# Path to your oh-my-bash installation.
export OSH=/home/moo/.oh-my-bash

# STYLES 
## https://github.com/ohmybash/oh-my-bash/blob/master/themes/THEMES.md

OSH_THEME="font"
CASE_SENSITIVE="true"
ENABLE_CORRECTION="true"
COMPLETION_WAITING_DOTS="true"
HIST_STAMPS="yyyy-mm-dd"
OMB_USE_SUDO=true

# COMPLETIONS 
## /.oh-my-bash/completions/*

completions=(
  git
  composer
  ssh
)

# ALIASES
## /.oh-my-bash/aliases/*
## /.oh-my-bash/custom/aliases/

aliases=(
  general
)

alias bashconfig="mate ~/.bashrc"
alias ohmybash="mate ~/.oh-my-bash"
alias rnote="flatpak run com.github.flxzt.rnote"
alias startmax="emacs --daemon &; sleep 5; emacsclient -c -a 'emacs'"
alias emax="emacsclient -c -a 'emacs'"
alias killmax="emacsclient -e '(kill-emacs)'"
alias ll="ls -a"
alias csb="ssh mae117@cluster.csb.pitt.edu"
alias dennis="ssh mae117@klaus.devbio.pitt.edu"
alias eup="~/.emacs.d/bin/doom upgrade; ~/.emacs.d/bin/doom sync; ~/.emacs.d/bin/doom purge; ~/.emacs.d/bin/doom doctor"
alias startr="sudo rstudio-server start"
alias stopr="sudo rstudio-server start"
alias up="sudo apt update && sudo apt upgrade -y"
alias saus="source .bashrc"

# PLUGINS
## /.oh-my-bash/plugins/*
## ~/.oh-my-bash/custom/plugins/

plugins=(
  git
  bashmarks
)

# EXPORTS
PATH=/home/moo/.local/bin:$PATH

# OH-MY-BASH
source "$OSH"/oh-my-bash.sh
