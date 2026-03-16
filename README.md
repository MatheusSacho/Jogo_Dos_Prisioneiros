# 🎩 Desafio dos Chapéus – Puzzle dos 100 Prisioneiros

Este é um simulador interativo do famoso puzzle lógico **100 Prisoners and Hats**.

Nesta versão o jogo foi adaptado para **20 prisioneiros** para facilitar a visualização.

## 🧠 Objetivo

Maximizar o número de sobreviventes.

Cada prisioneiro:

- usa um chapéu vermelho ou azul
- consegue ver apenas os chapéus à sua frente
- precisa dizer "vermelho" ou "azul"

Se acertar → sobrevive  
Se errar → morre

---

## 🎮 Modos de jogo

### Modo Normal
- Chapéus revelados após cada turno
- Histórico completo

### Modo Difícil
- Chapéus ocultos (❓)
- Apenas a última resposta aparece
- Necessário memorizar a lógica

---

## 🧩 Estratégia

O primeiro prisioneiro anuncia a **paridade** do número de chapéus vermelhos que ele vê:

- **Vermelho → número par**
- **Azul → número ímpar**

Isso transmite **1 bit de informação** para todos os outros prisioneiros.

Com essa informação e as respostas anteriores, os outros conseguem deduzir seu chapéu.

Resultado ideal:

- **19 prisioneiros garantidos**
- **1 prisioneiro com 50% de chance**

---

## 🚀 Como executar

Basta abrir o arquivo:
