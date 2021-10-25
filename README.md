**Instalando Typora Linux Mint**

Olá pessoal :tipping_hand_man:

Estive com dificuldade para instalar o typora no linux mint, por isso estou colocando aqui a lista de comandos que precisei utilizar para instalar esse carinha.

***Abra o terminal e siga a sequência de passos abaixo***

`1º passo`

`wget -qO - https://typora.io/linux/public-key.asc | sudo apt-key add -`

`2º passo`

`echo -e "\ndeb https://typora.io/linux ./" | sudo tee -a /etc/apt/sources.list`

`3º passo`

`sudo apt-get update` 

`4º e último passo`

`sudo apt-get install typora`

Agora é só utilizar esse excelente editor de texto para arquivos README.

