# Le Saint Esprit — Marseille

> Site officiel & réservation du restaurant bistronomique **Le Saint Esprit**  
> 16 Rue du Refuge · Le Panier · 13002 Marseille  
> Réservations : [09 61 29 30 43](tel:+33961293043)

---

## 🏛️ Présentation

Sous les voûtes de pierre séculaires d'un ancien fournil au cœur du quartier historique du Panier à Marseille, **Le Saint Esprit** propose une cuisine instinctive rythmée par les saisons, les arrivages directs des bateaux de pêcheurs locaux, une cave de maturation de viandes d'exception et une sélection soignée de vins vivants.

---

## 📂 Architecture du Projet

```text
.
├── index.html              # Page d'accueil (Hero salle voûtée, identité, ambiance, aperçu carte, galerie)
├── menu.html               # Carte complète (Snacks & partage, assiettes du marché, viandes & poissons)
├── histoire.html           # Histoire du lieu (L'ancien fournil, l'héritage du Panier, l'équipe)
├── reservation.html        # Module de réservation en ligne & carte d'accès Google Maps interactive
├── assets/
│   ├── css/
│   │   ├── tokens.css      # Design tokens (Palette bordeaux/or, typographie, espacements)
│   │   └── main.css        # Styles globaux, layout, navigation & composants responsive
│   └── images/             # Photographies compressées et optimisées (WebP & JPG haute fidélité)
├── photos_originales/      # Visuels et archives sources
└── README.md
```

---

## 🚀 Lancer en Local

Aucune dépendance requise (site statique pur, ultra-léger et rapide) :

```bash
# Avec Python 3
python3 -m http.server 3000

# Ou avec npx serve
npx serve .
```

Puis ouvrez votre navigateur sur [http://localhost:3000](http://localhost:3000).

---

## 📱 Standards & Performance

- **Mobile First & Responsive** : Conçu sur-mesure pour les formats tactiles (galeries en scroll-snap naturel, zones de frappe ≥ 44px).
- **SEO & Référencement local** : Balisage sémantique HTML5 complet et données structurées **Schema.org** JSON-LD (`@type: Restaurant`).
- **Performance** : 0 bibliothèque tierce lourde, animations matérielles natives (`transform`, `opacity`), lazy loading des médias sous la ligne de flottaison.
