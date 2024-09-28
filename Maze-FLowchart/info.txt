# MAZE FLOWCHART
Postgres SQL et un gestionnaire de base de données relationnelles open-source.
Ces principales caractéristiques sont les suivantes:
	Conformitées ACID(Atomicité, cohérence, Isolation et Durabilite) qui sont nécessaire pour l'intégrité des données
	Extensibilité: On peut rajouter des extensions au système pour faire des taches qui ne sont pas build-in. Par exemple PostGIS
	pour les données géographiques et pgcrypto pour ajout de fonction cryptographiques
	Typage de données avancées: On as en fait la possibilité de créer des types de données a partir des types de bases(TEXT, INTEGER, BOOLEAN, JSON, TABLEAU, UUID)
	un peu comme les strutures en C
	Replication: Postgres embarque plusieurs mécanismes de réplication tels que la réplication en flux pour repliquer toutes les données sur les bases de données anexes et la réplication logiques qui permet de répliquer uniquement certaines données prédéfinies
	
IL est souvent utilisé pour les applications financières, les entrepôts de données et les applications web à grande échelle
Est-ce qu'il y a une syntax propre à POSTGRES quand on écrit du SQL ?
NOSQL
les bases de données NOSQL sont un type de système qui ne se repose pas sur le modèle relationnel traditionelle. Ce genre de système est adapté pour les données non structurés ou semi-structurés.
Les données sont généralement représentées sous formes de pair clé-valeur, de documents, de colones ou de graphes
L'un de leur avantages est la scalabité horizontale: C'est à dire que plutôt d'augmenter les specificités matérielles d'un serveur lorsque la charge de données augmente on peut tout simplement rajouter de nouveau serveur pour diviser la tâche de travaille de l'ancien.
Le fait qu'il s'agisse de données non structuré ou peu structurée represente aussi un grand avantage
En exemple de base de données non relationnels on peut citer MONGODB (JSON), ou Cassandra ()
