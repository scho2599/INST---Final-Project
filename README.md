# INST---Final-Project
# By: Shua Cho

## Overview:

This is the final version of my consolidation project that I have updated to meet the requirement of the final project. It builds on top of my Trisky Battles game which is a two player game where each player takes turns playing cards to win rounds by matching suits and card values. The goal is to be thte first player to hit 9 points or win through another special condition called "shooting the moon" in which they score all 16 points. This final submission helps with some calrity and also reflects my learning. 

## How to run:

1. Make sure you have **Python 3** installed on your computer.
2. Download the file `tricksy_battle.py` from this project.
3. Open a terminal or command prompt and navigate to the folder where the file is saved.
4. Run the game by typing:  python tricksy_battle.py
5. The game will then start to run on the terminal.

## Included Features: 

1. A 48 card deck created and shuffled using random.shuffle.
2. Each player is dealt 8 cards to start.
3. A new “public card” is shown after each round (for visual info only).
4. Players must follow suit if possible; otherwise, they play any card.
5. A simple scoring system tracks points, and the first to 9 wins.
6. “Shooting the moon” rule awards 17 points if a player wins all 16 rounds.
7. After both players reach 4 cards, they are dealt 4 more cards (twice).
8. Final scores are saved in a file called final_scores.txt.
9. The program politely asks the user if they want to play again at the end.

## Shortcomings:

So honestly the error I had from my last submission is still there. It is a small error involving the game giving the round win to the wrong player sometimes. Sometime like even when someone shouldve won based on the suits it like unintentionally gives the win to the opponent. Sometime like even when someone shouldve won based on the suits it like unintentionally gives the win to the opponent. I wasnt able to figure out why exactly this was happening as I got caught up in studying for other finals however the game still runs normally besides that, it still keeps score normally and plays the rounds as normal. 

## What I learned:

Honestly I beieve this was a good project in terms of my growth. It helped me understand how to break problems down into smaller parts, use loops and functions, and be okay with making mistakes as well. I still had an issue with my final code that I wasnt able to fully overcome by the time of my submission but thats okay and it just further fuels me to to becoming better in my coding journey. 
