# new_pc_setup


echo export PS1="\[\033[38;5;9m\]\u\[$(tput sgr0)\] @ \[$(tput sgr0)\]\[\033[38;5;2m\]\h\[$(tput sgr0)\] \[$(tput sgr0)\]\[\033[38;5;14m\]\$(git branch 2> /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/(\1)/')\[$(tput sgr0)\] > \[$(tput sgr0)\]" >> .bashrc

