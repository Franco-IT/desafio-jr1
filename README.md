# Desafio Técnico — Desenvolvedor(a) Full Stack Júnior

Bem-vindo(a) ao desafio técnico para a vaga de Desenvolvedor(a) Júnior na **Franco IT**. O objetivo deste teste é avaliar os teus conhecimentos fundamentais em **Node.js** e **React**, bem como a tua organização, boas práticas e capacidade de estruturar uma solução simples e funcional.

---

## 🛠️ O Desafio: Mini-Gerenciador de Tarefas (To-Do List)

Deves construir uma aplicação web full stack para gestão de tarefas diárias. A aplicação será composta por uma API (Backend) e uma Interface Web (Frontend) que comunicam entre si.

### 📋 Requisitos do Backend (Node.js)
Deves criar uma API simples utilizando **Node.js** (com Express ou a framework da tua preferência, como NestJS). 
*Não é obrigatório configurar um banco de dados complexo (PostgreSQL/MongoDB); podes persistir os dados em memória (um array) ou num ficheiro `.json` local.*

A API deve expor as seguintes rotas:
* `GET /tasks`: Retorna a lista de todas as tarefas.
* `POST /tasks`: Cria uma nova tarefa. Cada tarefa deve ter pelo menos: `id`, `title` (título) e `completed` (booleano).
* `DELETE /tasks/:id`: Remove uma tarefa específica através do seu ID.

### 🎨 Requisitos do Frontend (React)
Deves criar uma interface simples e limpa utilizando **React** (podes usar Vite, Next.js ou React Puro) que consuma a API desenvolvida.

A interface deve conter:
* Um campo de texto e um botão para adicionar uma nova tarefa.
* A listagem das tarefas atuais que foram procuradas no backend.
* Um botão ou ícone ao lado de cada tarefa para a conseguir eliminar.

---

## ⚙️ O que vamos avaliar?

Não procuramos uma aplicação visualmente perfeita ou ultra-complexa, mas sim fundamentos sólidos:

* **Organização de Código:** Estrutura de pastas clara, nomes de variáveis intuitivos e código limpo.
* **Fundamentos de Node.js:** Configuração correta de rotas, métodos HTTP adequados (`GET`, `POST`, `DELETE`) e tratamento básico de erros (ex: não tentar eliminar uma tarefa que não existe).
* **Fundamentos de React:** Uso correto de Hooks (`useState`, `useEffect`), controlo de formulários e componentização equilibrada.
* **Comunicação Front-Back:** Integração assíncrona (`fetch` ou `axios`) e configuração correta de CORS no backend.
* **Uso de Git:** Histórico de commits organizado e mensagens claras.

---

## 🚀 Como Entregar

1. Cria um repositório **público** no teu GitHub.
2. Podes organizar o projeto como um monorepo (ex: uma pasta `/backend` e uma pasta `/frontend`) ou em repositórios separados, como preferires.
3. Altera o ficheiro `README.md` principal explicando brevemente:
    * Como instalar as dependências e correr o Backend.
    * Como instalar as dependências e correr o Frontend.
4. Envia o link do repositório para o nosso e-mail de contacto assim que terminares.

*Dica: Foca-te primeiro em fazer o fluxo básico funcionar (Listar -> Criar -> Eliminar) antes de te preocupares com estilizações avançadas.*

Boa sorte! Estamos ansiosos por ver o teu código. 🚀
