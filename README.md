![GitHub Logo](images/robert_kapa_second_war.jpg)

# BASHRC do Robert Kapa

Estes são os arquivos de configuração do shell bash do Mr. Kapa. 

Para fazer com que estes arquivos sejam válidos para seu shell Bash, é necessário baixar este repositório e criar links simbólicos do diretório do seu usuário

```
$ git clone https://github.com/robertkapa/bashrc-robertkapa.git
$ cd bashrc
$ ln -sf $(pwd)/bash_profile ~/.bash_profile
$ ln -sf $(pwd)/bashrc ~/.bashrc
$ . ~/.profile
```

```
$ source /etc/bash_completion.d/git-prompt
```

Referência: https://github.com/GustavoVS/bashrc
