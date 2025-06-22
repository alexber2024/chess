# Creating a Chess Engine based on Deep Learning model

In this project I built a simple chess engine, which based purely on Deep Learning. The engine was able to defeat Stockfish engine level 1 (ELO rating 1000-1200) in a simulated game:

![](https://raw.githubusercontent.com/alexber2024/chess/refs/heads/main/images/game3.gif)

The Deep Learning model that powers the engine was trained on 700k chess positions evaluations. It has around 1M parameters with the following architecture:

![](https://raw.githubusercontent.com/alexber2024/chess/refs/heads/main/images/combined_model.jpg)

*Please note that the data files in this repo are truncated and only serve as an example. You can download full data from:
https://www.kaggle.com/datasets/ronakbadhe/chess-evaluations*
