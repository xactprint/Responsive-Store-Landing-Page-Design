Choix de design

Direction esthétique — Éditorial raffiné
Plutôt qu’un template e-commerce générique, VAULT adopte une approche éditoriale luxueuse inspirée de boutiques comme Aesop et Hay. La palette utilise un ivoire chaud (#f8f5f0), un charbon presque noir (#1c1a17) et un accent doré laiton (#b08d57) — des tons naturels, intemporels, loin du style dégradé violet trop utilisé.

Typographie
Playfair Display (serif, Google Fonts) — pour les titres et le logo. Ses italiques apportent une touche d’élégance à des accroches comme « those who notice »
DM Sans (sans géométrique) — pour le texte courant et les éléments d’interface. S’associe parfaitement avec Playfair sans entrer en concurrence

Mise en page & espacement
Le Hero utilise une grille 50/50 avec l’image à droite — cela offre de l’espace sans donner une impression de vide
Les produits utilisent une grille à 4 colonnes (→ 2 colonnes sur tablette → 1 colonne sur mobile)
Un padding vertical généreux (--space-2xl) crée une sensation aérée et premium

Détails à remarquer
Anneau décoratif animé en rotation sur l’image du hero
Icône cœur (wishlist) qui apparaît en fondu au survol des cartes produits
Bande défilante (marquee) pour communiquer les avantages sans surcharger la mise en page
Badges (Meilleure vente / Nouveau / –20%) avec un code couleur distinct
La section À propos utilise un panneau sombre avec une image plein cadre — un contraste visuel fort

Responsive (adaptabilité)
Tous les points de rupture sont gérés via des media queries CSS (sans dépendance à un framework) :

≤ 1024px (tablette) : produits → 2 colonnes ; section À propos en empilement vertical ; footer empilé
≤ 768px (mobile) : menu hamburger ; hero en une seule colonne ; produits → 1 colonne ; newsletter empilée
≤ 480px (petits mobiles) : footer en une colonne ; boutons en pleine largeur

Le menu hamburger est réalisé en JavaScript — aucune bibliothèque nécessaire. Il utilise une animation basée sur max-height pour un effet de glissement fluide vers le bas.
