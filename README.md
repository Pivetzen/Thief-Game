# 👮‍♂️ Police vs Thief - Strategy Game

Um jogo de estratégia abstrata baseado em turnos, inspirado em jogos clássicos de tabuleiro como *Alquerque* e o *Jogo da Onça*. O projeto foi desenvolvido para ser executado diretamente no navegador via **GitHub Pages**.

## 🎮 Como Jogar

O objetivo do jogo depende do lado que você está controlando:

* **Policiais (👮):** Devem cercar o ladrão para que ele não tenha mais movimentos válidos.
* **Ladrão (🥷):** Deve atravessar o cerco e chegar à linha superior (nível 0) para escapar.

### Regras:
1. Os jogadores se alternam em turnos.
2. Cada peça só pode se mover para um ponto vazio que esteja conectado por uma linha.
3. Não é permitido pular peças ou ocupar o mesmo espaço.

## 🚀 Demonstração

Você pode jogar a versão estável aqui:
> **Link:** [https://Pivetzen.github.io/Thief-Game/](https://Pivetzen.github.io/Thief-Game/)

## 🛠️ Tecnologias Utilizadas

* **HTML5 & CSS3:** Estrutura e estilização da interface.
* **JavaScript (Canvas API):** Renderização do tabuleiro, lógica de movimentação, conexões dinâmicas e condições de vitória.
* **GitHub Pages:** Hospedagem gratuita e rápida.

## ⚙️ Funcionalidades Especiais

* **Tabuleiro Dinâmico:** O usuário pode definir a quantidade de níveis (linhas) do tabuleiro, e o jogo gera automaticamente os pontos e as conexões por proximidade.
* **Lógica de Grafo:** O sistema utiliza um grafo para validar se um movimento entre dois pontos é permitido.

## 📥 Como rodar localmente

Se quiser testar em sua máquina:

1. Clone o repositório:
   ```bash
   git clone [https://github.com/Pivetzen/Thief-Game.git](https://github.com/Pivetzen/Thief-Game.git)
