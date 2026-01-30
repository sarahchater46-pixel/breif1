# breif1
projet brief, autour de l'evolution des ventes et les performances par categorie,produit,sous categorie et segment
• Sources de données

Les données proviennent de fichiers Excel :

Achats

Évaluations

• Logique des jointures et relations

Les relations entre les tables sont définies comme suit :

LEFT JOIN : Achats ↔ Évaluations
Permet de conserver tous les achats, même ceux sans évaluation.

LEFT JOIN : Achats ↔ Retours
Permet d’analyser les retours tout en conservant l’ensemble des achats.

INNER JOIN : Achats ↔ Personnes
Seuls les achats associés à des clients existants sont pris en compte.

• Instructions d’utilisation du dashboard

Utiliser les filtres pour affiner l’analyse.

Les paramètres permettent de modifier les indicateurs affichés.

Les visualisations sont interactives et liées entre elles.
