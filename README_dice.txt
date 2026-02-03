# Simple Dice Game

## Description
This program is a simple Python command-line dice game. The player places a wager, guesses a number between 1 and 6, and wins double their wager if the guess matches the dice roll. If the guess is incorrect, the player loses their wager.

---

## How the Game Works
1. The player is asked if they want to play.
2. The player enters a wager amount.
   - The wager must be a positive integer less than or equal to 100.
3. The player guesses a number between 1 and 6.
4. A dice roll is generated randomly.
5. If the guess is correct:
   - The player wins double their wager.
6. If the guess is incorrect:
   - The player loses their wager.

---

## Input Validation
- Wagers greater than 100 are rejected.
- Invalid wagers (zero or negative values) are rejected.
- Guess numbers must be between 1 and 6.

---

## Example Output





---

## 📄 README for `dice_game_double_play.py`

```markdown
# Dice Game – Double Play

## Description
This program extends the Simple Dice Game by adding a **double play** feature. After the first round, the player may choose to gamble again with increased stakes. The final winnings or losses are calculated based on both rounds.

---

## How the Game Works

### Part 1: Initial Play
1. The player chooses whether to play.
2. The player enters a wager (must be an integer ≤ 100).
3. The player guesses a number between 1 and 6.
4. A dice roll is generated.
   - If correct, the player wins double the wager.
   - If incorrect, the player loses the wager.
5. The result is stored as a positive (win) or negative (loss) total.

---

### Part 2: Double Play
1. The player is prompted for double play only if the wager is valid.
2. The double play amount is twice the absolute value of the current total  
   (equivalent to four times the original wager).
3. If the player declines:
   - The game ends and the current total is displayed.
4. If the player accepts:
   - The player makes a second guess.
   - If correct, the double play winnings are added.
   - If incorrect, the double play amount is subtracted.
5. The final total is displayed.

---

## Possible Outcomes
- Win first bet, win double play
- Lose first bet, win double play
- Lose both bets
- Win first bet, lose double play
- Win first bet, decline double play

---

## Example Output
