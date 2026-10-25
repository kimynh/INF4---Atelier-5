# Campus Tech — Data Integration Case Study (M1 MIAGE, Groupe n°10)

## Membres du groupe et contributions
- Insafe LAHBICHI — Section 1 (audit des sources) et Section 2 (nettoyage et validation)
- Elodie Cao — Section 3 (jointures et réconciliation)
- Steve YEE KON PINE — Section 4 (indicateurs) et Section 5 (figures 1-2)
- Daria QUESNEL — Section 5 (figure 3), Section 6 (decision brief) et Section 7 (export)

## Contenu du dépôt
- `notebooks/05-Data-Integration-Case-Study.ipynb` : notebook final, exécuté de bout en bout
- `data/` : les trois fichiers CSV fournis (bruts, non modifiés)
- `case_study_outputs/` : tables de synthèse exportées (CSV) et les 3 figures (PNG)

## Instructions d'exécution
1. Cloner le dépôt : `git clone https://github.com/kimynh/INF4---Atelier-5.git`
2. Installer les dépendances : `pip install pandas numpy matplotlib`
3. Ouvrir `notebooks/05-Data-Integration-Case-Study.ipynb` dans VS Code ou Jupyter
4. Restart Kernel puis Run All, le notebook recrée automatiquement `case_study_outputs/`
5. Les fichiers déjà présents dans `case_study_outputs/` correspondent à la dernière exécution validée

## Résumé des résultats
- 252 commandes brutes → 241 commandes retenues pour l'analyse (2 doublons exacts, 7 rejetées pour format invalide, 2 exclues pour référence inconnue)
- Magasin au CA total le plus élevé : Paris Est (10 528,9 €)
- Magasin à la commande médiane la plus élevée : Lille Centre (158,5 €)
- Conclusion : l'affirmation du manager n'est que partiellement confirmée (voir la Section 6 du notebook pour le détail)