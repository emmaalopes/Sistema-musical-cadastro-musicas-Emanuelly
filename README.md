# 🎵 Sistema Musical

Um sistema web completo para gerenciamento de artistas, álbuns e biblioteca musical. O projeto conta com uma interface responsiva, moderna e padronizada, desenvolvida em HTML5 e CSS3.

---

## 📌 Índice

- [Visão Geral](#-visão-geral)
- [Funcionalidades](#-funcionalidades)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como Executar o Projeto](#-como-executar-o-projeto)
- [Próximos Passos (Sprint 2)](#-próximos-passos-sprint-2)

---

## 🎧 Visão Geral

O **Sistema Musical** permite autenticar utilizadores e gerir coleções de música. O painel principal oferece acesso rápido para cadastrar artistas, inserir novas músicas e navegar por uma biblioteca musical completa com suporte a filtros e visualização de dados.

---

## 🚀 Funcionalidades

### 🔐 1. Tela de Login (`login.html`)
- Formulário centralizado de autenticação.
- Campos para **Usuário** e **Senha** com validações nativas do HTML5 (`required`, `autocomplete`).
- Caixas de dicas com credenciais de teste (`admin` / `123`).

### 🏠 2. Menu Principal (`index.html`)
- Painel de controlo principal com visualização em grelha (*grid*).
- Boas-vindas personalizadas ao utilizador.
- Links rápidos para navegar entre as secções:
  - **Gerenciar Artistas**
  - **Cadastrar Músicas**
  - **Biblioteca Musical**
- Botão de navegação para **Sair** (*logout*).

### 🎤 3. Cadastro de Artistas (`cadastro_artista.html`)
- Formulário em grelha de duas colunas para inserção de:
  - Nome do Artista (Obrigatório)
  - Gênero Musical
  - País de origem
  - Foto do Artista (suporte a upload `JPG` / `PNG` até 5MB)
- Tabela integrada para listar, editar, eliminar e aceder diretamente às músicas cadastradas do artista.

### 🎵 4. Cadastro de Músicas (`cadastro_musica.html`)
- Inserção detalhada de músicas com os seguintes campos:
  - Artista (Menu de seleção encadeado)
  - Título (Obrigatório)
  - Álbum e Gênero Musical (Opcionais)
  - Link do YouTube (Validação do URL)
  - Capa do Álbum
  - Letra da Música (Caixa de texto expandida)
- Tabela integrada exibindo as músicas cadastradas e botão direto para assistir ao vídeo no YouTube.

### 🎼 5. Biblioteca Musical (`listagem_musicas.html`)
- Tabela completa de exibição da coleção musical.
- Filtros dinâmicos por **Busca Geral** (Título, Álbum, Artista), **Artista** e **Gênero**.
- Ações rápidas em cada registo (Editar, Eliminar e Link de reprodução externa no YouTube em nova aba).

---
