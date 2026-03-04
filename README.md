# 🍔 BurguerTopia — Cardápio Digital com Pedido via WhatsApp

![HTML](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat&logo=javascript&logoColor=black)

> Cardápio digital responsivo para restaurantes e lanchonetes. O cliente monta o pedido, informa o endereço de entrega e finaliza diretamente pelo WhatsApp com a mensagem já formatada.

---

## 📸 Preview

| Cardápio | Carrinho |
|---|---|
| ![Menu](./.github/Cardapio.png) | ![Cart](./.github/FinalizarPedido.png) |

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

## 🛠️ Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — layout, modal e responsividade
- **JavaScript (Vanilla)** — manipulação do DOM, lógica do carrinho e geração do link WhatsApp via [API wa.me](https://wa.me)
