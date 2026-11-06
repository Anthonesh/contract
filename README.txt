PACTE DES INTENTIONS SCANDALEUSES - VERSION 2
==============================================

CONTENU :
  index.html            La page web responsive (sort, parchemin, contrat, signature)
  audio/LISEZ-MOI.txt   Consignes pour le vocal et la musique optionnelle

DEMARRAGE :
  1) Décompresse tout le ZIP, sans effacer le dossier audio.
  2) Ouvre index.html dans un navigateur pour tester les animations,
     le contrat et la signature.
  3) Pour le lecteur YouTube, il faut héberger la page sur un site HTTPS
     (par exemple GitHub Pages) ou lancer un serveur HTTP local.
     Windows depuis le dossier du projet : py -m http.server 8000
     Puis visite : http://localhost:8000
  4) Sur mobile, publie l'ensemble sur GitHub Pages et ouvre l'URL HTTPS.

MUSIQUE YOUTUBE :
  https://www.youtube.com/watch?v=3tAJeLNZ62M
  Erreur 153 = absence de Referer HTTP, fréquente sur file://.
  L'URL HTTPS corrige le contexte, mais lecture auto et disponibilité
  de la vidéo restent soumises aux règles de YouTube et du navigateur.

SIGNATURE :
  Signer avec doigt/souris, puis « Sceller le pacte ».
  Le bouton « Enregistrer en PDF » ouvre l'impression :
  sélectionner « Enregistrer au format PDF » sur le navigateur.
  La signature reste dans le navigateur : aucun envoi serveur.

EFFETS VISUELS :
  Ni stroboscope ni flashes, animations douces,
  bouton « animations minimales », prefers-reduced-motion respecté.
  Une sensibilité à l'épilepsie reste individuelle : tester prudemment.

