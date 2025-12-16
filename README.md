# TFM – Màster Universitari en Ciència de Dades (UOC)

Aquest repositori conté els **annexos tècnics** del Treball Final de Màster (TFM) del Màster Universitari en Ciència de Dades de la **Universitat Oberta de Catalunya (UOC)**.

L’objectiu del repositori és garantir la **traçabilitat, transparència i reproductibilitat** del procés analític i de modelatge desenvolupat al TFM, complementant el document principal lliurat.

> **Nota important**: l’**Annex 1** forma part del document principal del TFM i **no s’inclou** en aquest repositori.

---

## Estructura dels annexos

Els annexos es corresponen directament amb els apartats metodològics descrits al TFM, especialment els capítols **4.3 (Preprocessament i anàlisi de dades)**, **4.4 (Modelatge predictiu)** i **4.5 (Validació i control de qualitat)**.

### 📎 Annex 2 – Integració i neteja inicial de dades

* Fitxer: `TFM_Annex2.ipynb`
* Contingut:

  * Càrrega del dataset principal i del diccionari de variables
  * Verificació d’estructura, tipus de dades, duplicats i valors nuls
  * Validació de coherència entre dades i diccionari
  * Resum executiu inicial del conjunt de dades

---

### 📎 Annex 3 – Transformacions i enginyeria de variables bàsica

* Fitxer: `TFM_Annex3.ipynb`
* Contingut:

  * Tractament de valors nuls (estructurals, moderats i baixos)
  * Creació de variables de control i flags de qualitat
  * Derivació de variables temporals bàsiques
  * Preparació del dataset net per a fases posteriors

---

### 📎 Annex 4 – Anàlisi exploratòria de dades (EDA)

* Fitxer: `TFM_Annex4.ipynb`
* Contingut:

  * Anàlisi exploratòria descriptiva del dataset final
  * Validació de distribucions, nuls i coherència de variables
  * Definició del mapa de variables per als models de freqüència i severitat
  * Preparació del conjunt de dades per a la fase de modelatge

---

### 📎 Annex 5 – Enginyeria de variables avançada

* Fitxer: `TFM_Annex5.ipynb`
* Contingut:

  * Definició de variables explicatives per model
  * Construcció de datasets base per a freqüència, severitat i ràtio econòmica
  * Control explícit de duplicats i consistència d’estructura
  * Preparació dels datasets per a la partició temporal

---

### 📎 Annex 6 – Divisió del conjunt de dades

* Fitxer: `TFM_Annex6.ipynb`
* Contingut:

  * Aplicació d’una divisió **exclusivament temporal** (train/test)
  * Definició coherent dels conjunts d’entrenament (2015–2017) i test (2018)
  * Generació dels datasets finals per a cada família de models
  * Prevenció explícita de *data leakage*

---

### 📎 Annex 7 – Modelatge predictiu

* Fitxer: `TFM_Annex7.ipynb`
* Contingut:

  * Model base GLM/GAM per a freqüència i severitat
  * Models avançats (ensemble i no lineals)
  * Selecció manual i automàtica de predictors
  * Avaluació amb mètriques estàndard (AUC, log-loss, RMSE, MAE, etc.)

---

### 📎 Annex 8 – Validació, avaluació i control de qualitat

* Fitxer: `TFM_Annex8.ipynb`
* Contingut:

  * Validació final dels models seleccionats
  * Avaluació sobre el cohort temporal de test
  * Anàlisi de calibratge, residus i fiabilitat
  * Comparativa de models i control de qualitat global

---

## Dades

Les dades originals utilitzades en aquest treball:

* Han estat **anonimitzades**
* Estan subjectes a **confidencialitat** i compliment del **RGPD**
* **No s’inclouen** en la distribució pública d’aquest repositori

Els notebooks estan preparats per ser revisats a nivell metodològic i conceptual, però no per executar-se sense accés als datasets originals.

---

## Llicència

Aquest treball està subjecte a una llicència:

**Creative Commons Reconeixement – No Comercial – Compartir Igual 3.0 Espanya (CC BY-NC-SA 3.0 ES)**
[https://creativecommons.org/licenses/by-nc-sa/3.0/es/](https://creativecommons.org/licenses/by-nc-sa/3.0/es/)

Aquesta llicència no afecta els drets morals de l’autor/a.

---

## Autoria

Carles Pons
Treball Final de Màster – Ciència de Dades
Universitat Oberta de Catalunya (UOC)
