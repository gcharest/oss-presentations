# Ouvert par défaut

**Guillaume Charest**

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

Petite parenthèse - Combien sont familiers avec logiciels libres?

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

## Conditions

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

## Types de licences libres

---

### Permissive

>Vous permet de faire essentiellement tout ce que vous voulez avec le logiciel et même le distribuer sous une licence différente.

---

### Réciproques (Copyleft)

>Vous permet de faire essentiellement tout ce que vous voulez avec le logiciel **mais** nécessite que la distribution soit faite sous la même licence que vous l'avez obtenu.

---

## Licences très connues

* MIT License (Expat)
* Apache License 2.0 (Apache-2.0)
* BSD 3-Clause License (Revised)
* Mozilla Public License 2.0 (MPL-2.0)
* GNU General Public License v3 (GPL-3)
* GNU Affero General Public License v3 (AGPL-3.0)

Utilisez [TL;DR Legal](https://tldrlegal.com) pour faciliter votre recherche

Note:

- 3 premières sont permissives
- 3 dernières sont réciproques

--

### Utilisation

---


## Using

without modifications

--

>Provided 'as-is'

Consider the software with the same responsibility lenses as if you had written it.

--

[Excerpt from US Defense OSS FAQ](https://dodcio.defense.gov/Open-Source-Software-FAQ/#Q:_Is_open_source_software_commercial_software.3F_Is_it_COTS.3F):
> Open source software that has at least one non-governmental use, and has been or is available to the public, is commercial software. If it is already available to the public and is used unchanged, it is usually COTS.

--

| Standalone | Combination of components | Development and deployment |
| ---------- | ------------------------- | -------------------------- |
| Web browser, Productivity suite, Operating system and utilities (Window manager, Desktop environment, Text editor, Console..), .. | Application and plugins with database and web server | Custom development using open source software programming languages and dependencies, HTTP server, Database management system, Container platform |

--

# Support Model

Internal or External

---

## Using

with modifications

--

## Considerations

See [Draft Guidelines on Licences](https://github.com/canada-ca/open-source-logiciel-libre/blob/master/en/guides/using-open-source-software.md#verify-open-source-software-ownership-or-licence)


--

You're working in the open:

--

## Why bother

> It looks like a lot of work...

--

Technically, you manages thousands of licences already...

--

* Don't start with a blank canvas, focus on the added value
* Speed up development time by reusing existing solutions to common problems
* Leverage a large community of peers to enhance quality and for wider maintenance
* Build on top of giants' shoulders and communities

--

> Aspiring to world class is not enough, when everyone else starts there

Jeff McAffer, formerly Director of Microsoft's Open Source Program Office

-- 

[2018 Open Source Security and Risk Analysis](https://www.synopsys.com/content/dam/synopsys/sig-assets/reports/2018-ossra.pdf), Synopsys Center for Open Source Research & Innovation
