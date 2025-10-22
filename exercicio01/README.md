

# 🐘 Introdução ao PHP — Exemplo Prático

Este repositório contém um exemplo simples de como integrar HTML com PHP usando um formulário básico.

A ideia é mostrar como o PHP pode ser usado para processar ações do usuário, como o clique em um botão, e retornar uma resposta dinâmica.

---

## 📂 Estrutura do Projeto

- `index.html`: Página principal com um formulário que envia uma requisição para o script PHP.
- `olamundo.php`: Script PHP que será executado quando o usuário clicar no botão.

---

## 💡 Como funciona

### 🔸 `index.html`

```html
<form action="olamundo.php" method="GET">
  <input type="submit" value="Executar PHP">
</form>
