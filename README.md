## Description:

This userscript automatically performs jumps in the web game <https://bocchinet.com/GQux/>.

## How it works:

It intercepts the original game.js script.
It injects logic into the game's physics update loop.
This logic simulates the ball's trajectory after a potential jump.
If the simulation predicts the jump will land the ball close enough to the hole (based on configurable physics parameters), it automatically triggers the jump.

## How to Use:

Install the userscript with a manager like Tampermonkey.
Visit the game page: https://bocchinet.com/GQux/
The script will run automatically.
