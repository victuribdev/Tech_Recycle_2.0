# Tech-Recycle 2.0

Sistema de gerenciamento de pontos de coleta de materiais recicláveis.

## 🚀 Funcionalidades

- Mapa interativo com pontos de coleta
- Cadastro de pontos de coleta
- Filtro por tipo de material
- Sistema de autenticação
- Gerenciamento de usuários

## 🛠️ Tecnologias

- Node.js
- Express
- MySQL
- Handlebars
- Leaflet.js
- OpenCage Geocoding API

## 📋 Pré-requisitos

- Node.js (versão 14 ou superior)
- MySQL (versão 8.0 ou superior)
- NPM ou Yarn

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/victuribdev/tech-recycle-2.0.git
cd tech-recycle-2.0
```

2. Instale as dependências:
```bash
npm install
```

3. Configure as variáveis de ambiente:
Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis:
```
DB_HOST=localhost
DB_USER=seu_usuario
DB_PASSWORD=sua_senha
DB_NAME=tech_recycle
DB_PORT=3306
SESSION_SECRET=seu_segredo_aqui
```

4. Inicie o servidor:
```bash
npm start
```

## 📦 Estrutura do Projeto

```
tech-recycle-2.0/
├── assets/          # Arquivos estáticos (CSS, imagens, etc)
├── views/           # Templates Handlebars
├── routes/          # Rotas da aplicação
├── controllers/     # Controladores
├── models/          # Modelos do banco de dados
├── config/          # Configurações
└── index.js         # Arquivo principal
```

## 🤝 Contribuindo

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/AmazingFeature`)
3. Faça o Commit das suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Faça o Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## ✒️ Autores

* **Victor Ribeiro** - *Desenvolvimento* - [victuribdev](https://github.com/victuribdev) 