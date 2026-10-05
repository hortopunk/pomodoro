# Pomodoro

Minuteur minimaliste pour smartphone. Une barre rouge traverse l'écran au fil du temps ; le temps restant s'affiche au centre, rouge sur fond blanc et blanc sur fond rouge.

## Fonctionnalités

- Durée configurable (`mm:ss` ou minutes)
- Barre de progression plein écran
- Écran maintenu allumé (Wake Lock)
- Passage automatique en plein écran et en paysage
- Vibration à la fin
- Installable comme application (PWA)

## Utilisation

L'application est statique : `index.html`, `manifest.json` et les icônes `pomodoro.png` et `pomodoro_192.png` suffisent.

Le plein écran, le verrouillage d'orientation et le Wake Lock exigent un contexte sécurisé. Servez les fichiers en HTTPS (GitHub Pages, par exemple) ou via `localhost` :

```bash
python -m http.server 8000
```

## Installation sur Android

1. Ouvrir l'URL de l'application dans Chrome.
2. Menu ⋮ → **Ajouter à l'écran d'accueil**.

Après une modification du manifeste, désinstaller puis réinstaller l'application pour la prendre en compte.
