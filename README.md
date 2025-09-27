# spotify-streams-ML
Predicts the number of streams a song will get on Spotify using supervised machine learning

## Dataset
- Spotify Top Songs 2023  
- Target: `streams`  
- Features: release year, playlist/chart presence, audio attributes (danceability, energy, valence, etc.)

## Models
- Linear Regression  
- Decision Tree Regressor  
- k-Nearest Neighbors (kNN)  
- Support Vector Regressor (SVR)  
- Ensemble Voting Regressor  

## Workflow
1. Data preprocessing & EDA  
2. Model training with cross-validation  
3. Hyperparameter tuning (GridSearchCV)  
4. Performance comparison (RMSE)
