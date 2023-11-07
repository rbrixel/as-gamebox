*WORK IN PROGESS*

# as-gamebox
Gamebox for Airsoft for small fields. No Keypad needed - only two buttons. Sound playback instead of buzzer/piezo.

## Hardware
* Arduino Nano
* DFPlayer mini
* LCD 16*2
* 2x big buttons - red and blue
* ...

## Game modes
*[DM] Domination*
Two teams play. Each team must press its own button to score points. The team that reaches the score limit first wins.
If Team Red presses their button, the counter for Team Red counts up. If the blue team presses the blue button, the counter for the red team stops and the counter for the blue team starts counting.

*[BD] Bomb defuse*
Two teams play. There is one team that attacks and one team that defends.
The attackers have to get to the bomb and hold down the button for about 10 seconds to activate the bomb. If the process is interrupted, the activation counts down slowly back to zero. Once the bomb is activated, the defenders have 5 minutes to deactivate the bomb. To deactivate the bomb, the button must be held down for 20 seconds. If the process is interrupted, the deactivation slowly counts back to zero.
