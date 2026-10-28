# 🕒 Relógio Digital Minimalista

Um relógio digital elegante, minimalista e responsivo construído com tecnologias web puras. O projeto exibe a hora atualizada em tempo real, a data por extenso no formato local, o fuso horário do sistema e uma barra de progresso visual para os segundos.

---

## ✨ Demonstração Visual

- **Estilo:** Design limpo com paleta de cores moderna (tons pastéis e detalhes em verde-azulado).
- **Animações:** Indicadores de dois pontos (`:`) piscantes com tratamento para acessibilidade.

---

## 🚀 Funcionalidades

- **Hora em Tempo Real:** Sincronização precisa baseada na API nativa do JavaScript.
- **Alternador de Formato:** Botão dinâmico para alternar entre o formato de **24 horas** e **12 horas (AM/PM)**.
- **Detecção de Fuso Horário:** Identifica e exibe automaticamente o fuso horário configurado no dispositivo do usuário.
- **Data por Extenso:** Exibição da data local formatada nativamente com `Intl.DateTimeFormat`.
- **Barra de Progresso:** Linha visual inferior que se expande horizontalmente de acordo com a passagem dos segundos (0 a 60).
- **Acessibilidade:** Suporte a preferências do sistema operacional através da media query `prefers-reduced-motion` (pausa a animação dos dois pontos se o usuário preferir menos movimento).

---

## 📦 Estrutura do Projeto

O código está organizado em três arquivos principais simples de manter:

```text
├── index.html   # Estrutura semântica e esqueleto da aplicação
├── style.css    # Estilização moderna utilizando CSS Variables e Flexbox/Grid
└── script.js    # Lógica de atualização do tempo e manipulação de eventos do DOM
```

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica utilizando tags como `<main>`, `<time>` e `<button>`.
- **CSS3:** Layout estruturado com CSS Grid, Flexbox, fontes externas e responsividade fluida baseada na função `clamp()`.
- **JavaScript (ES6+):** Manipulação assíncrona do tempo através de otimização no loop do `setTimeout`.

---

## 🔧 Como Executar o Projeto Localmente

1. Clone o repositório em sua máquina:
   ```bash
   git clone https://github.com
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd seu-repositorio
   ```
3. Abra o arquivo `index.html` diretamente em qualquer navegador web ou utilize a extensão **Live Server** no VS Code.

---

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se livre para clonar, modificar e distribuir o código.

---
Desenvolvido com ☕ por Murillo (https://github.com)
