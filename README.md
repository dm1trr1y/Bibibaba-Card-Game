# 🌵 Wild West: Card Duel

A browser-based tactical card game inspired by the mechanics of *Bang!*, *Slay the Spire*, and *Inscryption*. Step into the dusty boots of a gunslinger and face off against outlaws in intense 1-on-1 duels!

## 🎮 Features

* **Slay the Spire Cycle:** Draw 4 cards at the start of your turn, manage a limited pool of energy, and discard unplayed cards at the end of your turn.
* **Inscryption Intent System:** Anticipate your enemy's next move. The enemy's "Intent" is displayed before they act, allowing you to plan your attacks and defenses strategically.
* **Bang! Thematic Cards:** Use classic Wild West actions like *Bang!* (Attack), *Missed!* (Block), and *Beer* (Heal).
* **Three Difficulty Levels:**
  * 🟢 **Level 1 (Easy) - Drunken Jim:** Low damage, highly predictable. Good for learning the ropes.
  * 🟡 **Level 2 (Medium) - Bandit Billy:** Uses dodges and dynamic, heavier attacks.
  * 🔴 **Level 3 (Hard) - Sheriff "Black Eye":** Utilizes heavy counter-attacks and fatal shotgun blasts. You must balance your shields perfectly to survive.

## 🚀 How to Play

1. Save the game code as an `index.html` file.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge). No installation or server required.
3. Choose your difficulty level from the Main Menu.
4. **Combat Rules:**
   * You start each turn with **3 Energy (⚡)**.
   * Click on a card in your hand to play it (if you have enough energy).
   * Pay close attention to the **Enemy Intent** box. If they plan to attack for 12 damage, make sure to play "Missed!" cards to build up your Block.
   * Click **End Turn** when you are out of energy or strategic moves.
   * Reduce the enemy's HP to 0 to win. If your HP drops to 0, you lose.

## 🃏 Card Types

* 🔴 **Red (Attack):** Direct damage to the opponent (e.g., *BANG!*, *Shotgun*).
* 🔵 **Blue (Defend):** Grants "Block" (Dodge) to absorb incoming damage on the enemy's next turn. *Note: Block resets at the start of your turn.*
* 🟢 **Green (Heal):** Restores your Health Points (e.g., *Beer*).
* 🟠 **Gold (Special):** Powerful combination cards like *Duel* that offer both offense and defense at a higher energy cost.

## 🛠️ Technologies

* **HTML5:** Structure and canvas.
* **CSS3:** Styling, animations, and responsive layout.
* **Vanilla JavaScript:** Game logic, deck management, and enemy AI.
* *Zero dependencies — no external libraries or frameworks needed!*
