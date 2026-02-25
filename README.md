# NLP-Projekt: Textvorverarbeitung und Visualisierung

## Projektbeschreibung
Dieses Projekt demonstriert **Textvorverarbeitung**, **Merkmalextraktion** und **Visualisierung** von Textdaten mit Python.  
Der Datensatz enthält Rohtext (z. B. Wikipedia-Artikel) und das Ziel ist es, die häufigsten Begriffe zu analysieren, seltene Wörter zu entfernen und die Daten visuell darzustellen.

## Projektschritte

### Schritt 1: Textvorverarbeitung
- Funktion `clean_text` erstellt:
  - Groß-/Kleinschreibung vereinheitlichen
  - Satzzeichen entfernen
  - Zahlen entfernen

- Stopwords entfernen
- Seltene Wörter filtern (z. B. Wörter, die weniger als 1000 oder 2000 Mal vorkommen)
- Tokenisierung der Texte
- Lemmatisierung der Wörter


### Schritt 2: Analyse & Visualisierung
- **Wortfrequenzen berechnen**:
  - Mit `pd.value_counts` oder `Counter`
- **Balkendiagramm** der häufigsten Wörter erstellen
- **WordCloud** zur Visualisierung aller Wörter oder der Top-N Wörter


### Schritt 3: Alles in einer Funktion
Eine Funktion `preprocess_and_visualize` wurde erstellt, die in einem Schritt:
- Textbereinigung
- Stopwords-Entfernung
- Seltene Wörter filtern
- Tokenisierung & Lemmatisierung
- Balkendiagramm & WordCloud  

kombiniert.
