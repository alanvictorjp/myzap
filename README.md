#### Este é uma cópia do myzap original desenvolvido por Bill Barsch.
#### Nessa cópia, foi adicionado alguns métodos e removido algumas coisas.

- Removido opção de guardar token em nuvem
- Removido arquivos referentes ao docker
- Removido arquivos .sh para manuseio do docker
- Removido lib venom-bot

## Instalação
`apt update -y && apt upgrade -y && apt install git curl wget lsof build-essential procps vim -y`

`curl -fsSL https://deb.nodesource.com/setup_16.x | bash -`

`apt install nodejs -y`

`cd /`

`git clone https://github.com/alanvictorjp/myzap.git`

`cd myzap/`

`npm install && npm update`


#### Opcional, se não instalar o chrome, será usado o chromium
`wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb`

`dpkg -i google-chrome-stable_current_amd64.deb`

`apt-get -f install`
