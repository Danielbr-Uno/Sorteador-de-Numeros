# 🎲 Sorteador de Números Aleatórios  

Este projeto é um **sorteador de números aleatórios em JavaScript**.  
Você define:  
- 🔢 A **quantidade** de números que deseja sortear  
- ⬇️ O número **mínimo**  
- ⬆️ O número **máximo**  

E o sistema faz a mágica acontecer! ✨  

---

## 🚀 Como funciona  

1. O usuário informa os valores:  
   - **Quantidade de números** a serem sorteados.  
   - O **intervalo** (de X até Y).  

2. O programa:  
   - Verifica se o valor mínimo é menor que o máximo.  
   - Confere se a quantidade não é maior que o intervalo disponível.  
   - Gera números **aleatórios e únicos** dentro do intervalo.  
   - Exibe o resultado em tela.  

---

---

## 📂 Estrutura de Arquivos  

- `index.html` → Interface do usuário 🖼️  
- `style.css` → Estilos 🎨  
- `script.js` → Lógica do sorteador ⚡  

---

## 🔑 Principais Funções  

- `sortear()` → Faz a validação e o sorteio dos números.  
- `gerarNumeroAleatorio(min, max)` → Cria um número aleatório dentro do intervalo.  
- `alterarStatusBotao()` → Habilita/desabilita o botão de reinício.  
- `reiniciar()` → Reseta os campos para começar um novo sorteio.  
