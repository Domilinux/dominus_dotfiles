# Lines configured by zsh-newuser-install
HISTFILE=~/.histfile
HISTSIZE=100
SAVEHIST=1000
setopt extendedglob
unsetopt beep
bindkey -v
# End of lines configured by zsh-newuser-install
# The following lines were added by compinstall
zstyle :compinstall filename '/home/domagoj/.zshrc'

# completion vim style

autoload -U compinit
zstyle ':completion:*' menu select
zmodload zsh/complist
compinit
_comp_options+=(globdots)		# Include hidden files.




bindkey -M menuselect 'h' vi-backward-char
bindkey -M menuselect 'k' vi-up-line-or-history
bindkey -M menuselect 'l' vi-forward-char
bindkey -M menuselect 'j' vi-down-line-or-history
bindkey -v '^?' backward-delete-char

# PS1
#PROMPT='%F{red}%m%F{magenta}@%F{yellow}domagoj  %F{green}%1~ %F{blue}❯  '
#PROMPT='%F{blue}%1~ %F{magenta}❯ '
PROMPT='%F{green}%1~ %F{magenta}>>> %F{}'
#PS1="%B%{$fg[red]%}[%{$fg[yellow]%}%n%{$fg[green]%}@%{$fg[blue]%}%M %{$fg[green]%}%~%{$fg[red]%}]%$%b "
#export PS1

# aliases

alias ls='ls --color=always'
alias ssh='/usr/bin/ssh '
alias network='sudo virsh net-start default'

autoload -Uz compinit
compinit
# End of lines added by compinstall
#source /usr/share/zsh/plugins/fast-syntax-highlighting/fast-syntax-highlighting.plugin.zsh 2>/dev/null

source /home/domagoj/zsh-autosuggestions/zsh-autosuggestions.zsh
source /home/domagoj/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
