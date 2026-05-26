# Projeto — Landing Page com Tailwind CSS

## Objetivo

Desenvolver uma landing page moderna e responsiva de um produto da escolha de vocês utilizando Tailwind CSS.

O foco principal da atividade é praticar:

- Responsividade
- Flexbox/Grid
- Espaçamento
- Organização visual
- Hierarquia de texto
- Componentização visual
- Utilização de utility classes

---

# Requisitos Obrigatórios

A página tem como pré-requisitos mínimos:

- Navbar
- Hero Section
- Pelo menos 3 seções principais
- Cards ou elementos organizados em Grid/Flex
- Footer
- Responsividade para mobile e desktop
- Hover effects/transitions
- Paleta de cores consistente

Vocês podem adicionar outros itens que vocês queiram, sejam criativos :D

Note que esse repositório JÁ INCLUI o Tailwind CSS já configurado, vocês devem somente alterar o `index.html`.

---

# Exemplos

A landing page pode ser sobre qualquer produto, plataforma ou serviço fictício.

Exemplos:

- Plataforma de IA
- Dashboard SaaS
- VPN/Cybersecurity
- Produto gamer
- Streaming
- Ferramenta de produtividade
- Aplicativo mobile
- Loja virtual
- Startup futurista
- Plataforma de estudos

---

# Sobre o Tailwind CSS

O Tailwind CSS é um framework CSS utility-first.

Diferente do CSS tradicional, onde você cria classes próprias:

```css
.card {
  padding: 16px;
  background: black;
}
```

No Tailwind você utiliza classes utilitárias diretamente no HTML:

```html
<div class="p-4 bg-black rounded-xl">
```

Cada classe representa uma única responsabilidade:

- `p-4` → padding
- `bg-black` → background
- `rounded-xl` → bordas arredondadas

Isso acelera muito a construção de interfaces modernas e evita a necessidade de arquivos CSS gigantescos e difíceis de manter.

Segue abaixo o processo de instalação do Tailwind CSS.

---

## Instalação

Para aqueles que se perderam durante a aula, segue aqui um guia de instalação de como instalar o Tailwind CSS utilizando Vite.

```bash
npm create vite@latest (nome do diretório do seu projeto)
```

---

# Entre no diretório do seu projeto

```bash
cd (nome do seu projeto)
```

---

# Instale as dependências do Tailwind CSS

```bash
npm install tailwindcss @tailwindcss/vite
```

---

# No arquivo style.css, remova todo o conteúdo e deixe somente

```css
@import "tailwindcss";
```

---

# Crie o arquivo vite.config.js com o seguinte conteúdo

```js
import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'

export default defineConfig({
  plugins: [
    tailwindcss(),
  ],
})
```

---

# Delete os arquivos ./src/counter.js

O arquivo `main.js` deve ser mantido, pois ele é utilizado pelo Vite para importar o `style.css`.

A estrutura do projeto deve ficar:

```txt
meu-projeto
|
|-- node_modules
|-- public
|-- src
|    |-- assets
|    |-- style.css
|    |-- main.js
|
|-- index.html
|-- package-lock.json
|-- package.json
|-- vite.config.js
```

---

## Executar ambiente de desenvolvimento

O `npm run dev` deve estar SEMPRE rodando se você quer enxergar o seu site.

```bash
npm run dev
```

---

# Entrega

A entrega deve ser feita via GitHub Classroom até 29/05 às 23:59.

Façam commits frequentes e mantenham o código organizado.

Boa sorte :D
