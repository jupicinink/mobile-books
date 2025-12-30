# 📚 MobileBooks

Landing page **estática e responsiva**, desenvolvida como projeto de estudo para praticar **HTML e CSS**, com foco em **layout responsivo**, **semântica**, **organização de estilos** e **componentes visuais modernos**.

O projeto simula uma livraria digital fictícia chamada **MobileBooks**, pensada para oferecer uma boa experiência em **dispositivos móveis, tablets e desktops**.

---

## 🎯 Objetivo do Projeto

- Praticar **HTML e CSS puro**, utilizando:
  - Flexbox
  - Grid
  - Breakpoints responsivos
- Aplicar **HTML semântico** para melhor organização e acessibilidade.
- Trabalhar com **CSS modularizado**, separando estilos por responsabilidade.
- Integrar bibliotecas externas leves (ex.: **Swiper.js**).
- Criar uma página estática com aparência profissional para **portfólio e estudo**.

---

## ✨ O que o projeto oferece

- 📌 **Landing page completa**, contendo:
  - Cabeçalho responsivo com menu tipo **hambúrguer**
  - Banner principal com campo de busca
  - Carrossel de lançamentos
  - Cards informativos
  - Seção de tópicos visitados recentemente
  - Área de inscrição por e-mail
  - Rodapé simples e funcional
- 🎨 **Estilos organizados por módulos**, facilitando manutenção e aprendizado
- 🔤 Uso de **Google Fonts**
- 🖼️ Imagens e ícones organizados em pasta dedicada

---

## 🛠️ Destaques Técnicos

- ✅ HTML semântico (`header`, `section`, `footer`, `ul`, `input`, etc.)
- ✅ CSS separado por responsabilidade:
  - reset
  - estilos globais
  - componentes
- ✅ Carrossel implementado com **Swiper (via CDN)**
  - Navegação
  - Paginação
  - Loop
- ✅ Meta tag `viewport` configurada corretamente
- ✅ Compatível com diferentes tamanhos de tela

---

## 📁 Estrutura do Repositório

text
├── index.html
├── styles/
│   ├── reset.css
│   ├── styles.css
│   ├── header.css
│   ├── banner.css
│   ├── carrosel.css
│   └── topicos.css
├── img/
│   └── (imagens e ícones do projeto)
└── README.md

🌐 **Acesse o projeto online (GitHub Pages):**  
👉 https://jupicinink.github.io/mobile-books/

---
## ▶️ Como abrir e testar localmente

### Opção 1 — Abrir diretamente
1. Abra o arquivo `index.html` no navegador.
2. Recomendado usar **Chrome**, **Firefox** ou **Edge**.

---

### Opção 2 — Servidor local 

cd /home/cpd10/Documentos/JuliaWorkplace/Cursos_Julia/mobile-books
python3 -m http.server 8000

Acesse:  
👉 http://localhost:8000

---

### Opção 3 — VS Code + Live Server
1. Instale a extensão **Live Server**.
2. Clique com o botão direito em `index.html`.
3. Selecione **Open with Live Server**.

---

## 📱 Responsividade e Breakpoints

- 📲 **Mobile (320–480px)**  
  Layout em coluna e menu hambúrguer

- 📟 **Tablet (481–768px)**  
  Grid simples e carrossel com menos itens

- 🖥️ **Desktop (>768px)**  
  Visual completo com mais itens por slide

---

## 🚀 Possíveis Melhorias Futuras

- Converter imagens para **WebP** com fallback
- Adicionar **lazy-loading** (`loading="lazy"`)
- Melhorar formulários (validação e feedback visual)
- Implementar **internacionalização (i18n)**
- Automatizar build com **Vite** ou **Parcel**
- Minificação de CSS e assets

---

## 👩‍💻 Autora

**Julia Picinini**  
Estudante de Engenharia de Software  
Projeto de estudos e portfólio