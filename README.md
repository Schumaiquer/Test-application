# Aplicação para testar framework de automação

A aplicação consiste num cadastro de jogos (ninja-reto-games)


### Passos para instalação e execução do projeto

## Instale o Ruby

* No Windows [https://qaninja.io/instalando-ruby-no-windows/]
* No Linux [https://qaninja.io/instalando-ruby-nodejs-e-zsh-no-linux-ubuntu/]
* No macOS [https://qaninja.io/instalando-ruby-nodejs-e-zsh-no-macos/]

## Passo a passo comandos para rodar

### 1. Gerenciador de pacotes do Ruby


`
gem install bundler
`


### 2. Instale o Rails


`
gem install rails -v 5.1.4
`


### 3. Workarround SQLite no Windows (Caso Seja Windows)


`
gem install sqlite3 --platform=ruby -- --with-sqlite3-dir=C:/distr/sqlite --with-sqlite3-include=C:/distr/sqlite
`


### 4. Dependências do projeto


`
bundle install
`


### 5. Banco de dados


`
rails db:migrate
`


## Executando a aplicação

A aplicação sobe http://localhost:3000/

`
rails s
`

