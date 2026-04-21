# Personal Website (UFSC)

Projeto da disciplina **Programação para Web** do curso de **Sistemas de Informação (UFSC)**.

## 📁 Estrutura do projeto

- `index.html`: página principal estática com estrutura semântica.
- `style.css`: estilos da página (layout, cores, espaçamentos e responsividade).
- `img/`: imagem de perfil utilizada no `aside`.
- `icons/`: favicon da página.

## ✅ Requisitos atendidos

### 1) Arquivos principais
- `index.html` como arquivo principal.
- `style.css` como CSS externo vinculado por `<link>`.

### 2) Estrutura semântica obrigatória
- `<header>` com `<nav>` e links internos.
- `<aside>` com informações pessoais.
- `<main>` com conteúdo dividido em `<section>`.
- `<footer>` com `<address>` para contato.

### 3) Conteúdo mínimo
- Nome e foto.
- Curso com link para página do curso.
- Áreas de interesse.
- Linguagens de programação.
- Tecnologias.
- Link para GitHub.
- Seções obrigatórias:
  - Sobre mim
  - Interesses
  - Disciplinas cursadas
  - Projetos públicos (links externos)

### 4) Navegação interna
- Menu com âncoras para navegação entre seções (`#sobre`, `#interesses`, `#disciplinas`, `#projetos`).

### 5) Estilização com CSS
- Layout principal usando **CSS Grid** (`.layout`).
- Elementos de navegação usando **Flexbox** (`nav ul`).
- Estilização visual com cores, bordas, espaçamento, sombras e hover.

### 6) Responsividade
- Uso de **media query** (`@media (max-width: 900px)`).
- Reorganização do layout para uma coluna no mobile.
- Sidebar deixa de ser sticky no mobile para melhorar leitura.
- Ajustes para evitar overflow horizontal em links de projetos.

## ▶️ Como executar localmente

Basta abrir o arquivo `index.html` no navegador.

Opcionalmente, você pode servir via HTTP local:

```bash
python3 -m http.server 8000
```

Depois acesse: `http://localhost:8000`

## 🌐 Deploy

### Status atual
- **Concluído**: deploy realizado via **Vercel**.

### URL publicada
- `https://arthur-cichovski.vercel.app/`
