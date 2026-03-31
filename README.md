# 🚗 Sistema de Estacionamento

Projeto acadêmico e de portfólio para gerenciamento de estacionamento de veículos, desenvolvido em **Node.js** com separação entre **Front-End** e **Back-End**.
O objetivo é praticar **organização de projetos**, **versionamento com Git/GitHub** e uso de **dependências modernas**.

---

# 📂 Estrutura do Projeto

```
Estacionamento/
│
├── FrontEnd/        # Interface do usuário
│
└── BackEnd/         # API e lógica de negócio
    │
    ├── controllers/
    │   ├── ProprietarioControlls.js
    │   └── VeiculoControlls.js
    │
    ├── models/
    │   ├── db.js
    │   ├── Proprietario.js
    │   └── Veiculo.js
    │
    ├── node_modules/
    │
    ├── index.js
    ├── package.json
    └── package-lock.json
```

---

# 🚀 Instalação

## 1. Clonar o repositório

```bash
git clone https://github.com/Rodrigo-Mazzucco/projeto-estacionamento.git
```

---

## 2. Entrar na pasta do BackEnd

```bash
cd BackEnd
```

---

## 3. Instalar dependências

```bash
npm install
```

---

# 📦 Dependências utilizadas

* **express** → framework para criação de rotas e servidor
* **nodemon** → reinicialização automática em desenvolvimento
* **sequelize** → ORM para banco de dados
* **body-parser** → parser de requisições HTTP
* **mysql2** → driver para conexão com MySQL
* **cors** → habilita requisições cross-origin

Instalação manual (caso necessário):

```bash
npm install express sequelize body-parser mysql2 cors --save
npm install -g nodemon
```

---

# ▶️ Como rodar o projeto

## Ambiente de desenvolvimento

```bash
nodemon index.js
```

## Ambiente de produção

```bash
npm start
```

---

# 🛠️ Tecnologias

* Node.js
* Express
* Sequelize
* MySQL
* JavaScript (ES6+)
* Nodemon

---

# 📖 Commits Semânticos

O projeto segue o padrão de **commits semânticos**:

* **feat:** → nova funcionalidade
* **fix:** → correção de bug
* **docs:** → mudanças na documentação
* **style:** → ajustes de formatação
* **refactor:** → melhorias de código sem alterar funcionalidade
* **test:** → inclusão ou alteração de testes
* **chore:** → tarefas de manutenção (ex.: remover node_modules, atualizar dependências)

Exemplo:

```bash
git commit -m "feat: adicionar estrutura inicial do BackEnd"
```

---

# 📌 Observações

* A pasta **node_modules** não é versionada (controlada pelo `.gitignore`).
* Para rodar o projeto em qualquer máquina, basta **clonar o repositório** e executar:

```bash
npm install
```

* O repositório está organizado para manter **FrontEnd** e **BackEnd separados na raiz**.
