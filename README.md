# 🧠 ML-heart_disease / NBA

Ce projet utilise deux jeux de données pour des analyses prédictives et exploratoires :

- 🫀 **Heart Disease (UCI)** : prédiction de la présence de maladie cardiaque
- 🏀 **NBA Player Stats** : analyse de performances des joueurs NBA

---

## 🫀 Dataset : Heart Disease (UCI)

Ce dataset est utilisé pour prédire la **présence ou les caractéristiques d’une maladie cardiaque** chez un patient. Il est couramment utilisé dans des projets de classification, de régression ou d’analyse médicale.

### 📊 Colonnes

| Colonne       | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| `age`         | Âge du patient (en années).                                                 |
| `sex`         | Sexe du patient (1 = homme ; 0 = femme).                                    |
| `cp`          | Type de douleur thoracique :<br>0 = angine typique, 1 = angine atypique, 2 = non-angineuse, 3 = asymptomatique |
| `trestbps`    | Pression artérielle au repos (mm Hg).                                       |
| `chol`        | Taux de cholestérol sérique (mg/dl).                                        |
| `fbs`         | Glycémie à jeun > 120 mg/dl (1 = oui ; 0 = non).                            |
| `restecg`     | Résultat ECG au repos :<br>0 = normal, 1 = anomalie ST-T, 2 = hypertrophie VG probable |
| `thalach`     | Fréquence cardiaque maximale atteinte.                                      |
| `exang`       | Angine induite par l’exercice (1 = oui ; 0 = non).                          |
| `oldpeak`     | Dépression du segment ST (exercice vs repos).                               |
| `slope`       | Pente du segment ST :<br>0 = plate, 1 = douce, 2 = raide                    |
| `ca`          | Nb de vaisseaux principaux visibles (0–3).                                  |
| `thal`        | Résultat au thallium :<br>1 = défectueux, 2 = normal, 3 = fixé              |
| `num` / `target` | Présence de maladie cardiaque (1 = oui ; 0 = non).                      |

---

## 🏀 Dataset : NBA Player Stats

Jeu de données contenant des statistiques individuelles de joueurs NBA.

### 📋 Colonnes

| Colonne       | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| `Player`      | Nom du joueur.                                                              |
| `Pos`         | Poste (ex : C = pivot, SG = arrière, etc.).                                 |
| `Age`         | Âge du joueur.                                                              |
| `Tm`          | Équipe (abréviation, ex : TOR = Toronto).                                   |
| `G`           | Matchs joués.                                                               |
| `GS`          | Titularisations.                                                            |
| `MP`          | Minutes par match.                                                          |
| `FG`, `FGA`, `FG%` | Tirs réussis, tentés, % réussite.                                      |
| `3P`, `3PA`, `3P%` | Tirs à 3 points (réussis, tentés, %).                                  |
| `2P`, `2PA`, `2P%` | Tirs à 2 points (réussis, tentés, %).                                  |
| `eFG%`        | Pourcentage de réussite ajusté (eFG%).                                      |
| `FT`, `FTA`, `FT%` | Lancers francs réussis, tentés, % réussite.                            |
| `ORB`, `DRB`, `TRB` | Rebonds offensifs, défensifs, totaux.                                |
| `AST`, `STL`, `BLK` | Passes décisives, interceptions, contres.                            |
| `TOV`, `PF`, `PTS` | Balles perdues, fautes, points par match.                             |

---


### 📥 Installation

```bash
# Cloner le repo
git clone [https://github.com/ton-utilisateur/ML-heart_disease.git](https://github.com/elachkham/ML-heart_disease-nba.git)
cd ML-heart_disease


