# Ansatteide Selskaper – Prediksjonsmodell

Dette prosjektet ble laget i forbindelse med en casekonkurranse arrangert av **Menon Economics** og **Økonomisk institutt ved Universitetet i Oslo**. Målet var å bygge en modell som predikerer sannsynligheten for at et selskap er ansatteid, basert på strukturelle og økonomiske kjennetegn ved selskapet og dets eiere.

## 🏆 Resultat

Jeg deltok i konkurransen og kom på **2. plass**, i konkurranse med mange dyktige studenter.

## 🔍 Problemstilling

> Hvordan kan vi bruke økonometriske eller maskinlæringsbaserte modeller til å estimere sannsynligheten for at et selskap er ansatteid?

Datasettet var hentet fra et reelt prosjekt utført av Menon på oppdrag for **Finansforbundet** (2023).

## 🔧 Teknologi og metode

- 📦 Python
  - `xgboost`
  - `pandas`
  - `scikit-learn`
- 🧠 Modell: `XGBRegressor` med hyperparameter-tuning via `RandomizedSearchCV`
- 🧼 Preprosessering:
  - Konvertering av objekt-kolonner til kategorier
  - Standardisering av numeriske kolonner
- 📈 Evaluering:
  - Mean Squared Error (MSE)



## 📊 Resultater

Modellen leverte god treffsikkerhet, og prediksjonene ble brukt til å estimere sannsynlighet for ansatteierskap i et ukjent testsett.

