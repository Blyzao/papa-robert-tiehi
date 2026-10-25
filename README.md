# En mémoire de Papa Robert TIEHI

Site d'hommage à Papa Robert TIEHI (1er janvier 1944 – 2 octobre 2026), instituteur et patriarche de Facobly.

**Site en ligne : https://blyzao.github.io/papa-robert-tiehi/**

Réalisé par [Blyzao](https://github.com/Blyzao), en octobre 2026, pour la grande famille TIEHI.

## Contenu

- Écran d'ouverture avec une bougie et deux colombes. Le bouton « Entrer » lance la musique et le défilement automatique.
- Accueil : le portrait dans une couronne de lys, qui zoome lentement. Une colombe traverse l'écran.
- Sa vie : courte biographie, illustrée d'un diaporama de portraits.
- Un héritage : l'instituteur, le patriarche, la joie de vivre.
- Avis de décès, avec la liste des familles.
- Programme des obsèques : compte à rebours, frise des trois jours et liens Google Maps.
- Souvenirs : galerie de photos en carrousel 3D, avec agrandissement au clic.
- Soutenir la famille : numéros Wave, Orange Money et MTN Mobile Money, avec un bouton pour copier le numéro.
- Verset biblique (2 Timothée 4:7) et remerciements.
- Pas de formulaire.

## Fichiers

- `index.html` : tout le site (structure, styles et scripts). Les réglages sont dans l'objet `REGLAGES`, en haut du script : date de la levée du corps, liste des photos de la galerie, numéros de soutien, vitesse du défilement.
- `img/` : les photos optimisées, et `apercu.jpg`, l'image affichée quand on partage le lien (WhatsApp, Facebook).
- `ornements/` : les colombes, lys, coins et frises à l'aquarelle (PNG transparents). Un ornement absent est simplement ignoré.
- `musique/musique.mp3` : jouée à l'ouverture, avec un bouton pour la couper.

## Tester en local

```bash
python -m http.server 8765
```

Puis ouvrir http://localhost:8765. Ajouter `?apercu` à l'adresse affiche tout le contenu d'un coup, sans écran d'ouverture.

## Partager le lien

Pour forcer WhatsApp à afficher le nouvel aperçu après une modification, partagez une variante de l'adresse, par exemple `https://blyzao.github.io/papa-robert-tiehi/?hommage`.

## Droits

- **Code** (HTML, CSS, JavaScript) : licence MIT, voir [LICENSE](LICENSE).
- **Photos et textes** : propriété de la famille TIEHI. Tous droits réservés, aucune réutilisation sans son accord.
- **Ornements** : illustrations générées par IA pour ce site. Tous droits réservés.
- **Musique** : « Mon meilleur ami », de Rosny Kayiba. Œuvre protégée, propriété de ses ayants droit, utilisée ici dans un cadre familial non commercial. À retirer sur simple demande.
- **Polices** : Cormorant Garamond, EB Garamond et Great Vibes (Google Fonts, licence SIL Open Font License).
