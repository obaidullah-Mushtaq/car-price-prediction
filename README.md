# Car Price Prediction 📊🚗

Dieses Projekt analysiert einen Datensatz mit über 19.000 Fahrzeugen, um herauszufinden, welche Merkmale den Preis eines Autos beeinflussen – und wie man ihn vorhersagen kann.

## 🔍 Ziel
Das Ziel ist es, Muster zu erkennen und ein Modell zu entwickeln, das den **Preis eines Autos** anhand technischer und optischer Eigenschaften vorhersagen kann.

---

## 📁 Dateien

- `train.csv`: Trainingsdaten mit 18 Spalten (inkl. Preis)
- `test.csv`: Testdaten ohne Preis (für spätere Vorhersagen)
- `car_price_analysis.ipynb`: Jupyter Notebook für Analyse & Visualisierung

---

## ✅ Geplante Schritte

1. **Daten laden & erkunden**  
   → Struktur, fehlende Werte, Datentypen

2. **Daten bereinigen**  
   → `Mileage`, `Levy`, `Engine volume` etc. umwandeln

3. **Daten visualisieren**  
   - Preisverteilung (Histogramm)  
   - Hersteller-Vergleich (Boxplot)  
   - Einfluss von Baujahr, Motorgröße etc.

4. **Feature Engineering**  
   → Neue Spalten wie z. B. `km_per_year`, `price_per_cylinder`

5. **Modelltraining**  
   → Lineare Regression, Random Forest, etc.

6. **Vorhersage auf Testdaten**  
   → Preis schätzen

7. **Fazit und Verbesserungsideen**

---

## 🧠 Verwendete Tools

- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Jupyter Notebook oder VS Code mit .ipynb-Unterstützung

---

## 🔮 Zielgruppe

Datenanalysten, ML-Einsteiger, Auto-Interessierte und Studierende, die lernen möchten, wie man aus realen Daten Wissen gewinnt.
