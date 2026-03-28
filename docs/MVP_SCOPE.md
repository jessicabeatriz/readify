<nav aria-label="Seletor de Idioma / Language Switcher" align="center">
  <a href="#-português"><span aria-hidden="true">🇧🇷</span> Português</a> | <a href="#-english"><span aria-hidden="true">🇺🇸</span> English</a>
</nav>

---

## <span aria-hidden="true">🇧🇷</span> Português

# <span aria-hidden="true">📄</span> Readify - Visão do Produto e Escopo

### 1. Visão do Produto
O **Readify** é um diário virtual e organizador de leituras totalmente responsivo (Desktop e Mobile). Ele permite que os leitores gerenciem seu acervo, registrem seus sentimentos e anotações ao longo da leitura e organizem seus livros em coleções, tudo em uma interface limpa, acessível e personalizável.

### 2. Priorização de Funcionalidades (MoSCoW)

#### MUST HAVE (Obrigatório para o MVP - v1.0)
* **Autenticação Segura:** Cadastro e Login (JWT). O usuário tem uma área privada e só visualiza seus próprios dados.
* **Gestão de Acervo (CRUD):** Adicionar, editar, listar e remover livros (Título, Autor, Gênero, Capa).
* **Rastreamento de Status:** Classificar livros em: `QUERO LER`, `LENDO`, `LIDO`, `ABANDONADO` e `LISTA DE DESEJOS`.
* **Diário de Leitura (Notas):** O usuário pode adicionar múltiplas anotações a um mesmo livro (ex: registrar um acontecimento marcante, uma citação ou o sentimento daquele momento), formando um histórico de leitura.
* **Avaliação (Rating):** Poder atribuir uma nota (ex: 1 a 5 estrelas) para o livro.
* **Responsividade e Acessibilidade:** Interface web fluida para celular e PC, com suporte a leitores de tela e navegação 100% por teclado (foco em a11y).

#### SHOULD HAVE (Importante, mas entra na v2.0)
* **Coleções Personalizadas:** Criar tags/pastas customizadas para agrupar livros (ex: "Favoritos da Vida", "Ficção Científica", "Lidos em 2026").
* **Dashboard de Estatísticas:** Visão geral do perfil (ex: quantos livros foram lidos no ano, autores mais lidos).

#### COULD HAVE (Diferencial técnico - v2.5)
* **Busca via API Externa:** Preenchimento automático dos metadados do livro (capa, autor, etc.) consumindo a API do Google Books através do ISBN.
* **Dark Mode:** Alternância de tema claro/escuro na interface.

#### WON'T HAVE (Fora do escopo - Não faremos)
* Rede social, feed de amigos ou comentários públicos.
* Sistema de empréstimo de livros entre usuários.
* Aplicativo Mobile Nativo (iOS/Android).

---

## <span aria-hidden="true">🇺🇸</span> English

# <span aria-hidden="true">📄</span> Readify - Product Vision and Scope

### 1. Product Vision
**Readify** is a fully responsive (Desktop and Mobile) virtual diary and reading organizer. It allows readers to manage their collection, record their feelings and notes throughout their reading journey, and organize their books into collections, all within a clean, accessible, and customizable interface.

### 2. Feature Prioritization (MoSCoW)

#### MUST HAVE (Mandatory for MVP - v1.0)
* **Secure Authentication:** Registration and Login (JWT). Users have a private area and can only view their own data.
* **Collection Management (CRUD):** Add, edit, list, and remove books (Title, Author, Genre, Cover).
* **Status Tracking:** Classify books as: `WANT TO READ`, `READING`, `READ`, `ABANDONED`, and `WISHLIST`.
* **Reading Diary (Notes):** Users can add multiple notes to the same book (e.g., recording a remarkable event, a quote, or the feeling of that moment), building a reading history.
* **Rating:** Ability to assign a rating (e.g., 1 to 5 stars) to a book.
* **Responsiveness and Accessibility:** Fluid web interface for mobile and PC, with screen reader support and 100% keyboard navigation (focus on a11y).

#### SHOULD HAVE (Important, but planned for v2.0)
* **Custom Collections:** Create custom tags/folders to group books (e.g., "All-Time Favorites", "Science Fiction", "Read in 2026").
* **Statistics Dashboard:** Profile overview (e.g., how many books were read in the year, most read authors).

#### COULD HAVE (Technical differential - v2.5)
* **External API Search:** Automatic filling of book metadata (cover, author, etc.) by consuming the Google Books API using the ISBN.
* **Dark Mode:** Light/dark theme toggle in the interface.

#### WON'T HAVE (Out of scope - We won't do)
* Social network, friends feed, or public comments.
* Book lending system between users.
* Native Mobile Application (iOS/Android).