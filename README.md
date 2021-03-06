### Refer to image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/emoji-game-output-v2.gif" alt="emoji-game-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

#### Added Functionality

The app has the following functionalities

- The _Score_ and _Total Score_ for the current game is **0** initially.
- When an **Emoji** is clicked

  - If the clicked emoji is not the same as any of the previously clicked emojis
    then the _Score_ will be increased by **1**.
  - If all the emojis are clicked exactly once

    - The _Game status_ along with _Best score_ and _Play Again_ button will
      be displayed as shown in the **design file (won game)**.
    - The _Best score_ will be equal to the _Top Score_

  - If the clicked emoji is the same as any of the previously clicked emojis

    - The _Game status_ along with _Current score_ and _Play Again_ button
      will be displayed as shown in the **design file (lose game)**.

    - If the score achieved in the current game is higher than the previous
      scores then the _Top Score_ will be updated accordingly.

- When the _Play Again_ button is clicked, then we will be able to play the
  game again.

- The _Play Again_ button will reset the game and _Score_ value but not the
  _Top Score_ value.
