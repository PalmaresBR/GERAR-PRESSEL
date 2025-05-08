# Pressel Generator Web Component

Um pequeno **Web Component** (`<pressel-generator>`) para gerar, de forma segura e estilizada, o HTML/CSS/JS de um “pressel” (popup de cookies) com:

- **Validação** automática de URL de afiliado (`http`/`https`).
- **Camuflagem** da URL de imagem de fundo (via Base64).
- Botões **Gerar**, **Copiar Código** e **Limpar** — sem recarregar a página.
- **Animação** suave de fade-in/fade-out para o popup.
- Meta tags para **impedir tradução** automática do Google Translate.

---

## 🚀 Instalação

Basta copiar o snippet abaixo para o seu HTML (por exemplo, num bloco de _Custom HTML_ do WordPress ou em qualquer página estática):

```html
<pressel-generator></pressel-generator>

<script type="module">
  // Cole aqui a classe PresselGenerator completa...
</script>
