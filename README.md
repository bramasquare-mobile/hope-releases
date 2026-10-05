# Hope — téléchargements

Installateurs de l'application **Hope** (gestion de cabinet médical).
Ce dépôt ne contient pas de code : uniquement les versions publiées automatiquement par
[`hope-app`](https://github.com/bramasquare-mobile/hope-app) (dépôt privé).

## Dernières versions

Mise à jour automatique à chaque publication. « — » : pas encore publiée.

<!-- builds:start -->
| Canal | Plateforme | Fichier | Publiée le (heure de Tunis) | Branche | Commit | Taille | Build |
|---|---|---|---|---|---|---|---|
| Test | Windows | [Hope-Setup-Latest.exe](https://github.com/bramasquare-mobile/hope-releases/releases/download/preprod-latest/Hope-Setup-Latest.exe) | 05/10/2026 11:22 | develop | [d9dfaa8](https://github.com/bramasquare-mobile/hope-app/commit/d9dfaa85a5beecc561c96308c55ba94ae220aa13) | 37,6 Mo | [exécution](https://github.com/bramasquare-mobile/hope-app/actions/runs/37294397124) |
| Test | Tablette Android | [Hope-Android-Latest.apk](https://github.com/bramasquare-mobile/hope-releases/releases/download/preprod-latest/Hope-Android-Latest.apk) | 05/10/2026 11:42 | develop | [fda145b](https://github.com/bramasquare-mobile/hope-app/commit/fda145b6e89822075bf4ade16dea5af87bf18f74) | 70,8 Mo | [exécution](https://github.com/bramasquare-mobile/hope-app/actions/runs/37297723409) |
| Test | macOS | — | — | — | — | — | — |
| Stable | Windows | — | — | — | — | — | — |
| Stable | Tablette Android | — | — | — | — | — | — |
| Stable | macOS | — | — | — | — | — | — |
<!-- builds:end -->

## Version stable (production)

| Plateforme | Lien permanent |
|---|---|
| Windows | https://github.com/bramasquare-mobile/hope-releases/releases/latest/download/Hope-Setup-Latest.exe |
| macOS | https://github.com/bramasquare-mobile/hope-releases/releases/latest/download/Hope-Latest.dmg |
| Tablette Android | https://github.com/bramasquare-mobile/hope-releases/releases/latest/download/Hope-Android-Latest.apk |

## Version de test (preprod)

À utiliser uniquement pour valider une version avant sa mise en production.

| Plateforme | Lien permanent |
|---|---|
| Windows | https://github.com/bramasquare-mobile/hope-releases/releases/download/preprod-latest/Hope-Setup-Latest.exe |
| macOS | https://github.com/bramasquare-mobile/hope-releases/releases/download/preprod-latest/Hope-Latest.dmg |
| Tablette Android | https://github.com/bramasquare-mobile/hope-releases/releases/download/preprod-latest/Hope-Android-Latest.apk |

Chaque version est aussi disponible individuellement dans l'onglet [Releases](https://github.com/bramasquare-mobile/hope-releases/releases) :
`v<version>` pour la production, `preprod-<commit>` pour les tests.

## Installation

- **Windows** : lancer `Hope-Setup-Latest.exe` (installation pour l'utilisateur, sans droits administrateur).
- **macOS** : ouvrir le `.dmg` et glisser Hope dans Applications. Tant que la version n'est pas signée par Apple,
  faire clic droit → Ouvrir au premier lancement.
- **Tablette Android** : autoriser l'installation depuis cette source, puis ouvrir le fichier `.apk`.
- **iPad** : distribution via TestFlight / App Store (à venir).
