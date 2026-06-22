# 🚲 Localiza Bike — Protótipo Interativo

Protótipo navegável de um aplicativo de aluguel de bicicletas, construído em **HTML, CSS e JavaScript puro** (sem frameworks, sem dependências de build). Projeto de estudo de UX/UI.

## ✨ Demo

Abra o `index.html` no navegador ou hospede em qualquer serviço de páginas estáticas (GitHub Pages, Netlify, Vercel).

## 📱 Telas e fluxo

1. **Splash** — barra de progresso de 3s → Bem-vindo
2. **Bem-vindo** — "Começar" → Ativar Localização · "Já tenho conta" → Login
3. **Ativar Localização** — "Ativar" → Login · "Talvez mais tarde" → Bem-vindo
4. **Login** — qualquer botão (Entrar / Google / Apple / Facebook) → Seleção de Planos
5. **Seleção de Planos** — Diário / Mensal / Família → Confirmação (conteúdo dinâmico por plano)
6. **Confirmar Plano** — "Confirmar e Desbloquear" → Mapa · "X" → volta aos Planos
7. **Mapa** — clicar num pin de estação → Detalhes da Estação
8. **Detalhes da Estação** — botão voltar → Mapa

## 🎨 Design System

- **Cor primária:** Verde Localiza `#00843D`
- **Tipografia:** Inter
- Tokens de cor, espaçamento, border radius e tipografia aplicados de forma consistente

## 📂 Estrutura

```
índex.html      → protótipo completo (single file)
assets/         → logos, ilustrações e imagens das telas
```

## 🛠️ Tecnologias

- HTML5 · CSS3 (custom properties / design tokens) · JavaScript vanilla
- SVG inline para ícones · imagens otimizadas

---

Desenvolvido como estudo de UX/UI · Design base no Google Stitch, reconstruído em código.
