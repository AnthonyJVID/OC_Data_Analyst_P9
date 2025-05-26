# 🐔 OC - Projet 9 : Étude de marché pour l’exportation de volailles (La Poule Qui Chante)

Ce projet simule une mission pour **La Poule Qui Chante**, entreprise agroalimentaire française souhaitant s’implanter à l’international. L’objectif est de regrouper les pays en segments pertinents via des méthodes de **clustering**, afin d’orienter une future étude de marché.

---

## 🎯 Objectif de la mission

> Identifier des groupes de pays présentant des caractéristiques similaires selon des données issues de la FAO, afin de définir les zones prioritaires pour l’exportation.

Trois axes méthodologiques ont été suivis :

1. **Analyse exploratoire** des indicateurs clés : production, import/export, évolution démographique
2. **Clustering** :
   - Classification Ascendante Hiérarchique (CAH) avec dendrogramme
   - K-means avec interprétation des centroïdes
3. **Visualisation** des résultats via ACP (Analyse en Composantes Principales)

---

## 🧪 Démarche analytique

Deux notebooks distincts structurent la mission :

| Notebook | Contenu |
|---------|---------|
| `P9_Preparation_Nettoyage_Analyse_Exploratoire.ipynb` | Nettoyage, fusion, création de nouvelles variables (taux d’évolution, production, etc.) |
| `P9_Clustering_Visualisations.ipynb` | CAH, K-means, ACP, visualisation et interprétation des groupes |

---

## 📁 Arborescence du projet

```
├── P9_Preparation_Nettoyage_Analyse_Exploratoire.ipynb  → Analyse exploratoire
├── P9_Clustering_Visualisations.ipynb                   → Clustering & visualisation
├── data/                                                → Données FAO
├── presentation.pptx                                    → Présentation des résultats et recommandations
├── README.md                                            → Présentation du projet
└── requirements.txt                                     → Librairies Python utilisées
```

---

## 📊 Résultats obtenus

- Clustering de **169 pays** selon 6 indicateurs agro-économiques
- Identification de **groupes homogènes** de pays :
  - Fort taux d’importation vs. auto-suffisance
  - Croissance démographique élevée
  - Faible production locale
- Recommandations sur les **marchés prometteurs** selon les résultats de l’ACP et des k-means

---

## 📈 Visualisations

- Dendrogrammes pour la CAH
- Nuages de points colorés selon les clusters
- Représentation ACP pour la compréhension des liens entre pays/variables

---

## 🧠 Auteur

Projet réalisé par **AnthonyJVID** dans le cadre du parcours *Data Analyst* chez OpenClassrooms.

---

## 📄 Licence

Projet réalisé à but pédagogique pour illustrer une démarche d’analyse de marché internationale basée sur des données publiques (FAO).
