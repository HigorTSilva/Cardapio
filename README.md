# 🍔 BurguerTopia — Cardápio Digital com Pedido via WhatsApp

![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![HTML](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat&logo=javascript&logoColor=black)

> Cardápio digital responsivo para restaurantes e lanchonetes. O cliente monta o pedido, informa o endereço de entrega e finaliza diretamente pelo WhatsApp com a mensagem já formatada.

---

## 📸 Preview

| Cardápio | Carrinho |
|---|---|
| ![Menu](./.github/preview-menu.png) | ![Cart](./.github/preview-cart.png) |

---

## ✨ Funcionalidades

- 📋 **Cardápio completo** com nome, descrição, foto e preço de cada item
- 🛒 **Carrinho dinâmico** — adicione e remova itens em tempo real
- 🔢 **Contador de itens** visível na barra inferior fixa
- 💰 **Total automático** atualizado a cada alteração no carrinho
- 📍 **Campo de endereço de entrega** integrado ao modal do carrinho
- 💬 **Envio automático para WhatsApp** com mensagem já formatada (itens, quantidades, preços e endereço)
- 📱 **Layout responsivo** para desktop e dispositivos móveis

---

## 🔄 Fluxo do Pedido

```
1. Cliente navega pelo cardápio
        ↓
2. Clica no ícone 🛒 para adicionar itens
        ↓
3. Barra inferior exibe a quantidade total
        ↓
4. Cliente abre "Meu Carrinho"
        ↓
5. Revisa os itens e pode remover se quiser
        ↓
6. Digita o endereço de entrega
        ↓
7. Clica em "Finalizar Pedido"
        ↓
8. Redirecionado ao WhatsApp com a mensagem pronta ✅
```

---

## 💬 Exemplo de Mensagem no WhatsApp

```
Olá! Gostaria de fazer o seguinte pedido:

🍔 Cheddar Bacon — Qtd: 1 — R$ 32,90
🍗 Frango Grelhado — Qtd: 1 — R$ 12,90
🥤 Coca Lata — Qtd: 1 — R$ 5,00

💰 Total: R$ 50,80

📍 Endereço de entrega: Rua das Flores, 123, Petrópolis - RJ
```

---

## 🗂️ Estrutura do Projeto

```
burguertopia/
├── index.html          # Estrutura principal da página
├── style.css           # Estilos e responsividade
├── script.js           # Lógica do carrinho e integração WhatsApp
├── assets/
│   └── images/         # Imagens dos produtos
└── README.md
```

---

## 🚀 Como Usar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/burguertopia.git
cd burguertopia
```

### 2. Configure o número do WhatsApp

No arquivo `script.js`, altere a variável com o número do restaurante:

```js
const WHATSAPP_NUMBER = "5521999999999"; // DDI + DDD + número
```

### 3. Abra no navegador

Basta abrir o `index.html` diretamente no navegador ou servir com qualquer servidor estático:

```bash
# Com Live Server (VS Code) ou:
npx serve .
```

> Nenhuma dependência ou instalação necessária. Projeto 100% HTML, CSS e JavaScript puro.

---

## ⚙️ Personalização

| O que mudar | Onde |
|---|---|
| Nome e endereço do restaurante | `index.html` — seção do header |
| Itens do cardápio (nome, preço, foto) | `index.html` — cards do menu |
| Horário de funcionamento | `index.html` — badge do header |
| Número do WhatsApp | `script.js` — constante `WHATSAPP_NUMBER` |
| Cores e fontes | `style.css` — variáveis CSS no `:root` |

---

## 🛠️ Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — layout, modal e responsividade
- **JavaScript (Vanilla)** — manipulação do DOM, lógica do carrinho e geração do link WhatsApp via [API wa.me](https://wa.me)

---

## 📄 Licença

Este projeto está sob a licença [MIT](./LICENSE). Sinta-se à vontade para usar, modificar e distribuir.

---

<p align="center">Feito com ❤️ para facilitar pedidos de delivery</p>
