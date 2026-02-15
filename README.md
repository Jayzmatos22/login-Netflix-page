# 🍿 Netflix Clone - Cadastro & Login

Um projeto de interface (UI) inspirado na Netflix, focado inteiramente em **CSS Vanilla** (CSS puro), sem a utilização de frameworks como Tailwind. O objetivo foi aplicar conceitos de posicionamento, estilização de formulários e micro-interações.



## 🎯 Desafios Superados

Neste projeto, foquei em resolver problemas comuns de CSS:
- **Sobreposição de camadas:** Uso de `linear-gradient` múltiplo sobre imagem de fundo.
- **Micro-interações:** Efeitos de `hover` dinâmicos que alteram a cor e a posição dos elementos.
- **Estilização de Inputs:** Customização completa de campos de texto e senha para fugir do padrão do navegador.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica com `header` e `main`.
* **CSS3 (Puro):** * **Flexbox:** Para organização dos elementos internos.
    * **Transitions:** Para suavizar as mudanças de estado (1.7s e 3s nos hovers).
    * **Transforms:** Para o efeito de deslocamento lateral (`translateX`).
    * **Gradients:** Manipulação de cores `rgba` para criar o efeito de sombra sobre a imagem.

## 🚀 Efeitos em Destaque

### 1. Deslocamento do Botão
O botão "Entrar" não apenas muda de cor para verde, mas também se desloca 20px para a direita de forma suave:
```css
.btn-entrar {
    transition: transform 0.8s ease;
}

.btn-entrar:hover {
    transform: translateX(20px);
}