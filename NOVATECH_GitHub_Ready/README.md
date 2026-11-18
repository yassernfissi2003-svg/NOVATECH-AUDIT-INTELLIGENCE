# NOVATECH Audit Intelligence

Prototype web local de contrôle de fiabilité des documents financiers.

## Démarrage

Ouvrir `index.html` dans un navigateur récent (Chrome ou Edge).

## Publication avec GitHub Pages

1. Importer `index.html`, `README.md` et `.gitignore` à la racine du dépôt.
2. Dans Settings → Pages, choisir `Deploy from a branch`.
3. Sélectionner la branche `main` et le dossier `/ (root)`, puis enregistrer.

## Périmètre et limites

Prototype d'aide au contrôle : extraction et règles heuristiques peuvent produire des erreurs et des faux positifs. Les alertes ne prouvent pas une falsification ni l'utilisation d'une IA. Les vérifications auprès de sources indépendantes restent humaines.

Ne pas déposer de factures, reçus, relevés bancaires, données personnelles ou fichiers clients dans ce dépôt public.

Certaines fonctions de lecture peuvent dépendre de bibliothèques chargées depuis Internet par le navigateur. Le traitement s'effectue dans le navigateur selon les fonctions disponibles dans cette version.
