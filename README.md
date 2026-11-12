<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="images/logo-fond-fonce.svg">
    <img src="images/logo-fond-clair.svg" alt="Blue Box Labs" width="340">
  </picture>
</p>

# Blue Box DAW

Un logiciel de mixage pour Windows, simple à prendre en main. On ouvre les pistes séparées d'un morceau (voix, batterie, basse, guitares…), on règle chaque piste, on écoute, on exporte le mix.

![La fenêtre de Blue Box DAW : les pistes à gauche, leurs formes d'onde à droite](images/ecran.png)

## Installer

1. Télécharger `BlueBoxDAW_…_x64-setup.exe` sur la page de la [dernière version](../../releases/latest).
2. Lancer le fichier. Windows affiche « éditeur inconnu » : cliquer sur « Informations complémentaires », puis « Exécuter quand même ». Le logiciel n'a pas de certificat payant, c'est tout.
3. Ouvrir le logiciel, puis glisser dans la fenêtre le dossier qui contient les pistes du morceau, en WAV, FLAC ou MP3.

Windows 10 ou 11, 64 bits.

## Mises à jour

Au lancement, le logiciel regarde s'il existe une version plus récente. Si oui, il dit ce qui change et propose de l'installer. Les morceaux, les presets et les réglages restent en place.

## Sur chaque piste

- Volume, pan, muet, solo, avec un niveau stéréo et un témoin de saturation.
- Égaliseur à cinq bandes et deux coupes, avec le spectre du son derrière la courbe.
- Compresseur, avec sa courbe et la réduction affichée en direct.
- Dé-esseur, pour les « s » qui sifflent.
- Reverb, avec six pièces toutes faites.
- Niveleur automatique et normalisation, pour une voix dont le niveau bouge.
- 24 presets par instrument, et les vôtres.

## Sur le mix entier

- Égaliseur général, largeur stéréo, écoute en mono.
- Limiteur : le mix ne sature plus, même poussé fort.
- Morceau de référence : un disque que vous aimez, à comparer d'une touche avec votre mix, au même volume.
- Mesure du volume (LUFS) et de la crête.

## Retoucher les pistes

- Scinder une piste, retirer un passage (une toux, une phrase parlée), le raccourcir, le déplacer.
- Copier un bout qui est bon pour reboucher un passage raté.
- Volume et fondus propres à chaque clip.
- Boucle sur un passage, zoom, marqueurs avec texte.

Le fichier audio d'origine n'est jamais modifié, et tout s'annule avec Ctrl+Z.

## Exporter

En WAV 24 bits, en FLAC 24 bits ou en MP3 à 320 kbit/s, au volume du mix ou à un volume choisi (par exemple celui des plateformes de streaming).

## Raccourcis utiles

| Touche | Effet |
|---|---|
| Espace | Lecture ou pause |
| M, S | Couper la piste choisie, l'écouter seule |
| T | Scinder à la tête de lecture |
| B | Boucle |
| N | Poser un marqueur |
| R | Basculer entre le mix et le morceau de référence |
| Ctrl + molette | Zoomer sur la ligne de temps |
| Ctrl + Z | Annuler |

Le bouton « ? » en haut à droite du logiciel donne la liste complète.

## Licences

Le logiciel est écrit en Rust, avec Tauri pour la fenêtre. Il utilise des bibliothèques libres, dont l'encodeur MP3 [LAME](https://lame.sourceforge.io) (licence LGPL). La liste complète est fournie sur demande.
