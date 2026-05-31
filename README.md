# Examinerande uppgift i Deep Learning-kurs

## Installation och hur man kör 

Python version 3.13.7

1. Klona projektet från Github. I terminalen: git clone https://github.com/josefinoleryd/facial-expression-cnn.git

2. Installera nödvändiga paket. I terminalen: pip install -r requirements.txt

3. Ladda ner FER-2013 från exempelvis Kaggle. 

4. Strukturen ska vara:
```text
data/
├── test/
│   ├── angry/
│   ├── disgust/
│   ├── fear/
│   ├── happy/
│   ├── neutral/
│   ├── sad/
│   └── surprise/
└── train/
    ├── angry/
    ├── disgust/
    ├── fear/
    ├── happy/
    ├── neutral/
    ├── sad/
    └── surprise/
```
5. Öppna model-experiments-and-report.ipynb. Hela notebooken är körd när den pushas upp på github så du behöver inte köra om den för att se resultatet, men vill du så är det "Run All".

## Teknikstack

- Programmeringsspråk: Python
- Dataanalys och beräkningar: Pandas och NumPy 
- Visualisering och figurer: Matplotlib och Seaborn
- Bildhantering: Pillow och OpenCV
- Maskininlärning: TensorFlow/Keras och scikit-learn
- Rapport och genomförande: Jupyter Notebook
- Versionshantering: Git och Github