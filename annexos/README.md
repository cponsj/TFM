# TFM – Màster Universitari en Ciència de Dades (UOC)
## Annexos tècnics – Repositori GitHub

Aquest repositori conté els **annexos tècnics del Treball Final de Màster (TFM)** del *Màster Universitari en Ciència de Dades* de la **Universitat Oberta de Catalunya (UOC)**.

L’objectiu del repositori és garantir la **traçabilitat, transparència i reproductibilitat** del procés complet de preprocessament de dades, enginyeria de variables, modelatge predictiu, validació i avaluació desenvolupat al TFM, complementant el document principal lliurat.

> **Nota important**
> - L’**ANNEX 1 – Protocol operatiu per a la comparativa de models predictius**
> - i l’**ANNEX 2 – Traçabilitat completa del pipeline de dades i modelatge predictiu**
> formen part **íntegrament del document principal del TFM** i **no s’inclouen** en aquest repositori.
>
> Aquest repositori correspon a l’**ANNEX 3**, que agrupa el detall tècnic complet del pipeline implementat.

---

## ANNEX 3 – Detall tècnic del pipeline de dades i modelatge predictiu

Aquest annex consolida en un únic repositori els notebooks tècnics que documenten de manera exhaustiva els apartats **3.3, 3.4, 3.5 i 3.6** del TFM (*Implementació, modelatge, validació i resultats*).

Cada notebook correspon directament a un subapartat del document principal i segueix el mateix ordre i numeració conceptual.

---

### 📎 Preprocessament i anàlisi de dades (Capítol 3.3)

**`TFM_Annex2_Preprocessament_i_neteja_de_dades.ipynb`**  
*Apartat 3.3.1 – Integració i neteja de dades*

- Càrrega del dataset original i del diccionari de variables  
- Validació d’estructura, tipus de dades, duplicats i valors nuls  
- Comprovacions de coherència actuarial i temporal  
- Generació del dataset net inicial

---

**`TFM_Annex3_Transformacions_i_enginyeria_de_variables_basica.ipynb`**  
*Apartat 3.3.2 – Transformacions i enginyeria de variables bàsica*

- Tractament de valors nuls estructurals i puntuals  
- Creació de flags de qualitat i coherència  
- Derivació de variables temporals bàsiques  
- Preparació del dataset per a l’anàlisi exploratòria

---

**`TFM_Annex4_Analisi_exploratoria_de_dades_EDA.ipynb`**  
*Apartat 3.3.3 – Anàlisi exploratòria de dades (EDA)*

- Anàlisi descriptiva i visual del portafoli  
- Validació de distribucions i asimetries  
- Identificació de patrons rellevants per a freqüència i severitat  
- Preparació del mapa de variables per al modelatge

---

**`TFM_Annex5_Enginyeria_de_variables_avancada.ipynb`**  
*Apartat 3.3.4 – Enginyeria de variables avançada*

- Construcció de datasets base per a freqüència, severitat i ràtio  
- Control explícit de *data leakage* actuarial i temporal  
- Transformacions numèriques i categòriques  
- Reducció de dimensionalitat i coherència multivariable

---

**`TFM_Annex6_Divisio_del_conjunt_de_dades.ipynb`**  
*Apartat 3.3.5 – Divisió del conjunt de dades*

- Divisió estrictament temporal (train 2015–2017 / test 2018)  
- Generació dels datasets finals *model-ready*  
- Garantia d’absència de *data leakage* prospectiu

---

### 📎 Modelatge predictiu (Capítol 3.4)

**`TFM_Annex7_Modelatge_predictiu.ipynb`**

- Models base actuarials (GLM/GAM)  
- Models avançats basats en ensembles i no lineals  
- Selecció manual i automàtica de predictors  
- Optimització d’hiperparàmetres  
- Comparació sistemàtica de models  
- Explicabilitat del model (SHAP, PDP, LIME)  
- Selecció de models *champion*

---

### 📎 Validació i resultats (Capítols 3.5 i 3.6)

**`TFM_Annex8_Validacio_avaluacio_i_resultats.ipynb`**

- Validació final dels models seleccionats  
- Avaluació sobre el cohort temporal de test (2018)  
- Control de qualitat i coherència de mètriques  
- Resultats finals utilitzats en les conclusions del TFM  

---

## Dades

Les dades originals utilitzades en aquest treball:

- Han estat **anonimitzades**
- Estan subjectes a **confidencialitat** i compliment del **RGPD**
- **No s’inclouen** en aquest repositori públic

Els notebooks permeten la revisió metodològica i conceptual del pipeline, però **no estan pensats per executar-se sense accés als datasets originals**.

---

## Llicència

Aquest treball està subjecte a la llicència:

**Creative Commons Reconeixement – No Comercial – Compartir Igual 3.0 Espanya (CC BY-NC-SA 3.0 ES)**  
https://creativecommons.org/licenses/by-nc-sa/3.0/es/

Aquesta llicència no afecta els drets morals de l’autor.

---

## Autoria

**Carles Pons**  
Treball Final de Màster – Ciència de Dades  
Universitat Oberta de Catalunya (UOC)

