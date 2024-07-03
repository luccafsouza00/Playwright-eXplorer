# MasterClass Playwright eXplorer

Este projeto é parte da MasterClass **Playwright eXplorer** ministrada pela **QAx**. O objetivo é explorar uma aplicação para testar o player de música de um clone do Spotify desenvolvido em **React.js**. Utilizamos **Playwright** em **TypeScript** para criar e executar os testes automatizados.

## Funcionalidades Principais

Em especial, destaca-se a utilização da função `route` do **Playwright**, permitindo a interceptação da API e a criação de mocks para simular requisições HTTP. Isso facilita testar o carregamento de músicas no formato MP3 de maneira personalizada para as necessidades do teste.

## Tecnologias Utilizadas

- **React.js**: Utilizado no desenvolvimento da aplicação de clonagem do Spotify.
- **TypeScript**: Linguagem utilizada para escrever os testes.
- **Playwright**: Ferramenta de automação de testes.

## Requisitos

- **Node.js**: v20.15.0
- **Playwright**: 1.17.132

## Como Executar os Testes

Para rodar os testes, siga os passos abaixo:

1. Certifique-se de que você tem o **Node.js** na versão especificada (v20.15.0) instalado em sua máquina.
2. Instale as dependências do projeto.
    ```sh
    npm install
    ```
3. Execute os testes com o seguinte comando:
    ```sh
    npx playwright test
    ```
