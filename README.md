# ba_hotel_reservation

Application Flutter pour la réservation d'hôtels (prototype).

Description
-----------
Ce dépôt contient une application mobile Flutter destinée à gérer la réservation d'hébergements : affichage d'hôtels, fiche détaillée, réservation et pages d'administration de base. Le projet est structuré pour être multi-plateforme (Android / iOS / web).

Principales fonctionnalités
- Parcours des établissements (liste, filtres simples)
- Fiche détaillée d'un hôtel
- Processus de réservation basique
- Architecture modulaire côté Flutter (modules, routes, widgets réutilisables)

Prérequis
- `Flutter` (version stable récente)
- SDK Android et/ou Xcode si vous ciblez les plateformes natives

Installation et exécution
1. Récupérez les dépendances :

```
flutter pub get
```

2. Lancer l'application en développement :

```
flutter run
```

3. Construire un APK Android :

```
flutter build apk --release
```

4. Construire pour iOS (sur macOS avec Xcode) :

```
flutter build ios --release
```

Tests

```
flutter test
```

Structure du projet (principaux fichiers/dossiers)
- `lib/` : code Flutter
	- `main.dart` : point d'entrée
	- `motel_app.dart` : configuration principale de l'app
	- `modules/` : fonctionnalités séparées en modules
	- `models/` : modèles de données
	- `logic/` : logique métier / providers
	- `routes/` : définition des routes
	- `widgets/` : composants réutilisables
	- `utils/`, `constants/`, `common/` : utilitaires et constantes
	- `language/`, `l10n/` : localisation
- `android/`, `ios/` : code & configuration natifs
- `assets/` : images et ressources (vérifier `pubspec.yaml` pour lister)
- `test/` : tests unitaires et widget
- `web/` : ressources pour la version web

Remarques
- Vous avez ajouté plusieurs fichiers sous `lib/` (modules, models, widgets, etc.). J'ai inclus les dossiers principaux ci‑dessus — si vous voulez que je liste chaque fichier ajouté, dites-moi lesquels ou je peux générer automatiquement un inventaire détaillé.

Contribuer
- Créez une branche dédiée : `git checkout -b feat/ma-fonction`
- Respectez les conventions de code et ajoutez des tests pour les nouvelles fonctionnalités
- Ouvrez une pull request avec une description et captures d'écran si nécessaire

Licence
- Ajoutez ou vérifiez un fichier `LICENSE` si vous souhaitez préciser la licence du projet.

Contact
- Pour questions ou retours : ouvrez une issue dans ce dépôt.
