# Sobre o RepoStoreMobile

O RepoStore é uma aplicação para armazenar repositórios do GitHub, dividida em três partes: [front-end web](https://github.com/EdeiltonSO/RepoStoreWeb), [back-end](https://github.com/EdeiltonSO/RepoStoreServer) e front-end mobile (este repositório).

Por meio da versão mobile, o usuário pode visualizar o título, tecnologias utilizadas e o número de likes de cada repositório armazenado no back-end. Além disso, é possível curtir os repositórios listados.

## Tecnologias utilizadas

* [JavaScript](https://www.javascript.com/)
* [React Native](https://reactnative.dev/)

# Execução

## Requisitos

### 1. Gerenciador de pacotes

Para conseguir executar os comandos do passo a passo a seguir, é necessário contar com o gerenciador de pacotes [Yarn](https://yarnpkg.com/) instalado em sua máquina. Se preferir, o NPM também pode ser utilizado (mas claro; os comandos serão diferentes).

### 2. Ambiente React Native

Para executar o RepoStoreMobile na sua máquina, é preciso contar com um dispositivo físico ou emulador iOS ou Android configurado. Se essa etapa ainda precisa ser executada, [esta documentação da Rocketseat](https://react-native.rocketseat.dev/) pode te ajudar a preparar um ambiente para executar aplicações React Native. 

## Executando a aplicação

Com tudo configurado, basta seguir os passos abaixo:

1. Faça o download do repositório;

2. Abra a pasta do projeto com um editor de código — como o [Visual Studio Code](https://code.visualstudio.com/);

3. No terminal, execute:
* ```yarn```;
* ```yarn start```;

Abra outra instância do terminal e, como o emulador aberto (ou device físico conectado), prossiga com:
* ```yarn android``` para executar a versão Android e/ou ```yarn ios``` para executar a versão iOS;

## Observações

### 1. Network Error
Caso ocorra um ```Network Error``` na execução do app em emuladores Android, abra uma instância do terminal e execute o comando ```adb reverse tcp:3333 tcp:3333``` e recarregue a aplicação;

### 2. Back-end
Sem o back-end (ou com um back-end sem repositórios), o app somente mostrará uma tela roxa. Assim, é fundamental executar o [RepoStoreServer](https://github.com/EdeiltonSO/RepoStoreServer) e adicionar um repositório de teste para visualizar o resultado da busca.