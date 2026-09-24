# CineMundo — Portal de Cinema

## Sobre o projeto

O **CineMundo** é um portal de cinema desenvolvido como projeto individual para a disciplina de desenvolvimento web.

A proposta do projeto é criar um espaço simples e organizado para reunir informações relacionadas ao cinema, apresentando filmes, notícias e informações sobre o próprio portal.

A **Versão 1** foi desenvolvida utilizando somente **HTML e CSS**, com foco na estrutura das páginas, organização do conteúdo, identidade visual, navegação e responsividade.

---

## Tema e justificativa

O tema escolhido para o projeto foi **cinema**, por ser um assunto amplo e que permite trabalhar diferentes tipos de conteúdo em um mesmo portal, como filmes, notícias e informações relacionadas ao universo cinematográfico.

A escolha também possibilita desenvolver uma interface visual que utilize imagens, cards, destaques e diferentes seções, permitindo aplicar conceitos de HTML semântico, CSS, Flexbox e responsividade.

O objetivo é criar uma experiência simples para que o usuário consiga navegar pelo portal e encontrar diferentes conteúdos relacionados ao cinema.

---

## Público-alvo

O CineMundo é destinado principalmente a:

* pessoas interessadas em cinema;
* estudantes e jovens que gostam de filmes;
* pessoas que procuram informações sobre lançamentos;
* usuários que desejam conhecer diferentes filmes e notícias do cinema.

O portal foi pensado para ser simples de utilizar, com navegação direta e conteúdo organizado em diferentes páginas.

---

## Objetivos do projeto

### Objetivo geral

Desenvolver um portal web sobre cinema utilizando HTML e CSS, aplicando conceitos de estrutura semântica, organização de conteúdo, identidade visual, Flexbox e responsividade.

### Objetivos específicos

* Criar uma estrutura de navegação entre diferentes páginas;
* Apresentar filmes de forma organizada;
* Criar uma seção de notícias sobre cinema;
* Desenvolver uma página de contato;
* Utilizar HTML semântico;
* Aplicar CSS para criar uma identidade visual consistente;
* Utilizar Flexbox na construção dos layouts;
* Adaptar o portal para diferentes tamanhos de tela;
* Planejar funcionalidades futuras para uma segunda versão utilizando JavaScript.

---

# Mapa de páginas

O portal possui quatro páginas principais:

```text
CineMundo
│
├── Início (index.html)
│   ├── Destaque
│   ├── Filmes em destaque
│   └── Sobre o CineMundo
│
├── Filmes (filmes.html)
│   └── Lista de filmes
│
├── Notícias (noticias.html)
│   └── Notícias sobre cinema
│
└── Contato (contato.html)
    └── Formulário de contato
```

### Página inicial

**Arquivo:** `index.html`

Apresenta o portal e funciona como ponto de entrada para o usuário. Possui uma área de destaque, filmes em destaque e uma breve apresentação do CineMundo.

### Página de filmes

**Arquivo:** `filmes.html`

Apresenta filmes organizados em cards, contendo imagem, título, ano e duração.

### Página de notícias

**Arquivo:** `noticias.html`

Apresenta notícias relacionadas ao cinema, organizadas em artigos com imagem, título, conteúdo e data.

### Página de contato

**Arquivo:** `contato.html`

Apresenta informações de contato e um formulário visual para que o usuário possa preencher nome, e-mail, assunto e mensagem.

> Na Versão 1, o formulário possui apenas a interface visual. O envio e o processamento dos dados serão planejados para a Versão 2.

---

# Wireframe / protótipo

O projeto foi planejado considerando uma estrutura simples e consistente entre as páginas.

## Estrutura geral

```text
┌──────────────────────────────────────────────┐
│                  CINEMUNDO                   │
│  Início   Filmes   Notícias   Contato        │
├──────────────────────────────────────────────┤
│                                              │
│              ÁREA DE DESTAQUE               │
│                                              │
│       O mundo do cinema em um só lugar      │
│                                              │
│              [ Explorar filmes ]             │
│                                              │
├──────────────────────────────────────────────┤
│              FILMES EM DESTAQUE             │
│                                              │
│    ┌────────┐   ┌────────┐   ┌────────┐    │
│    │ Imagem │   │ Imagem │   │ Imagem │    │
│    │        │   │        │   │        │    │
│    ├────────┤   ├────────┤   ├────────┤    │
│    │ Título │   │ Título │   │ Título │    │
│    │ Texto  │   │ Texto  │   │ Texto  │    │
│    └────────┘   └────────┘   └────────┘    │
│                                              │
├──────────────────────────────────────────────┤
│                 SOBRE O SITE                 │
│                                              │
│              Texto explicativo               │
│                                              │
├──────────────────────────────────────────────┤
│                    RODAPÉ                    │
└──────────────────────────────────────────────┘
```

As demais páginas seguem a mesma identidade visual, utilizando cabeçalho, navegação, conteúdo principal e rodapé.

---

# Tecnologias utilizadas

A Versão 1 utiliza somente:

* **HTML**
* **CSS3**

Não foi utilizado JavaScript na implementação da Versão 1.

---

# HTML semântico

O projeto utiliza elementos semânticos do HTML5 para organizar o conteúdo e melhorar a estrutura das páginas.

Entre os elementos utilizados estão:

* `<header>`
* `<nav>`
* `<main>`
* `<section>`
* `<article>`
* `<footer>`

A utilização desses elementos permite separar melhor as diferentes partes do conteúdo e torna a estrutura das páginas mais organizada.

---

# Identidade visual

O CineMundo utiliza uma identidade visual baseada em uma temática cinematográfica, com fundo escuro e uma cor de destaque em tons de amarelo/dourado.

A identidade visual é mantida nas diferentes páginas por meio de:

* mesma paleta de cores;
* mesma tipografia;
* cabeçalho padronizado;
* menu de navegação consistente;
* cards com o mesmo estilo;
* botões padronizados;
* rodapé compartilhado.

Os estilos foram organizados em arquivos CSS separados para facilitar a manutenção do projeto.

---

# Organização dos arquivos


portal-cinema/
│
├── index.html
├── filmes.html
├── noticias.html
├── contato.html
│
├── css/
│   ├── reset.css
│   ├── global.css
│   ├── home.css
│   ├── filmes.css
│   ├── noticias.css
│   └── contato.css
│
├── img/
│   ├── destaque.jpg
│   ├── filme1.webp
│   ├── filme2.webp
│   ├── filme3.webp
│   └── filme4.webp
│
└── README.md


### Organização dos arquivos CSS

O projeto possui um CSS global e um CSS específico para cada página.

* `reset.css` — reseta estilos padrão do navegador.
* `global.css` — contém estilos compartilhados entre as páginas.
* `home.css` — estilos específicos da página inicial.
* `filmes.css` — estilos específicos da página de filmes.
* `noticias.css` — estilos específicos da página de notícias.
* `contato.css` — estilos específicos da página de contato.

Essa organização permite manter os estilos separados de acordo com a função de cada página.

---

# Layout e Flexbox

O projeto utiliza **Flexbox** para construir e organizar diferentes partes da interface.

Entre os elementos que utilizam Flexbox estão:

* cabeçalho;
* menu de navegação;
* cards de filmes;
* área de notícias;
* seção de contato;
* rodapé;
* organização de conteúdos em diferentes tamanhos de tela.

O uso de Flexbox permite que os elementos se reorganizem de acordo com o espaço disponível.

---

# Responsividade

O CineMundo foi desenvolvido pensando em diferentes tamanhos de tela.

Foram utilizadas media queries no CSS para adaptar o layout principalmente para:

* computadores;
* tablets;
* smartphones.

Em telas menores, os elementos são reorganizados para facilitar a leitura e a navegação.

Entre as adaptações realizadas estão:

* reorganização do cabeçalho;
* quebra do menu de navegação;
* alteração da disposição dos cards;
* reorganização das notícias;
* ajuste dos tamanhos das imagens;
* redução dos tamanhos de títulos;
* adaptação do formulário de contato.

---

# Navegação

As páginas possuem um menu de navegação que permite acessar as diferentes áreas do portal.

```text
Início → index.html
Filmes → filmes.html
Notícias → noticias.html
Contato → contato.html
```

A navegação é realizada por links HTML, sem utilização de JavaScript.

---

# Conteúdo do portal

O CineMundo possui conteúdos relacionados diretamente ao tema escolhido.

### Filmes

A página de filmes apresenta:

* Uma Grande Jornada;
* Além do Universo;
* Novos Caminhos;
* Um Dia Inesperado.

Cada filme possui informações como título, ano e duração.

### Notícias

A página de notícias apresenta conteúdos relacionados ao universo do cinema, organizados em artigos individuais.

### Contato

A página de contato possui um formulário com campos para:

* nome;
* e-mail;
* assunto;
* mensagem.

---

# Versão 2 — Funcionalidades planejadas

A Versão 2 será utilizada para adicionar funcionalidades com **JavaScript**.

Essas funcionalidades serão apenas planejadas nesta etapa e **não fazem parte da implementação da Versão 1**.

## 1. Pesquisa de filmes

Adicionar um campo de pesquisa para permitir que o usuário procure filmes pelo nome.

Exemplo:

```text
Pesquisar filme: [________________] [Pesquisar]
```

O JavaScript poderá verificar o texto digitado e mostrar somente os filmes correspondentes.

---

## 2. Filtro de filmes

Adicionar filtros para facilitar a busca de filmes.

Possíveis filtros:

* gênero;
* ano;
* duração.

O usuário poderá selecionar um filtro e visualizar apenas os filmes correspondentes.

---

## 3. Sistema de favoritos

Adicionar uma opção para o usuário marcar filmes como favoritos.

O JavaScript poderá armazenar os filmes selecionados no navegador utilizando `localStorage`.

---

## 4. Validação do formulário

Implementar validação no formulário de contato.

O JavaScript poderá verificar:

* preenchimento dos campos obrigatórios;
* formato do e-mail;
* tamanho da mensagem.

Também poderá apresentar mensagens informando ao usuário se algum campo precisa ser corrigido.

---

## 5. Interações nos cards

Adicionar interações aos cards de filmes, permitindo que o usuário clique em um filme para visualizar mais informações.

---

# Limitações da Versão 1

A Versão 1 possui somente a estrutura e a interface visual do portal.

Por isso:

* o formulário de contato não envia mensagens;
* a pesquisa de filmes ainda não está implementada;
* os filtros ainda não funcionam;
* o sistema de favoritos ainda não existe;
* os cards não possuem interação dinâmica;
* não há armazenamento de informações no navegador.

Essas funcionalidades estão planejadas para a Versão 2.

---

# Publicação

O projeto será publicado utilizando **GitHub Pages**, permitindo acessar o CineMundo diretamente pelo navegador.

Link do projeto:

**https://brunahenz.github.io/portal-cinema/**

---

# Conclusão

O CineMundo foi desenvolvido como uma primeira versão de um portal de cinema, aplicando conceitos de HTML e CSS.

A versão atual apresenta estrutura semântica, navegação entre páginas, identidade visual consistente, uso de Flexbox, conteúdo contextualizado e responsividade.

As funcionalidades que dependem de JavaScript foram mantidas como planejamento para a Versão 2, conforme os requisitos do projeto.
