# ♟️ Chess Game using Machine Learning

This project combines the strategy of chess with the power of **Machine Learning** to build a chess position evaluation system. The model learns from a dataset of chess positions and their corresponding evaluations, allowing it to predict the strength of a given board state. It serves as a foundation for developing intelligent chess agents capable of decision-making.
Dataset URL: https://www.kaggle.com/datasets/ronakbadhe/chess-evaluations

---

## Project Overview

The main goal of this project is to train a **neural network model** that evaluates chess positions, then integrate it into an interactive chess interface. Users can play chess and see how the model predicts board evaluations during gameplay.

### Key Objectives
- Preprocess a dataset of chess positions and evaluation scores  
- Train a **TensorFlow neural network** to predict evaluation values  
- Test the model’s accuracy and performance  
- Integrate the model with an interactive chess UI using `ipywidgets`  

---

## Project Structure
```plaintext
chess_ml_app/
├── data/
│   └── chess_evaluations.csv         # Dataset of chess positions (FEN + evaluation)
├── models/
│   ├── chess_eval_model.h5           # Trained TensorFlow model
│   ├── eval_scaler_mean.npy
│   └── eval_scaler_std.npy
Chess_Game_ML.ipynb                   
```
## Installation and Setup
You can run this project on Google Colab by using merely the Chess_Game_ML.ipynb file.

---

## UI

Before clicking Start
![image alt](https://github.com/nanhmtnn/CS4200-Chess-Game/blob/ddbb78961531de67299c1cde3a41c2c41276673d/before_start.png)

Game starts
![image alt](https://github.com/nanhmtnn/CS4200-Chess-Game/blob/1b55a30bdf8ad2a97b6cf2137fb3c478582bc1e6/start.png)

The AI wins
![image alt](https://github.com/nanhmtnn/CS4200-Chess-Game/blob/ddbb78961531de67299c1cde3a41c2c41276673d/win.png)
