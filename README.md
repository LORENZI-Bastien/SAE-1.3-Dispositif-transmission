# SAÉ 1.3 · Découvrir un dispositif de transmission

> Étude de la transmission Wi-Fi et comparaison de la puissance reçue pour trois types d’antennes.

| | |
|---|---|
| **Formation** | BUT Réseaux et Télécommunications, Montbéliard |
| **Année** | 1<sup>re</sup> année, semestre 1 |
| **Outils et notions** | `Wi-Fi` `Antennes` `Équation de Friis` `dBm` `DD-WRT` |

## Objectif

Caractériser trois antennes Wi-Fi de types différents, utilisées sur un réseau réel monté avec un routeur Linksys :

- une antenne **omnidirectionnelle** (antenne d’origine du routeur) ;
- une antenne **directionnelle** (Yagi) ;
- une antenne **sectorielle**.

## Ce que j’ai réalisé

- Mise en place du réseau Wi-Fi de test.
- Calcul de la puissance reçue en fonction de la distance (de 1 à 12 m) avec l’équation de Friis, pour chaque antenne, à partir de la longueur d’onde (0,122 m à 2,4 GHz), des gains et de la puissance émise.

Le sujet prévoyait aussi des mesures de rayonnement à 360°, de pertes dues aux obstacles et une cartographie de couverture : les fichiers de ce dépôt ne documentent que les calculs.

## Contenu du dépôt

| Fichier | Description |
|---|---|
| [`calculs/calcul-puissance-recue-friis.ods`](calculs/calcul-puissance-recue-friis.ods) | Tableaux de calcul de la puissance reçue par antenne |
| [`consignes/sujet-sae-1.3.pptx`](consignes/sujet-sae-1.3.pptx) | Sujet de la SAÉ fourni par l’IUT |

---

<sub>Bastien Lorenzi · BUT Réseaux et Télécommunications, parcours cybersécurité · [Portfolio](https://wonderful-chebakia-f83e9d.netlify.app/#projets) · [Profil GitHub](https://github.com/LORENZI-Bastien)</sub>
