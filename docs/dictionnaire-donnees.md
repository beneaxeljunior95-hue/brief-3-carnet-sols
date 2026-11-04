# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ | Signification | Type | Règle de validation | Unité | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | Identifiant unique | texte | non vide, absent des données | — | S01 |
| parcelle |portion de terrain délimitée permettant d'identifier la parcelle sur laquelle le point est observé |texte |obligatoire et non vide |-|P1 | 
| texture |Indique la classe texturale du sol observé |texte|valeur autorisée : sableux, limoneux ou argileux |- | argileux|
| pH |il représente le niveau d'acidité ou d'alcalinité du sol au point observé | nombre|Doit être un nombre compris entre 0 et 14 |-|8|
| etatHumidite |Indique l'état d'humidité du sol observé |texte |Accepte uniquement :sec,intermediaire ou humide |-|humide |

**Listes de valeurs autorisées** : 

. texture : sableux, limoneux, argileux.

. etat d'humidité : sec, intermediaire, humide.

. pH : nombres compris entre 0 et 14

**Sources** : 

. dictionnaire de l'expert C: Sol et capteur de Sol

. SUJET.md (données)
