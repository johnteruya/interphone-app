#INTERPHONE APP
#Meus Git Alias
##Sempre que utilizar este, em um computador novo, introduzir ao git.

###Comando Básicos
1. git config --global alias.co checkout
2. git config --global alias.cm commit -m
3. git config --global alias.st status -sb
4. git config --global alias.tags tag -l 
5. git config --global alias.branches branch -a 
6. git config --global alias.remotes remote -a 
7. git config --global alias.delbr branch -D 

###Comando Personalizados
1. git config --global alias.lg 'log --all --graph --decorate --oneline --abbrev-commit'
2. git config --global alias.ac '!git add -A && git commit -m'
3. git config --global alias.envia '!git push && git rebase' --replace-all
