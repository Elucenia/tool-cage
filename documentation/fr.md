<!-- ELUCENIA technical documentation · cage · fr · no clinical/professional/rights approval -->

# Questionnaire CAGE

[conditions, sources et autorisations](https://elucenia.org/fr/outils/cage)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### C – Avez-vous déjà pensé que vous devriez réduire votre consommation d’alcool ou arrêter de boire ?

`c`

### A – Êtes-vous agacé quand d’autres personnes critiquent votre façon de boire ?

`a`

### G – Vous sentez-vous coupable de votre façon habituelle de boire ?

`g`

### E – Buvez-vous habituellement le matin pour diminuer la nervosité ou la gueule de bois ?

`e`

## Édition de la méthode

CAGE/Ewing 1984 : 4 questions binaires, 0–4, seuil≥2 ; portugais Masur–Monteiro 1983

## Formule documentée

Un point par réponse “oui”: Cut down (réduire), Annoyed (agacé par les critiques), Guilty (culpabilité), Eye-opener (boire au réveil). Seuil : ≥ 2.

## Limites et population

Bref questionnaire de dépistage des problèmes liés à l’alcool, suivi d’une évaluation clinique. La validation brésilienne citée concernait des hommes hospitalisés en psychiatrie ; sa performance ne doit pas être présumée identique dans d’autres populations. La composition de cette cohorte n’est pas une règle universelle d’exclusion selon le sexe.

## Références

- [Ewing JA. Detecting alcoholism: the CAGE questionnaire. JAMA, 1984.](https://doi.org/10.1001/jama.1984.03350140051025)

- [Masur J, Monteiro MG. Validation of the "CAGE" alcoholism screening test in a Brazilian psychiatric inpatient hospital setting. Braz J Med Biol Res, 1983.](https://pubmed.ncbi.nlm.nih.gov/6652293/)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Dépistage négatif

Un CAGE négatif n’exclut pas une consommation à risque actuelle : privilégiez l’AUDIT pour mesurer la consommation.


### 2

Une réponse positive : en dessous du seuil

Demandez la quantité et la fréquence de consommation (AUDIT).


### 3

Dépistage positif (≥ 2) : suspicion d’abus ou de dépendance à l’alcool

Outil de dépistage : confirmer par une évaluation clinique.

