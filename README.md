# Football analysis: ML-approach to predict the 2. Bundesliga

This project was created in order to store the code needed for my seminar at university.
The corresponding publication "Erklaerbarkeit von Modellen maschinellen Lernens und Anwendung auf die 2. Fußballbundesliga" analyses Germany's
second football division, since it seems to be the most unpredictable league in Europe (or even in the world).
The work uses four different machine learning models to predict the results (home win, draw, away win) of the games.

## Uses models

The models used are:
- Decision Tree (scikit-learn)
- Support Vector Machine (scikit-learn)
- Light Gradient Boosting Machine (lightgbm)
- Neural Network (pytorch)

An in-depth description and discussion is available in the publication.

## Data used

The data the models were trained on comes from [FootyStats](https://footystats.org/de/download-stats-csv).
Since the data is only available behind a paywall, the CSV-files are not going to be published in this repository.
The data contains several statistics from games of the 2. Bundesliga of the seasons 2015/16-2021/22 and the 2022/23 season marks the test data.

## Contact

If any questions occure, feel free to contact me:

Simon Schulze
simon.schulze@s2021.tu-chemnitz.de
Technische Universitaet Chemnitz / Chemnitz University of Technology
