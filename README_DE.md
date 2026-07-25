# Coffee Sales Forecast

Projekt für maschinelles Lernen zur Prognose des monatlichen Umsatzes
eines Cafés mit Linearer Regression in Python.

Ein vollständiger Analyse-Workflow, der zeigt, wie historische
Verkaufsdaten in eine geschäftliche Umsatzprognose umgewandelt werden
können. Das Projekt umfasst Datenvisualisierung, Modelltraining,
Vorhersagen, Modellbewertung und geschäftliche Interpretation.

# Daten

-   **Quelle:** Bildungsdatensatz für einen
    Data-Analytics-/Machine-Learning-Kurs.
-   Monatliche Umsätze von Januar 2022 bis Dezember 2024 (36
    Beobachtungen).
-   Variablen:
    -   `month_number`
    -   `year`
    -   `month`
    -   `month_name`
    -   `revenue`

# Projektziel

Entwicklung eines Machine-Learning-Modells zur Vorhersage zukünftiger
Monatsumsätze auf Grundlage historischer Verkaufsdaten und
Interpretation der Ergebnisse aus geschäftlicher Sicht.

# Projektschritte

1.  Daten vorbereiten und untersuchen.
2.  Explorative Datenanalyse durchführen.
3.  Trainingsdaten erstellen.
4.  Ein lineares Regressionsmodell mit scikit-learn trainieren.
5.  Das Modell mit MAE, RMSE und R² bewerten.
6.  Zukünftige Monatsumsätze prognostizieren.
7.  Ergebnisse geschäftlich interpretieren.

# Technologien

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Scikit-learn
-   Jupyter Notebook / Google Colab

# Wichtigste Erkenntnisse

-   Der Monatsumsatz zeigt einen klaren Aufwärtstrend.
-   Die lineare Regression bildet den allgemeinen Trend zuverlässig ab.
-   Das Modell eignet sich als Grundlage für einfache Umsatzprognosen.

# Empfehlungen

-   Verkaufsdaten regelmäßig aktualisieren.
-   Zusätzliche Einflussfaktoren wie Werbung, Feiertage oder Wetter
    berücksichtigen.
-   Bei stärkerer Saisonalität komplexere Prognosemodelle testen.
-   Das Modell regelmäßig mit neuen Daten neu trainieren.

# Repository-Struktur

``` text
data/
notebook/
images/
README.md
```

# Projekt reproduzieren

1.  `coffee_forecast_final.ipynb` öffnen.
2.  Benötigte Bibliotheken installieren.
3.  Alle Notebook-Zellen ausführen.
4.  Diagramme analysieren.
5.  Modell trainieren.
6.  Modell bewerten.
7.  Umsatzprognosen erstellen.

# Lernergebnisse

-   Explorative Datenanalyse
-   Lineare Regression
-   Modellbewertung
-   Umsatzprognosen
-   Geschäftliche Interpretation
