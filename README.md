# 🎮 Jogo do Número Secreto

Projeto desenvolvido com foco em praticar lógica de programação utilizando JavaScript puro.

O objetivo do jogo é adivinhar um número secreto gerado aleatoriamente pelo sistema, recebendo dicas a cada tentativa até acertar.

---

## 📌 Demonstração do funcionamento

Ao iniciar o jogo, o usuário recebe uma mensagem de boas-vindas e deve escolher um número entre 1 e 100.

O sistema informa se o número secreto é maior ou menor que o chute até que o jogador acerte.

---

## 🚀 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript

---

## 🧠 Lógicas e conceitos aplicados

Durante o desenvolvimento foram praticados:

- Geração de números aleatórios (`Math.random`)
- Conversão de dados (`parseInt`)
- Estruturas condicionais (`if / else`)
- Estrutura de repetição (`while`)
- Operadores de comparação
- Template Strings
- Operador ternário
- Contador de tentativas
- Interação com usuário (`alert` e `prompt`)

---

## ⚙️ Funcionamento do código

### 1️⃣ Geração do número secreto

```javascript
let numeroSecreto = parseInt(Math.random() * 100 + 1);
