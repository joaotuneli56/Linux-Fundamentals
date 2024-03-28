# CAP 02.05 Arquivos de configuração do shell

Alguns arquivos são automaticamente lidos pelo shell no momento do login e do logout de um usuário ou ainda no momento da chamada do shell a partir de uma sessçao que já tenha sido iniciada.

Caso o bash seja invocado durante um login , ele lerá os atrquivos `/etc/profile` , `~/.bash_profile`,`~/.bash_login` e `~/.profile`, nessa ordem, caso eles existam.

Quando não se tratar de um shell invocando numa sessão de login, como é o caso de  teterminais em sessões X, os arquivosexecutados automaticamente, caso existam , serão o `/etc/bash.bashrc` e `~/.bashrc`

## Para que serve as alias

O alias serve para dar um apelido para algo, no nosso caso muito utilizada para chamar comandos muito extensos com apenas 1 palavra

### Criando alias

```bash
alias nat="comando"
```

### Reescrevendo alias

```bash
unalias nat="comando"
```


`OBS:` A pasta `/etc` , se aplica a todos os usuarios do sistema