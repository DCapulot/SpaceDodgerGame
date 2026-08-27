# 🚀 Space Shooter Game

Um jogo **2D desenvolvido com JavaScript e HTML5 Canvas**, no qual você controla uma nave espacial e precisa sobreviver desviando e destruindo asteroides enquanto coleta **power-ups**.

O objetivo é conseguir a maior pontuação possível enquanto enfrenta uma quantidade crescente de asteroides.

---

## 🔗 Link do Projeto

👉 **[Acesse o projeto aqui](https://dcapulot.github.io/SpaceDodgerGame/)**

---

## 🎮 Como Jogar

Utilize as teclas do teclado para controlar a nave:

| Tecla            | Ação                  |
| ---------------- | --------------------- |
| ⬅️ Seta esquerda | Mover para a esquerda |
| ➡️ Seta direita  | Mover para a direita  |

### 🎯 Objetivo

Durante a partida, você deve:

* ☄️ Desviar dos asteroides;
* 🔫 Destruí-los com tiros;
* ⚡ Coletar power-ups;
* 🏆 Conseguir a maior pontuação possível;
* 🚀 Sobreviver pelo maior tempo possível.

---

## ⚡ Power-ups

O jogo possui diferentes tipos de power-ups que ajudam o jogador durante a partida.

### 🛡️ Shield — Escudo

Protege a nave contra colisões durante alguns segundos.

### 🔥 Auto Shoot

Ativa o disparo automático da nave, permitindo atacar os asteroides sem precisar realizar cada disparo manualmente.

---

## 🧠 Mecânicas do Jogo

O jogo possui um sistema de dificuldade baseado na progressão da partida:

* ☄️ Asteroides caem continuamente do topo da tela;
* 📈 A quantidade de asteroides aumenta com o tempo;
* ⚡ A velocidade dos asteroides aumenta progressivamente;
* 🏆 O jogador acumula pontuação durante a partida;
* 💥 Os asteroides podem ser destruídos com tiros;
* 🛡️ O escudo protege contra colisões temporariamente;
* ☠️ Colidir sem o escudo resulta em **Game Over**.

---

## 🖼️ Assets Necessários

As imagens utilizadas pelo jogo devem ser colocadas dentro da pasta `images/`.

```text
images/
├── fundo.png
├── nave.png
├── asteroid.png
├── powerup.png
└── powerup_shield.png
```

---

## ▶️ Como Rodar

### 1. Clone o repositório

```bash
git clone URL_DO_SEU_REPOSITORIO
```

### 2. Abra o projeto

Entre na pasta do projeto e abra o arquivo:

```text
index.html
```

### 3. Estrutura básica do HTML

O jogo utiliza um elemento `canvas` para renderizar a partida:

```html
<canvas id="gameCanvas"></canvas>

<button onclick="startGame()">Start</button>

<div id="menu">Clique para jogar</div>
```

### 4. Inclua o JavaScript

No arquivo HTML, adicione:

```html
<script src="game.js"></script>
```

### 5. Execute no navegador 🌐

Abra o `index.html` em um navegador compatível e clique em **Start** para começar a partida.

---

## 🛠️ Tecnologias Utilizadas

* 🟨 **JavaScript**
* 🎨 **HTML5 Canvas**
* 🌐 **HTML5**

---

## 📈 Melhorias Futuras

Algumas funcionalidades que podem ser adicionadas futuramente:

* ❤️ Sistema de vidas;
* 🎵 Sons e música;
* 🎨 Menu mais elaborado;
* ⚠️ Sistema de dificuldade progressiva;
* 👾 Batalha contra chefão (**Boss Fight**);
* ⚡ Novos tipos de power-ups;
* 🏆 Sistema de recorde;
* 📱 Suporte para dispositivos móveis.

---

## 📂 Estrutura do Projeto

```text
Space-Shooter/
│
├── index.html
├── game.js
├── images/
│   ├── fundo.png
│   ├── nave.png
│   ├── asteroid.png
│   ├── powerup.png
│   └── powerup_shield.png
│
└── README.md
```

---

## 👨‍💻 Autor

**David**

Projeto desenvolvido como uma prática de desenvolvimento de jogos utilizando **JavaScript e HTML5 Canvas**, com foco em lógica de programação, interação com o usuário e criação de mecânicas de jogos 2D.

---

⭐ **Se você gostou do projeto, deixe uma estrela no repositório!**

🚀 **Prepare sua nave, destrua os asteroides e alcance a maior pontuação!**
