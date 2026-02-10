# 🌧️ Canvas Matrix - Chuva de Código

![Preview](src/img/previw.png)

Uma animação inspirada no icônico efeito de "chuva de código" do filme Matrix, criada com HTML5 Canvas e JavaScript puro.

---

O projeto exibe uma chuva infinita de números (0-9) em verde neon, cascateando pela tela com o efeito de rastro característico do filme Matrix.

## ✨ Características

- ✅ Animação fluida em 60 FPS
- ✅ Efeito de rastro semitransparente
- ✅ Responsivo - ajusta-se automaticamente ao tamanho da tela
- ✅ Sem dependências externas
- ✅ Código limpo e comentado
- ✅ Personalização fácil

## 🚀 Como Usar

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/canvas-matrix.git
```

2. Abra o arquivo `index.html` diretamente no navegador:

````bash

Você pode facilmente personalizar o efeito editando as variáveis no código:

```javascript
// Alterar os caracteres exibidos
const letters = "0123456789".split("");  // Troque por letras, símbolos, etc.

// Ajustar o tamanho da fonte
const fontSize = 18;  // Valores maiores = caracteres maiores

// Modificar a cor
ctx.fillStyle = "#0F0";  // #0F0 = verde, experimente outras cores

// Velocidade da animação
setInterval(draw, 40);  // Valores menores = mais rápido

// Opacidade do rastro
ctx.fillStyle = "rgba(0, 0, 0, 0.1)";  // Aumente 0.1 para rastros mais curtos
````

## 🛠️ Tecnologias

- HTML5 Canvas
- JavaScript (ES6+)
- CSS3

## 💡 Como Funciona

1. **Canvas**: Cria um canvas que ocupa toda a tela
2. **Colunas**: Divide a tela em colunas baseadas no tamanho da fonte
3. **Gotas**: Cada coluna tem uma "gota" que cai continuamente
4. **Rastro**: Um retângulo semitransparente preto cria o efeito de fade
5. **Reset**: Quando uma gota atinge o fim, ela retorna ao topo aleatoriamente

## 📱 Compatibilidade

Funciona em todos os navegadores modernos que suportam HTML5 Canvas:

- ✅ Chrome/Edge
- ✅ Firefox
- ✅ Safari
- ✅ Opera

Autor: Elisson

---
