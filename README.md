Projeto App React
Este projeto é um aplicativo desenvolvido em React Native utilizando Expo. O principal objetivo é consumir dados de uma API, exibir esses dados na tela e utilizar o armazenamento local do dispositivo por meio do Async Storage.

Conteúdo:

Descrição do Projeto

Funcionalidades

Tecnologias Utilizadas

Instalação e Execução

Estrutura do Projeto

Licença

Descrição do Projeto: O aplicativo busca dados da API JSONPlaceholder e exibe uma lista de posts. Cada post apresenta seu título e corpo. Além disso, os dados são armazenados localmente com o Async Storage, permitindo acesso rápido mesmo sem conexão com a internet.

Funcionalidades:

Consumo de API: Recebe dados da API e os armazena localmente.

Armazenamento Local: Utiliza o Async Storage para guardar as informações em cache.

Exibição dos Dados: Apresenta os posts em uma lista com um indicador de carregamento enquanto os dados são buscados.

Tecnologias Utilizadas:

React Native: Framework para desenvolvimento mobile.

Expo: Plataforma para criar, construir e implantar aplicativos React Native.

Async Storage: Biblioteca para gerenciamento de valores armazenados localmente.

Instalação e Execução:

Pré-requisitos:

Node.js (versão LTS recomendada)

npm ou yarn

Expo CLI (integrado localmente ao projeto)

Passos para Instalação:

Clone o repositório:

git clone https://github.com/SeuUsuario/ProjetoAppReact.git
Entre na pasta do projeto:

cd ProjetoAppReact
Instale as dependências:

npm install
Inicie o projeto:

npx expo start
Você poderá escolher executar o aplicativo:

Em um dispositivo móvel utilizando o aplicativo Expo Go;

Emulador Android com npm run android;

Emulador iOS (em macOS) com npm run ios;

Pelo navegador com npm run web.

Estrutura do Projeto:

ProjetoAppReact/
├── App.js            # Arquivo principal do aplicativo
├── package.json      # Gerenciamento de dependências e scripts
├── node_modules/     # Módulos instalados
├── app.json          # Configurações do Expo para o projeto
└── README.md         # Este arquivo de documentação