# 💖 Site "Nossa História"

Um site romântico feito para registrar histórias. Ideal para datas especiais como aniversários de namoro ou declarações de amor.

---

## ✨ Funcionalidades

- 🖼️ Carrossel de fotos carregado via repositório GitHub pessoal
- ⏱️ Contador em tempo real do tempo juntos (anos, meses, dias, horas, etc.)
- 💖 Efeitos visuais com brilhos e corações flutuantes
- 📅 Tema visual especial ativado automaticamente em datas comemorativas
- 🎥 Vídeo embutido com autoplay
- 📱 Layout responsivo para qualquer dispositivo

---

## 📁 Estrutura do Projeto

```

.
├── index.html               # Página principal
├── css/
│   └── style.css            # Estilos personalizados
├── js/
│   └── script.js            # Lógica principal e animações
├── img/
│   └── favicon.png          # Ícone da aba do navegador
└── README.md                # Você está aqui!

```

---

## 🔧 Tecnologias Utilizadas

- HTML5 e CSS3
- JavaScript moderno (ES6+)
- [Luxon](https://moment.github.io/luxon/#/) para manipulação de datas
- [Swiper.js](https://swiperjs.com/) para o carrossel de imagens
- Google Fonts (`Pacifico`, `Quicksand`)
- CDN pessoal do GitHub para carregar imagens

---

## 🖼️ Como adicionar novas fotos

O projeto está preparado para escalar automaticamente com novas imagens.

> ⚠️ **Importante:** As imagens usadas estão hospedadas em um repositório **pessoal**. Outros usuários precisarão criar o próprio repositório e ajustar o caminho no script.

### Passo a passo para adaptar:

1. Hospede suas imagens em seu próprio repositório GitHub (ex: `username/static-assets`).
2. No arquivo `script.js`, altere a constante `GITHUB_BASE` com a nova URL base:
   ```js
   const GITHUB_BASE = "https://raw.githubusercontent.com/seu-usuario/seu-repo/main/caminho/para/imagens/";

3. Atualize o array `imageNames` com os nomes dos arquivos:

   ```js
   const imageNames = ["1.jpg", "2.jpg", "3.jpg"];
   ```

---

## 📅 Sobre as datas comemorativas

A data inicial do relacionamento é configurada no topo do `script.js`:

```js
const startDateISO = "2025-06-01T00:00:00";
```

O site detecta automaticamente:

* 🗓️ **Aniversário mensal**: mesmo dia
* 🎉 **Aniversário anual**: mesmo dia e mês

Em ambas as ocasiões, o tema visual muda e efeitos de corações flutuantes são ativados.

---

## 💡 Ideias para melhorias futuras

* 🎶 Música romântica de fundo com controle de volume
* 📝 Legendas personalizadas por foto
* 📜 Linha do tempo interativa com eventos especiais
* 🧠 Modo memória: permitir escrever e salvar lembranças (localStorage)

---

## 📌 Licença

Este projeto foi criado por [@isousa.x](https://www.instagram.com/isousa.x/).
Sinta-se livre para se inspirar e adaptar para sua própria história de amor, criando sua versão personalizada! 💕

---
