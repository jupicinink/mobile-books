// ...existing code...
# Alura Plus — Projeto estático (Mobile Books)

Pequena página estática construída como projeto de estudo para praticar HTML e CSS, com foco em layout responsivo, organização semântica e uso de componentes visuais (carrossel, cards, navegação). Este repositório contém uma landing page fictícia de uma livraria digital — "AluraBooks" — pensada para diferentes dimensões de tela.

## Objetivo do projeto
- Servir como exercício prático de HTML e CSS (flexbox, grid, responsividade).
- Demonstrar organização de folhas de estilo por módulos (reset, header, banner, carrossel, tópicos).
- Praticar integração com bibliotecas externas leves (ex.: Swiper para carrossel).
- Produzir uma página estática acessível e responsiva, adequada para estudo e referência.

## O que o projeto oferece
- Layout completo de uma página promocional com:
  - Cabeçalho responsivo com menu tipo "hamburger".
  - Banner com busca destacada.
  - Seções com carrossel de lançamentos e cards informativos.
  - Lista de tópicos visitados recentemente.
  - Área de inscrição por e-mail e rodapé simples.
- Estrutura modular de CSS para facilitar estudo e manutenção.
- Exemplo de uso de fontes do Google Fonts.
- Imagens e ícones organizados em pasta `img/`.

## Destaques técnicos
- HTML semântico: uso de header, section, footer, listas e inputs adequadamente.
- CSS modularizado: arquivos separados por responsabilidade (reset, header, banner, etc.).
- Carrossel implementado com Swiper (CDN) e configuração básica para navegação, paginação e loop.
- Meta tag viewport configurada para boa renderização em dispositivos móveis.
- Compatível com várias larguras de tela (mobiles, tablets, desktops) através de breakpoints e estilos responsivos.

## Estrutura do repositório
- index.html — arquivo principal com toda a marcação da página.
- styles/
  - reset.css — reset básico de estilos.
  - styles.css — estilos globais e variáveis.
  - header.css — estilos do cabeçalho e navegação.
  - banner.css — estilos do banner de destaque.
  - carrosel.css — estilos do carrossel e cards laterais.
  - topicos.css — estilos da seção de tópicos.
- img/ — ativos de imagem utilizados na página.
- README.md — este documento.

## Como abrir e testar localmente

Opção 1 — Abrir diretamente
1. Abra `index.html` no navegador (duplo clique ou arraste para a janela do navegador).
2. Recomenda-se usar navegador moderno (Chrome, Firefox, Edge).

Opção 2 — Servir localmente (recomendado para evitar problemas com CORS/recursos)
- Usando Python (Linux):
  - No terminal, posicione-se na pasta do projeto:
    cd /home/cpd10/Documentos/JuliaWorkplace/Cursos_Julia/mobile-books
  - Rode:
    python3 -m http.server 8000
  - Acesse: http://localhost:8000

Opção 3 — VS Code + Live Server
- Instale a extensão Live Server.
- Clique com o botão direito em `index.html` -> "Open with Live Server".

## Responsividade e testes
- A página foi pensada para múltiplas larguras:
  - Mobile (320–480px): layout em coluna, menu hambúrguer.
  - Tablet (481–768px): grid simples, carrossel visível com menos itens por slide.
  - Desktop (>768px): visual completo com mais slides simultâneos.
- Teste responsividade:
  - Abra DevTools (F12) → Toggle device toolbar e selecione diferentes dispositivos.
  - Ajuste manualmente a largura da janela do navegador.
- Pontos para verificar:
  - Navegação acessível via teclado.
  - Contraste de texto sobre fundos (legibilidade).
  - Tamanhos de toque adequados em botões/links no mobile.

## Boas práticas e recomendações
- Separar ainda mais estilos por componente conforme o projeto cresce.
- Usar sprites ou SVG inline para ícones se otimizar tamanho e desempenho.
- Otimizar imagens (compressão) para reduzir tempo de carregamento.
- Implementar atributos alt descritivos (já presentes, revisar para melhorar acessibilidade).
- Adicionar testes manuais de acessibilidade (ex.: Lighthouse, axe).

## Possíveis melhorias
- Conversão das imagens para WebP e fornecer fallback.
- Lazy-loading de imagens (atributo loading="lazy").
- Melhorar formulários (validação e feedback).
- Internacionalização (idiomas).
- Automatizar build com uma ferramenta (parcel, vite) para minificação e live reload.

## Contribuição
Contribuições são bem-vindas. Fluxo sugerido:
1. Fork do repositório.
2. Criar branch com mudanças descritivas (ex.: feat/responsive-banner).
3. Fazer commits claros e pequenos.
4. Abrir Pull Request explicando a motivação e os testes feitos.

## Licença
Escolha a licença desejada e adicione aqui (ex.: MIT, Apache-2.0). Se preferir, mantenha como uso educacional apenas.

---

Autor: Julia Picinini  
Propósito: projeto de estudos e portfólio para