# Wordle Helper

A browser-based tool to help you solve [Wordle](https://www.nytimes.com/games/wordle/index.html) by filtering possible words based on your guesses.

[**Live site** ](https://RiveraMaxwell.github.io/wordle-helper)

---

## How to use

1. Type your guess into the 5 letter boxes
2. Right-click a box to cycle its color:
   - 🟩 **Green** — correct letter, correct position
   - 🟨 **Yellow** — correct letter, wrong position
   - ⬛ **Gray** — letter not in the word
3. Click **Find** to filter the word pool
4. Click any result word to fill it into the boxes

## Features

- **Animated tile flips** when cycling letter colors
- **Letter Frequency Heatmap** — shows which letters appear most in the remaining pool
- **Random Picks** — 10 random suggestions with a preference for all-unique-letter words
- **Best Next Guess** — ranks suggestions by how many words they'd eliminate (entropy scoring)
- All three panels appear side by side after the first Find
- Toggle Heatmap and Best Guess on/off via the settings buttons

## Word list

Sourced from [dracos/valid-wordle-words](https://gist.github.com/dracos/dd0668f281e685bad51479e5acaadb93) — the full set of valid Wordle guesses (~13,000 words).