# 📦 Projeto QR Code - Formação Node.js (DIO)

Este projeto faz parte da **formação Node.js** da [Digital Innovation One (DIO)](https://www.dio.me/) e tem como objetivo a **geração de QR Codes e senhas seguras** utilizando Node.js e conceitos modernos de arquitetura de software.


## 📁 Estrutura do Projeto

    projeto-qrcode/
    ├── .env # Variáveis de ambiente
    ├── .gitignore # Arquivos ignorados pelo Git
    ├── package.json # Dependências e scripts
    ├── package-lock.json # Controle de versões das dependências
    ├── docs/
    │ └── arquitetura.tldr # Resumo da arquitetura do projeto
    ├── src/
    │ ├── index.js # Ponto de entrada da aplicação
    │ ├── prompts-schema/ # Schemas de entrada de dados via terminal
    │ │ ├── prompt-schema-main.js
    │ │ └── prompt-schema-qrcode.js
    │ └── services/
    │ ├── password/ # Geração de senhas seguras
    │ │ ├── create.js
    │ │ ├── handle.js
    │ │ └── utils/permitted-characters.js
    │ └── qr-code/ # Geração de QR Codes
    │ ├── create.js
    │ └── handle.js


## 🚀 Funcionalidades

- ✅ Geração de QR Codes a partir de texto/URLs
- ✅ Geração de senhas fortes e personalizadas
- ✅ Estrutura modular seguindo boas práticas

## 🔧 Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [Prompt](https://www.npmjs.com/package/prompt)
- [QRCode](https://www.npmjs.com/package/qrcode)

## ▶️ Como Executar

1. Clone o repositório e navegue até a pasta do projeto:

        git clone https://github.com/Arielson13/formacao-nodejs-DIO.git
        cd formacao-nodejs-DIO/projeto-qrcode

2. Instale as dependências:

        npm install
3. Crie um arquivo `.env` se necessário (ex: com variáveis de configuração).
4. Inicie o projeto:

        node src/index.js

## 🧠 Aprendizados
Durante a construção deste projeto, foram aplicados conceitos como:

- Modularização de código

- Manipulação de entrada via terminal

- Uso de bibliotecas para criptografia e QRCode

- Separação de responsabilidades (Services, Prompts, Utils)



