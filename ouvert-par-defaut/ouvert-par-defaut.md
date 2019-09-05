# Ouvert par défaut

## Guillaume Charest

Conseiller principal, Emploi et développement social Canada

Rôle précédent: Lead pour le logiciel libre, Secrétariat du conseil du trésor du Canada

---

Présentation de la vision pour un gouvernement numérique et comment l’adoption d’une approche ouverte axée sur l’interopérabilité et la collaboration font partie intégrale de nos principes directeurs

--

## Vision et Politiques

---

![Normes numériques du GC](../assets/normes-numeriques.png)

[Lien vers le site des Normes numériques du gouvernement du Canada](https://www.canada.ca/fr/gouvernement/systeme/gouvernement-numerique/normes-numeriques-gouvernement-canada.html)

Note:

- [Travailler ouvertement part défaut]
- [Utiliser des normes et des solutions ouvertes]
- [Collaborer largement]

---

4 décembre 2018:

Mise à jour de la [Directive sur la gestion des technologies de l'information](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=15249)

1 avril 2020:

Entrée en vigueur de la nouvelle [Directive sur les services et le numérique](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32601)

Note:

Ces directives sont importantes

- Changement drastique direction
- Force les départements modifier leur approche

---

[Annexe: Procédures obligatoires pour l'évaluation de l'architecture intégrée](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=32602)

Note:

Donner une approche intégrée pour la gestion des TI

---

[A.2.3.8 Utiliser des normes et des solutions ouvertes par défaut](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=32602#claA.2.3.8)

Note:

1. Logiciel libre et normes ouvertes
2. Logiciel propriétaire avec API, format données standard ouvert
3. Développement interne relâché publiquement sous licence libre

---

[A.2.3.9 Maximiser la réutilisation.](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=32602#claA.2.3.9)

Note:

- Exploiter et réutiliser les solutions, composantes et processus existants
- Solutions d'organisation > solution département
- Partager le code publiquement si possible

---

[A.2.3.10 Permettre l'interopérabilité](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=32602#claA.2.3.10)

Note:

- Exposer toutes les fonctionnalités en tant que services
- Exécuter chaque service de la TI dans son propre processus
- Exécuter des applications dans des conteneurs
- Plateforme d'échange numérique du GC pour les composants tels que l'IPA Store, la messagerie et le bus de service du GC.

--

## Logiciels libres

Note:

- Petite parenthèse - Combien sont familiers avec logiciels libres?
- Concept méconnu au Gouvernement du Canada

---

>Logiciel disponible sous une licence libre

Guides en développement au Gouvernement du Canada considèrent les licences de la *Open Source Initiative* et de la *Free Software Foundation* comme les seules licences acceptées.

Note:

La Beer Licence, pas une bonne idée

---

### Droits de base

1. Utiliser le logiciel comme vous le voulez
2. Étudier le code source
3. Modifier le code source
4. Redistribuer le logiciel

---

### Conditions

1. Avis
2. Licence pour le travail dérivé

Note:

Dépend du type de licence

---

## Ce n'est pas libre

Si vous avez seulement accès au code source

>Vous **devez** avoir obtenu les droits basés sur une licence libre

Note:

Ex.: Droits négociés lors de contrats

---

### Types de licences libres

---

### Permissive

>Vous permet de faire essentiellement tout ce que vous voulez avec le logiciel et même le distribuer sous une licence différente.

---

### Réciproques (Copyleft)

>Vous permet de faire essentiellement tout ce que vous voulez avec le logiciel **mais** nécessite que la distribution soit faite sous la même licence que vous l'avez obtenu.

---

### Licences très connues

- MIT License (Expat)
- Apache License 2.0 (Apache-2.0)
- BSD 3-Clause License (Revised)
- Mozilla Public License 2.0 (MPL-2.0)
- GNU General Public License v3 (GPL-3)
- GNU Affero General Public License v3 (AGPL-3.0)

Utilisez [TL;DR Legal](https://tldrlegal.com) pour faciliter votre recherche

Note:

- 3 premières sont permissives
- 3 dernières sont réciproques

---

### Utilisation

>Partagé 'tel quel'

Considérez votre responsabilité d'utilisation de la même façon que si vous l'aviez développé vous-même

Note:

Possible de discuter l'utilisation après la présentation

---

### Avec ou sans modification

Contribuez aux projets que vous utilisez

Note:

- C'est la bonne chose à faire
- Vous transférer la maintenance du projet à la communauté
  - Code
  - Documentation
  - Bogues
  - Idées
  - Traduction
  - Accessibilité
  - Financement de projets si possible

---

[Extrait du département de la FAQ Logiciels Libres de la défense des É.-U.](https://dodcio.defense.gov/Open-Source-Software-FAQ/#Q:_Is_open_source_software_commercial_software.3F_Is_it_COTS.3F):
> Les logiciels libres qui ont au moins un usage non gouvernemental et qui ont été ou sont mis à la disposition du public sont des logiciels commerciaux. S'il est déjà mis à la disposition du public et qu'il est utilisé tel quel, il s'agit habituellement d'un système commercial.

---

>Viser à être une organisation de niveau mondiale n'est pas suffisant quand tout le monde y commence

Jeff McAffer, ancien Directeur du Bureau de programme de logiciels libres, Microsoft

Source: [Présentation](https://canada-ca.github.io/ofd-joep/en/open-first-day-agenda-details.html#open-source-at-scale) (Anglais)

Note:

Son point étant:

- Les logiciels libres sont maintenant utilisés dans pratiquement toutes les solutions disponibles
- La qualité des logiciels libres surpasse un projet interne à ressources limités
- Intelligence artificielle, infonuagique, chaines de bloc (blockchain), etc.

---

> C'est essentiellement les sciences économiques appliquées au génie logiciel

Stephen Walli, Gestionnaire principal de programme, Microsoft

Source: [Présentation](https://canada-ca.github.io/ofd-joep/en/open-first-day-agenda-details.html#the-engineering-economics-of-open-source) (Anglais)

Note:

Son point étant:

- Impossible d'embaucher tout le monde
- Développement logiciel de qualité est difficile
- Focus sur la valeur ajoutée

--

## Travailler ouvertement

Note:

- Pourquoi je vous ai parlé autant de logiciels libres?
- Pas une panacée
- C'est une façon de travailler plus qu'un logiciel

---

Transparence et Confiance

Note:

- Plus de 10 ans au gouvernement fédéral
- N'était pas dans mes plans de carrière
- Le portrait social a drastiquement changé
  - Fausse nouvelles
  - Collusion
  - Jeux de pouvoir
  - Changement d'administrations
- La lumière est le meilleur désinfectant

---

Interopérabilité

Note:

- Architectures orientées service
- Micro-services
- Découplement des solutions
- Interfaces de programmation (APIs)
  - Réutilisation des services
- Diminuer situation de verrouillage envers les vendeurs
  - Toujours verrouillage possible (technologie, produit, formats, etc.)

---

Collaboration

Note:

- Ressources limitées
- Défis sont croissants
  - Attentes du public
  - Rapidité des changements technologiques
  - Implications légales et éthiques
- DevOps

---

Logiciels libres

Note:

- Résoudre des problèmes communs de façon ouverte
- Coalescence naturelle vers les projets

--

## Exemples de projets

---

### Évaluation de l'Incidence Algorithmique

Projet lancé pour l'utilisation responsable et éthique de l'intelligence artificielle

Licence: MIT

Cité: [Observatoire de l'innovation du secteur publique](https://oecd-opsi.org/toolkits/algorithmic-impact-assessment/)

Note:

- 2 développeurs
- 3 semaines à temps partiel
- Librairies de logiciels libres
  - Vue.js
  - Survey.js
  - [Boîte à outils de l'expérience Web](https://wet-boew.github.io/v4.0-ci/index-fr.html)
- Contributions:
  - 8 contributeurs externes

---

### Échange de ressources ouvert

Projet lancé pour partager nos ressources ouvertement au Canada

- Projets de logiciels libres **créés** par les administrations publiques
- Logiciels libres tiers **utilisés** par les administrations publiques
- Normes ouvertes utilisés dans les administrations publiques

Licence: MIT

Note:

- 1 employé à temps partiel
- Montréal rejoint le projet
- Edmonton
- 20 contributeurs/contributrices en tout

--

## Merci
