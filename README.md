# Laravel bash aliases

A list of Laravel bash aliases.

```
alias ll='ls -l'
alias la='ls -la'

alias ps='phpstorm'

# git
alias g='git'
alias gs='git status'
alias gl="git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
alias nah="git reset --hard;git clean -df"
alias wip="git add . && git commit -m 'wip'"

alias p="phpunit"
alias pf="phpunit --filter "

# Laravel
alias art="php artisan"
alias tinker='php artisan tinker'
alias migrate="php artisan migrate"
alias viewlog='tail -f -n 450 storage/logs/laravel*.log \
                | grep -i -E \
                    "^\[\d{4}\-\d{2}\-\d{2} \d{2}:\d{2}:\d{2}\]|Next [\w\W]+?\:" \
                    --color'
```

Apply changes

```
source ~/.bashrc
```

## Credits
[Awesome Laravel bash aliases](https://github.com/ahinkle/awesome-laravel-bash-aliases)

