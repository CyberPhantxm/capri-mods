# Capri Lyrics

Paroles Spotify synchronisées pour Capri Desktop 0.8.9 (Mod API 3), sous Windows uniquement.

- Made by: Suoh

## Aperçu

Affiche les paroles Spotify synchronisées sur un bandeau **cyberpunk** (bouton **CC**).
Défilement fluide, gros plans du visage de Capri avec effets de glitch, fissures et zoom sur les yeux. Capri peut s'asseoir ou s'allonger pendant l'affichage.

## Fonctionnalités

- **Paroles synchronisées** (LRC) via [lrclib.net](https://lrclib.net) et [lyrics.ovh](https://api.lyrics.ovh)
- **Paroles simples** en fallback quand les paroles synchronisées sont indisponibles
- **Cache local** des paroles pour éviter les requêtes répétées
- **Affichage cyberpunk** : texte glitché, couleurs cyan/rose, fissures, zoom sur les yeux
- **Défilement fluide** avec la ligne courante mise en évidence
- **Bouton CC** pour afficher/masquer le bandeau
- **Poses de Capri** : assis, allongé, aucun
- Gestion des morceaux instrumentaux

## Installation

1. Placez le fichier `capri-lyrics.capri-code` dans le dossier des mods Capri :
   ```
   %LOCALAPPDATA%\Capri\mods\
   ```
2. Redémarrez Capri Desktop.
3. Le mod est automatiquement chargé et disponible.

## Utilisation

- Cliquez sur le bouton **CC** ou utilisez le menu **Paroles (CC)** pour afficher ou masquer le bandeau.
- Le raccourci **Ctrl+Alt+L** est disponible si Capri peut l’enregistrer.
- Les paroles se synchronisent automatiquement avec la lecture Spotify.
- La pose de Capri (assis / allongé / aucun) peut être réglée via les commandes du mod ou les paramètres associés.

## Sources de paroles

| Source | Type | URL |
|--------|------|-----|
| lrclib.net | Synchronisées + simples | https://lrclib.net |
| lyrics.ovh | Simples | https://api.lyrics.ovh |

Quand le bandeau est affiché, le titre, l'artiste, l'album et la durée du morceau en cours (dans n'importe quelle appli, pas seulement Spotify) sont envoyés à lrclib.net, et le titre et l'artiste à api.lyrics.ovh.

## Cache

Les paroles récupérées sont mises en cache localement dans le dossier du mod (fichier `lyrics-cache.jsonl`) pour un affichage instantané lors des écoutes répétées.

## Informations techniques

| Champ | Valeur |
|-------|--------|
| **ID** | `capri-lyrics` |
| **Nom** | Capri Lyrics |
| **Version** | 1.4.0 |
| **Auteur** | Suoh |
| **API requise** | 3 |
| **Permissions** | music, hotkeys |
| **Langage** | C# 5 (.NET Framework 4) |

## Compatibilité

Capri Desktop 0.8.9 sous Windows uniquement.

## Licence

Mod communautaire. La redistribution est autorisée avec mention de l'auteur d'origine.

Les visages de Capri affichés par le mod viennent de [Capri](https://github.com/lachydotmcg/capri-desktop).

---
*README généré pour l'upload du mod `capri-lyrics.capri-code`.*