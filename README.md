<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F2937,100:4B5563&height=200&section=header&text=Data%20Integration%20Case%20Study&fontSize=40&fontColor=ffffff&desc=Campus%20Tech%20%E2%80%94%20S%C3%A9ance%205&descAlignY=65&descSize=18"/>

<img src="https://readme-typing-svg.herokuapp.com?font=Quicksand&size=20&duration=3000&pause=1000&color=4CAF50&center=true&vCenter=true&width=650&lines=Nettoyer+%E2%80%A2+Int%C3%A9grer+%E2%80%A2+Analyser+%E2%80%A2+Recommander;Le+plus+gros+CA+est-il+le+meilleur+magasin+%3F"/>

🐼 **M1 MIAGE — INF4 Atelier Python pour la Data Science** 🎋
Université Paris 1 Panthéon-Sorbonne · Groupe **G10**

<img src="https://img.shields.io/badge/Python-3-2D2D2D?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-4CAF50?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Jupyter-2D2D2D?style=for-the-badge&logo=jupyter&logoColor=white"/>

</div>

---

## 🐼 Le projet

**Campus Tech** est un revendeur fictif d'accessoires informatiques. Le responsable affirme :

> *« Le magasin qui a le plus gros chiffre d'affaires total est notre meilleur magasin. Nous devrions copier sa méthode partout. »*

Notre mission : **intégrer trois sources de données**, vérifier cette affirmation et formuler une **recommandation fondée sur les données**. Les données sont synthétiques et contiennent volontairement des erreurs de qualité.

---

## 🎋 Démarche

| Étape | Contenu |
|---|---|
| 🐾 **1. Audit** | Dimensions, valeurs manquantes, doublons exacts, vérification des clés |
| 🧹 **2. Nettoyage** | Suppression des doublons, normalisation des identifiants, conversion des dates et nombres, `sales_valid` / `sales_review` |
| 🔗 **3. Intégration** | Jointures gauches contrôlées (`validate="many_to_one"`), `integration_review`, table de réconciliation |
| 📊 **4. Indicateurs** | CA par commande, synthèse par magasin, par catégorie et par jour |
| 📈 **5. Graphiques** | CA total par magasin, distribution du CA par commande, CA journalier |
| 📝 **6. Conclusion** | Note au responsable, avec limites et recommandations |
| 💾 **7. Export** | Tableaux CSV et figures PNG |

---

## 🗂️ Structure du dépôt

```
INF4---Atelier-5/
├── 🐼 README.md
├── 📄 requirements.txt
├── 📁 data/
│   ├── case_sales.csv        # une ligne = une commande
│   ├── case_stores.csv       # une ligne = un magasin
│   └── case_products.csv     # une ligne = un produit
└── 📁 notebooks/
    ├── 05-Data-Integration-Case-Study.ipynb
    └── 📁 case_study_outputs/  # tableaux CSV et figures PNG exportés
```

---

## ▶️ Exécution

```bash
# 1. Cloner le dépôt
git clone https://github.com/kimynh/INF4---Atelier-5.git
cd INF4---Atelier-5

# 2. Installer les dépendances
pip install -r requirements.txt

# 3. Ouvrir le notebook
jupyter notebook notebooks/05-Data-Integration-Case-Study.ipynb
```

Dans Jupyter : **Kernel → Restart & Run All**. Le notebook doit s'exécuter de haut en bas sans erreur. Les fichiers exportés sont écrits dans `notebooks/case_study_outputs/`.

---

## 🐾 Membres et contributions

🐼 Élodie CAO · 🐼 Steve YEE KON PINE · 🐼 Daria QUESNEL · 🐼 Insafe LAHBICHI

L'ensemble du projet a été réalisé **collectivement** : on a travaillé ensemble sur chaque étape (nettoyage, jointures, indicateurs, graphiques et conclusion) puis on a relu et validé le notebook complet.

---

<div align="center">

🎋 🐼 🎋

*Données synthétiques : les résultats décrivent l'échantillon fourni, pas une entreprise réelle.*

</div>
