# 🐍 PySnake

O projeto foca na lógica de movimentação matricial, manipulação de inputs em tempo real e gerenciamento de estados de jogo.

## 🎮 Funcionalidades

- **Renderização no Terminal:** Interface gráfica feita inteiramente com caracteres ASCII usando a biblioteca `curses`.
- **Dificuldade Progressiva:** Sistema de seleção de nível (1 a 5) que ajusta a velocidade do jogo dinamicamente.
- **Sistema de Pontuação:** Score em tempo real ao coletar frutas.
- **Detecção de Colisão:** Lógica para colisão com bordas e com o próprio corpo da cobra.
- **Input Não-Bloqueante:** Movimentação fluida sem pausar o loop do jogo.

## 🚀 Como Rodar o Jogo

### Pré-requisitos
Certifique-se de ter o [Python](https://www.python.org/) instalado.

### Passo a Passo

1. **Clone o repositório e acesse a pasta no CMD:**
   `git clone https://github.com/lucas-abreu56/pysnake`
   `cd pysnake`
2. **Instale as dependências:** (Nota: O curses é nativo no Linux/Mac. Para Windows, é necessário instalar o pacote compatível):
   `pip install -r requirements.txt`
3. **Execute o jogo:**
   `python pysnake.py`

## 🕹️ Como Jogar

1. **Execute o script** no seu terminal.
2. Digite o nível de dificuldade desejado: (`1` = Lento, `5` = Rápido).
3. Use as **Setas do Teclado** (`⬆️` `⬇️` `⬅️` `➡️`) para mover a cobra.
4. O objetivo é comer a fruta (`♦`) para crescer e pontuar.
5. **Game Over:** O jogo acaba se você bater na **parede** ou no **próprio corpo**.
