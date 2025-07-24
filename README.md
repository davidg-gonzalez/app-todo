# ✅ app-todo

Aplicação de lista de tarefas desenvolvida com **Vue.js**. Este projeto utiliza o `json-server` como um backend fake para simular uma API REST, facilitando o desenvolvimento e testes de funcionalidades.

---

## ✨ Funcionalidades

- ✅ Adicionar novas tarefas
- 📝 Editar tarefas existentes
- ❌ Remover tarefas
- 📌 Marcar como concluída
- 💾 Persistência simulada com `json-server`

---

## 🛠 Tecnologias utilizadas

- [Vue.js](https://vuejs.org/)
- [json-server](https://github.com/typicode/json-server)
- [Yarn](https://classic.yarnpkg.com/)

---

## 📦 Instalação e execução

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/app-todo.git
cd app-todo
```

### 2. Instale as dependências

```bash
yarn install
```

### 3. Inicie o backend fake (json-server)

Instale o `json-server` globalmente (se necessário):

```bash
npm install -g json-server
```

Execute o servidor:

```bash
json-server --watch database.json --port 3000
```

A API estará disponível em: [http://localhost:3000](http://localhost:3000)

> Obs: o arquivo `database.json` está incluído no projeto.

---

### 4. Inicie o servidor de desenvolvimento

```bash
yarn serve
```

Acesse: [http://localhost:8080](http://localhost:8080)

---

## 🧾 Scripts disponíveis

| Comando              | Ação                                |
|----------------------|-------------------------------------|
| `yarn serve`         | Inicia o app com hot-reload         |
| `yarn build`         | Compila para produção               |
| `yarn lint`          | Aplica lint e correções automáticas |

---

## 🔧 Personalização

Para personalizar configurações avançadas, consulte: [Vue CLI Config](https://cli.vuejs.org/config/)

---

## 📌 Observações

Este projeto é apenas para fins de aprendizado e demonstração no portfólio. O backend é simulado via `json-server`, portanto os dados são armazenados apenas temporariamente durante a execução.

---

## 👨‍💻 Autor

**David Gonzalez**  
[GitHub](https://github.com/davidg-gonzalez)  
[LinkedIn](https://www.linkedin.com/in/david-gonzalez-728015302/)