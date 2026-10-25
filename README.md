# En mémoire de Papa Robert TIEHI

Site d'hommage à Papa Robert TIEHI (1er janvier 1944 – 2 octobre 2026), instituteur et patriarche de Facobly.

Site en ligne : https://blyzao.github.io/papa-robert-tiehi/

## Contenu

- Écran d'ouverture avec une bougie, puis la photo d'accueil qui zoome lentement.
- Biographie illustrée d'un diaporama de portraits.
- Faire-part, programme des obsèques avec compte à rebours, galerie de photos en carrousel 3D, verset biblique.
- Défilement automatique, qui s'arrête dès qu'on touche l'écran et reprend après 8 secondes.
- Pas de formulaire.

## Fichiers

- `index.html` : tout le site (structure, styles et scripts). Les réglages sont dans l'objet `REGLAGES`, en haut du script.
- `img/` : les photos optimisées et `apercu.jpg`, l'image affichée quand on partage le lien (WhatsApp, Facebook).
- `musique/musique.mp3` (facultatif) : si ce fichier existe, la musique se lance à l'ouverture et un bouton permet de la couper.

## Tester en local

```bash
python -m http.server 8765
```

Puis ouvrir http://localhost:8765. Ajouter `?apercu` à l'adresse affiche tout le contenu d'un coup, sans écran d'ouverture.

## Droits

Les photos appartiennent à la famille TIEHI. Tous droits réservés.
