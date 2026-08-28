# Sinistr — démonstration

Site vitrine une page de **Sinistr**, restauration après sinistre dans le Grand
Montréal. Démonstration destinée à validation client. Le domaine `sinistr.ca`
n'est pas touché.

En ligne : <https://hostnextline.github.io/sinistr/>

## Le formulaire

Il n'est **pas branché**. La constante `ENDPOINT_FORMULAIRE`, en haut du script
de `index.html`, est vide : tant qu'elle l'est, le formulaire le dit clairement
et renvoie vers le téléphone. Il ne peut jamais afficher un faux succès.
Renseignez une URL qui accepte un POST JSON `{nom, telephone, courriel, message}`
et il fonctionne.

## Contenu

Un seul fichier autonome, `index.html` : styles et script inclus, aucun build,
aucune dépendance externe. Bilingue par balisage jumelé `.fr` / `.en` — toute
chaîne ajoutée doit exister dans les deux langues.

`og.html` sert uniquement à régénérer la carte de partage.

Aucun témoin, aucun traceur, aucun appel à un domaine tiers.
