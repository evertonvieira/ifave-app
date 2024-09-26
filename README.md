# IFAVE App

Este é um projeto desenvolvido com Ionic. Este README contém informações sobre como configurar e executar o projeto em seu ambiente local.

## Requisitos

Antes de começar, você precisará ter as seguintes ferramentas instaladas em sua máquina:

- [Node.js](https://nodejs.org/) (versão 20 ou superior)
- [npm](https://www.npmjs.com/) (geralmente vem com o Node.js)
- [Ionic CLI](https://ionicframework.com/docs/cli) (instale usando `npm install -g @ionic/cli`)
- [Cordova](https://cordova.apache.org/) (opcional, se você precisar de funcionalidades nativas)

## Configuração do Projeto

Siga os passos abaixo para configurar o projeto:

1. **Clone o repositório**:
   ```bash
    git clone https://github.com/evertonvieira/ifave-app.git
    cd ifave-app
   ```

2. **Instale as dependências**:

   ```bash
    npm install
   ```

3. **Verifique a instalação do Ionic**:

    Para garantir que o Ionic CLI está instalado corretamente, execute:

   ```bash
    ionic --version
   ```


## Executando o Projeto

Para rodar o projeto em um navegador, use o seguinte comando:

   ```bash
    npm start
   ```

Isso abrirá o aplicativo em seu navegador padrão em `http://localhost:4200`.


## Construindo o Aplicativo

Se você deseja construir o aplicativo para produção, use:

   ```bash
    npm run build
   ```

Os arquivos de produção serão gerados na pasta `www` na raiz do projeto.


## Testes
Para executar os testes:

   ```bash
    npm run test
   ```

### Contribuindo
Se você deseja contribuir para o projeto, sinta-se à vontade para abrir um pull request ou reportar problemas :D.