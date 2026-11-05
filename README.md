# Carnet d'observation des sols

> Projet individuel du SAS DFS, brief 3 (sujet : [SUJET.md](SUJET.md)). Remplacez chaque ✏️ par votre texte, puis supprimez cette ligne.

## Contexte

Dans le cadre des activité de la ferme pédagogique, des observations sont effectuées sur differentes parcelles afin de recueillir des informations sur les caractéristiques du sol.
Le programme permet d'enregistrer cinq informations principales : l'identifiant du point observé, la parcelle, la texture du sol, le pH et l'état d'humidité.
les informations sont conservées dans fichier JSON (donnees/observations.js) afin de pouvoir être consultées ultérieurement.
l'appplication propose également plusieurs opérations : ajoute une observation, afficher les données enregistrées, effectuer des recherches, classer les observations selon leur pH et produire une synthèse.
les observations présentant un pH inférieur à 5,5 sont signalées pour être examinées avec le coach. Ce seuil est uniquement utilisé comme repère pédagogique et ne constitue pas un diagnostic agronomique.


## Prérequis et lancement

- Node.js 20 ou plus récent, Git ; aucune bibliothèque à installer.

```bash
git clone https://github.com/VOTRE-COMPTE/brief-3-carnet-sols.git
cd brief-3-carnet-sols
node app.js
npm test
```

Sous PowerShell, si `npm` est bloqué : `npm.cmd test`.

## Fonctionnalités

✏️ *Cochez seulement ce qui marche : `- [x]`.*

- [X] Données lues et enregistrées dans `donnees/observations.json`
- [X] Ajouter une observation, saisies invalides refusées sans arrêter le programme
- [X] Lister les observations, message si le carnet est vide
- [X] Rechercher par point ou par parcelle ; filtrer par texture
- [X] Trier par pH
- [X] Synthèse : pH minimum et maximum, nombre par texture, points à discuter (pH < 5,5)
- [X] Bonus : supprimer et modifier une observation (choix 6 et 7)
- [X] Bonus : tri par pH décroissant, texture la plus fréquente

## Données

✏️ *Le fichier, le nombre d'observations, les champs (voir [docs/dictionnaire-donnees.md](docs/dictionnaire-donnees.md)), le pH sans unité. Rappelez qu'elles sont fictives.*

Les données utilisés dans cette étude sont issues d'un fichier de données contenant des observation relatives aux caractéristiques du sol.Elles comprennent les informations sur les parcelles, la texture du sol, le pH et l'état d'humidité.

Important : les données présentées sont entièrement fictives.Elles sont utilisées uniquement à des fins pédagogiques et pour illustrer le fonctionnement du projet.

Fichier : fichier de donnnées situé dans dossier donnnees/ .
Nombre d'observations : à préciser selon le contenu du fichier.
Nombre de champs : 5( id, parcelle, texture, pH, etatHumidite).
Unité du pH : le pH est sans unité

## Limites

Le programme ne réalise pas d'analyse chimique complète du sol.
Le programme ne formule aucune recommandation de fertilisation ou de correction du sol.
Les données sont fictives et ne permettent pas de représenter précisément les caractéristiques réelles des sols.

## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

✏️ *Prénom NOM, compte GitHub. Entraide : avec qui, sur quoi.*
Prénom NOM : Axel Junior BENE
compte GitHub : beneaxeljunior95-hue
Entraide : KAMBOU Xavier Romeo, ADOM Grace Victoire, DJANGON Junior, KOUAME Brou Grace Emmanuella 
Nature de l'entraide : échanges et partage de connaissances, assistance dans la compréhension des consignes, la rédaction du code et la résolution des difficultés rencontrées au cours du projet

