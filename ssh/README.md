# Chave SSH 

*1* Entrar Git Bash 
*2* DIGITAR: ssh-keygen -t ed25519 -C email
*3* Digite a senha que desejar
*4* DIGITAR: cd /C/Users/Gabrielle/.ssh/
*5* ls
*6* DIGITAR: cat id_ed25519.pub
*7* Copie a senha e coloque no GitHub 

_Voltando para o Git Bash_

*8* ls
*9* DIGITAR: eval $(ssh-agent -s)
*10* ls
*11* DIGITAR: ssh-add id_ed25519
*12* Digite a senha que criou anteriormente