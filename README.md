# Mobile Games: A/B Testing & Player Retention

<p><a href="https://www.facebook.com/cookiecatsgame">Cookie Cats</a> is a hugely popular mobile puzzle game developed by <a href="http://tactile.dk">Tactile Entertainment</a>. It's a classic "connect three"-style puzzle game where the player must connect tiles of the same color to clear the board and win the level. It also features singing cats. 

<p>As players progress through the levels of the game, they will <strong>occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress</strong>. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in the player's enjoyment of the game being increased and prolonged.<p>But where should the gates be placed? Initially, the first gate was placed at level 30. <strong>In this project, we're going to analyze an AB test where we moved the first gate in Cookie Cats from level 30 to level 40. In particular, we will look at the impact on player retention.</strong> </p>

Data Description

| Variable name        | Description                                                                |
|----------------------|----------------------------------------------------------------------------|
| `userid`             | The id of the user.                                                        |
| `version`            | The version of the game (gate 30 and gate 40).                             |
| `sum_gamerounds`     | The sum of game rounds played by users the first week after signing up.    |
| `retention_1`        | The retention on day 1 when they get to the gate.                          |
| `retention_7`        | The retention on day 7 when they get to the gate.                          |
