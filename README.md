#  The North Face - Système de recommandation NLP

##  Objectif
Identifier des groupes de produits similaires et construire 
un système de recommandation à partir de 500 descriptions textuelles.

##  Méthodologie
1. Nettoyage du texte : suppression HTML, lemmatisation, stop words
2. Vectorisation TF-IDF des descriptions produits
3. Clustering DBSCAN pour regrouper les produits similaires
4. Fonction de recommandation basée sur la similarité cosinus
5. Extraction de 15 thèmes latents via LSA (TruncatedSVD)

##  Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-blue?style=flat)
![DBSCAN](https://img.shields.io/badge/Clustering-DBSCAN-green?style=flat)

##  Structure
```
northface-nlp-recommendation/
│
├── northface_ml.ipynb
└── README.md
```

##  Formation
Jedha AI School — Certification Data Science RNCP Niveau 6
