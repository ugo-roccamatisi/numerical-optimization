# TP d'optimisation — Ugo Roccamatisi

Quatre notebooks corrigés et exécutés, sans date :

1. `TP1_Méthodes_de_Gradient_Corrigé.ipynb` : gradient d'une fonction quadratique, pas optimal et recherche linéaire d'Armijo.
2. `TP2_Newton-correction.ipynb` : méthode de Newton et approximation inverse BFGS.
3. `TP_pbs_avec_contraintes_corrigé.ipynb` : conditions KKT, points intérieurs et Uzawa.
4. `TP4_Gradient_stochastique_et_regularisation_l1.ipynb` : régularisation L1, ISTA et sa version stochastique.

Les trois premiers documents avaient déjà des parties corrigées ; les réponses manquantes et les erreurs empêchant leur exécution ont été réparées. En particulier, une valeur propre erronée du problème avec contraintes a été corrigée.

La bibliothèque pédagogique `toynn_2023` appelée dans la dernière partie du TP4 n'était pas fournie. L'expérience correspondante est autonome : elle entraîne un réseau NumPy de même architecture (2–8–8–8–1) sur une classification en anneau, avec gradient par mini-lot, pas décroissant et seuillage doux L1. Ses scores ne doivent donc pas être pris pour les sorties exactes de la bibliothèque d'origine.

Ouvrir chaque fichier dans Jupyter et lancer les cellules dans l'ordre ; les sorties et graphiques sont déjà présents.
