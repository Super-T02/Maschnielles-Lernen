# Maschnielles-Lernen
Hier entsteht das ML Projekt aus der Vorlesung Einführung ins Maschinelle Lernen

## Konzept
###### Vom 2022-11-13

### Methode 
**Neuronales Netz**
Ziel ist es hier, die Generalisierbarkeit des Modells in Abhängigkeit der Qualität der  Trainingsdaten herauszuarbeiten.

### Datensätze
- **Titanic Problem**: https://www.kaggle.com/competitions/titanic/data?select=test.csv
  Fragestellung: Welche Personen würden aufgrund der Trainigsdaten sterben?
  Eigenschaften: Basiert verschiedenen Klassen, wie Alter, Fahrtklasse, Anzahl Kinder an Bord/ Geschwister / Eltern, Preis, etc. (10 Felder)
- **Emotionen Herausfinden**: https://www.kaggle.com/datasets/kmirfan/micro-expressions
  Fragestellung: Welche Emotionen zeigen die Personen auf dem Bildet 
  Eigenschaften: Gelabelte Daten geordnet nach Emotion.
  Vorteil: Möglichkeit der Generalisierung 
  Nachteil: Bilder müssen verarbeitet werden 
- **Tier Klassifikation**: https://www.kaggle.com/datasets/alessiocorrado99/animals10
  Fragestellung: Was für ein Tier ist auf dem Bild zu sehen?
  Eigenschaften: Bereits gelabelte Bilder für verschiedene Tierarten
  Nachteil: Große Datenmenge (Schwer zu verarbeitet), Nur wenig Tierarten (10 verschiedene)

### Tools 
- Python 
- Tensorflow
- Jupyter Notebooks