# Simulação Física com Matter.js e p5.js

Este projeto é uma simulação simples de física utilizando **Matter.js** em conjunto com **p5.js**. Ele demonstra a aplicação de forças em um objeto (bola) dentro de um ambiente fechado, usando botões interativos.

## 📌 Descrição do Projeto

- Uma bola é criada dentro de um canvas 400x400.
- O ambiente possui quatro paredes (chão, teto, esquerda e direita).
- Dois botões permitem aplicar forças na bola:
  - Um botão empurra a bola para a **direita**.
  - Um botão empurra a bola para **cima**.
- A física (gravidade, colisões e restituição) é controlada pelo **Matter.js**.

## 🛠️ Tecnologias Utilizadas

- **JavaScript**
- **p5.js**
- **Matter.js**

## 🎮 Controles

- 🡆 **Botão Right**: Aplica uma força horizontal positiva na bola.
- 🡅 **Botão Up**: Aplica uma força vertical negativa (para cima) na bola.

## ⚙️ Funcionamento do Código

- `Engine.create()` cria o motor de física.
- `World.add()` adiciona corpos ao mundo físico.
- `Bodies.circle()` cria a bola com efeito de quique (`restitution`).
- `Matter.Body.applyForce()` aplica forças controladas pelos botões.
- A função `draw()` atualiza o motor e renderiza os objetos na tela.

## 📂 Estrutura Básica

- `setup()` → Inicializa canvas, mundo físico e botões.
- `draw()` → Atualiza a simulação e desenha os objetos.
- `hForce()` → Aplica força horizontal.
- `vForce()` → Aplica força vertical.

## ▶️ Requisitos para Executar

- Arquivos das imagens:
  - `right.png`
  - `up.png`
- Inclusão das bibliotecas:
  - p5.js
  - matter.js

## 👤 Autor

**Gabriel Bento**
