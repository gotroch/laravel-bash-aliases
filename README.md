# Laravel bash aliases

A list of Laravel bash aliases.

```
alias ll='ls -l'
alias la='ls -la'
alias ps='phpstorm'
alias g='git'
alias gs='git status'
alias gl='git pull'
alias gu='git push'
alias gl="git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
alias nah="git reset --hard;git clean -df"
alias wip="git add . && git commit -m 'wip'"
alias p="phpunit"
alias pf="phpunit --filter "
alias art="php artisan"
alias tinker='php artisan tinker'
alias migrate="php artisan migrate"
```

Apply changes

```
source ~/.bashrc
```
