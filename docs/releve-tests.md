# Relevé des tests

> Écrivez le résultat attendu avant d'essayer. Un écart n'est pas une faute : notez-le, corrigez, refaites le test.

**Calculs à la main** :

Nombre  total d'observations : 10
pH minimum 4,8 - observation S04
pH maximum 7,6 - observation S08
Nombre de sols sableux : 3
Nombre de sols limoneux : 4
Nombre de sols argileux : 3
Points dont le pH est strictement inférieur à 5,5 : S01, S04, S06, S09

#Vérification des observation du comptage par texture 

Sableux : S01, S04, S08 = 3 observations
Limoneux : S02, S05, S07, S10 = 4 observations
Aegileux : S03, S06, S09 = 3 observations


**Essais dans le menu** : un ajout valide (encore là après redémarrage), chaque règle refusée, une recherche introuvable, chaque tri, la synthèse, un choix inconnu.

| Action | Attendu | Obtenu | Testeur |
|---|---|---|---|
| Ajout d'une observation valide | L'observation est acceptée et enregistrée | Observation ajoutée avec succès. | Koffi Boagr VIEGNEKOU |
| Conservation après redémarrage | L'observation ajoutée reste présente après le redémarrage | À vérifier | Koffi Boagr VIEGNEKOU |
| Ajout avec pH = 14,1 | La saisie est refusée | refusée | Koffi Boagr VIEGNEKOU |
| Recherche S99 | Aucun résultat trouvé | Choix inconnu : retour au menu. Test de recherche à refaire. | Koffi Boagr VIEGNEKOU |
| Tri par pH | Les observations sont classées selon le pH croissant | Observations classées par pH dans l'ordre croissant. | Koffi Boagr VIEGNEKOU |
| Synthèse | Les valeurs calculées correspondent aux calculs manuels | pH minimum : 4,8 ; pH maximum : 7,6. | Koffi Boagr VIEGNEKOU |
| Choix inconnu | Le programme refuse le choix et continue | Choix inconnu : « 99 ». Tapez un chiffre du menu. | Koffi Boagr VIEGNEKOU |

## 4. Vérification sur un autre poste

**Objectif :** Vérifier que le projet peut être récupéré et exécuté sur un autre ordinateur à partir du dépôt GitHub.

Commandes utilisées :

```bash
git clone https://github.com/beneaxeljunior95-hue/brief-3-carnet-sols.git
cd brief-3-carnet-sols
node app.js
npm test
```

**Résultat attendu :**
- Le dépôt est correctement cloné.
- L'application démarre sans erreur.
- Le menu principal s'affiche.
- Les tests automatiques s'exécutent correctement.

**Testeur :** Koffi Boagr VIEGNEKOU

**Sur un autre poste** (`git clone`, `node app.js`, `npm test`, en suivant le README) : ✏️
