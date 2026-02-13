

# Simulador Mega-Sena Interativo

Este projeto é uma aplicação web que simula a experiência de realizar uma aposta na Mega-Sena. Ele permite que o usuário selecione seus números manualmente, valide a aposta e confira o resultado em tempo real.

## Funcionalidades Principais

* **Seleção de Números:** Interface amigável com botões numerados de 01 a 60 para escolha personalizada.
* **Sistema de Apostas:** Lógica para processar os números selecionados e compará-los com um sorteio gerado automaticamente.
* **Alternador de Tema (Dark Mode):** Inclui um interruptor (switch) que permite ao usuário alternar entre o modo claro e o modo escuro.
* **Resultados em Tempo Real:** Seção dedicada para exibir os números sorteados, a quantidade de números jogados e o total de acertos.
* **Reinicialização:** Botão "Reiniciar" para limpar o volante e começar um novo jogo rapidamente.

## Tecnologias Utilizadas

* **HTML5:** Estrutura semântica para o volante de apostas e controles.
* **CSS3:** Estilização moderna com suporte a temas e layout responsivo (CSS Grid/Flexbox).
* **JavaScript (ES6):** Gerenciamento da lógica de seleção de números, geração de números aleatórios para o sorteio e manipulação do DOM.

## Como Funciona a Aplicação

1. **Escolha:** O usuário clica nos botões numerados. A função `selecionarNumeros(n)` é disparada para registrar a escolha.
2. **Aposta:** Ao clicar em "Apostar", a função `apostar()` executa o sorteio oficial do sistema e valida os acertos do jogador.
3. **Feedback:** O rodapé da página é atualizado com o valor da aposta, quantidade de números e o desempenho final.
4. **Tema:** O checkbox no topo gerencia a troca de classes no CSS para alterar a paleta de cores global.

## Estrutura de Arquivos

* `index.html`: Página principal com a estrutura do simulador.
* `css/style.css`: Estilos visuais, incluindo o design dos botões e a lógica do slider de tema.
* `js/index.js`: Lógica JavaScript para interatividade e sorteio.

---

## Exemplo Visual do Tabuleiro

O código organiza os botões em grupos de 10, simulando o volante real da loteria:

```text
[01] [02] [03] [04] [05] [06] [07] [08] [09] [10]
[11] [12] [13] [14] [15] [16] [17] [18] [19] [20]
...
[51] [52] [53] [54] [55] [56] [57] [58] [59] [60]

<img width="818" height="692" alt="Image" src="https://github.com/user-attachments/assets/d950ca3b-cdb9-4ceb-af94-6c4d36705440" />
