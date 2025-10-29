

---

<div align="center">

# 🏛️ Koru Audit Framework

*Un système de gouvernance LLM/SLM pour des analyses stratégiques et création produit rigoureuses*

[![Licence: CC BY-NC-SA 4.0](https://img.shields.io/badge/Licence-CC%20BY--NC--SA%204.0-ef9421.svg?style=for-the-badge&logo=creative-commons)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Status](https://img.shields.io/badge/Status-En%20Développement-2ea44f?style=for-the-badge&logo=github)](https://github.com/votre-utilisateur/votre-repo)
[![Version](https://img.shields.io/badge/Version-0.1.0-0052cc?style=for-the-badge&logo=git)](https://github.com/votre-utilisateur/votre-repo/releases)

</div>

## 📋 Table des Matières

- [🏛️ Koru Audit Framework](#️-koru-audit-framework)
  - [📋 Table des Matières](#-table-des-matières)
  - [✨ Fonctionnalités](#-fonctionnalités)
    - [🎯 Le Concept](#-le-concept)
  - [🎯 Le Concept en Parallèle : Processus \& Architecture](#-le-concept-en-parallèle--processus--architecture)
  - [🚀 Démarrage Rapide](#-démarrage-rapide)
      - [1. Initialisation des Agents](#1-initialisation-des-agents)
      - [2. Lancement de l'Analyse de Conjoncture](#2-lancement-de-lanalyse-de-conjoncture)
      - [3. Définition de la Mission](#3-définition-de-la-mission)
  - [📂 Structure du Dépôt](#-structure-du-dépôt)
  - [🧠 Concepts Fondamentaux](#-concepts-fondamentaux)
  - [📜 Licence](#-licence)
    - [Pour plus de détails, consultez le fichier `LICENSE` du dépôt](#pour-plus-de-détails-consultez-le-fichier-license-du-dépôt)

## ✨ Fonctionnalités

<div align="center">

| 🔍 Analyse Stratégique | 🛡️ Contrôle Qualité | 🤖 Architecture d'Agents |
|----------------------|-------------------|-------------------------|
| Transforme les intentions en analyses actionnables | Protocole en double boucle pour une qualité optimale | Hiérarchie d'agents spécialisés |

</div>

Koru est un cadre opérationnel qui traite l'interaction avec les IA comme une discipline d'ingénierie. Basé sur une hiérarchie d'agents et un protocole d'audit rigoureux, il vise à transformer une intention stratégique en une analyse factuelle, actionnable et à faible risque d'hallucination.

---

### 🎯 Le Concept

Ce projet n'est pas une simple collection de prompts. C'est un **système de gouvernance** complet qui s'appuie sur deux piliers fondamentaux :



## 🎯 Le Concept en Parallèle : Processus & Architecture

Le système Koru repose sur la synergie de deux concepts fondamentaux : le **processus** (le "comment") et l'**architecture** (le "qui"). Les visualiser côte à côte permet de comprendre instantanément comment la structure des agents sert le cycle de vie de chaque mission.

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <h3>Pilier 1 : Le Processus en Boucle Supervisée</h3>
      <p><em>(Le "Comment")</em></p>
      <p>Ce schéma décrit le <strong>cycle de vie d'une tâche</strong>. Nous validons d'abord la qualité du prompt avant de valider celle du résultat, chaque étape étant supervisée par l'Architecte.</p>
    </td>
    <td align="center" valign="top" width="50%">
      <h3>Pilier 2 : L'Architecture des Agents</h3>
      <p><em>(Le "Qui")</em></p>
      <p>Ce schéma présente la <strong>structure de l'équipe</strong>. Le travail est réparti entre des agents spécialisés dont le dialogue garantit la pertinence et la faisabilité de l'analyse.</p>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src="docs/svg/protocol-double-loop-audit.svg" alt="Schéma du Processus en Boucle">
    </td>
    <td valign="top">
      <img src="docs/svg/architecture.svg" alt="Schéma de l'Architecture des Agents">
    </td>
  </tr>
</table>

## 🚀 Démarrage Rapide

Suivez ces étapes pour mener une analyse complète.

#### 1. Initialisation des Agents
Avant de commencer, chargez les *personnalités* des agents dans votre outil LLM (par ex. en tant que "Custom Instructions" / "Prompt Système").

- **Agent Manager Technique :** Copiez le contenu de `equipe-d'audit_prompt kgb/manager.md`.
- **Agent Visionnaire :** Copiez le contenu de `equipe-d'audit_prompt kgb/visionnaire.md`.

#### 2. Lancement de l'Analyse de Conjoncture
C'est le point de départ de toute mission. Envoyez le contenu du fichier suivant comme premier message pour établir le contexte.

- `equipe-d'audit_prompt kgb/conjoncture-audit.md`

#### 3. Définition de la Mission
Une fois la conjoncture établie, formulez votre besoin précis dans un nouveau message.

> **Exemple :** *"Je veux une analyse de marché sur les outils de productivité basés sur l'IA pour les freelances en Europe."*

## 📂 Structure du Dépôt

```txt
.
├── docs/                               # Documentation des    protocoles et de l'architecture
│   ├── protocol-double-loop-audit.mmd  # Schéma de l'audit en deux étapes
│   ├── formalisation_protocole-kgb.md  # Règles du dialogue entre agents
│   └── sys.mmd                         # Schéma de l'architecture système
├── equipe-d'audit_prompt kgb/          # Prompts et personnalités des agents
│   ├── conjoncture-audit.md            # Prompt d'initialisation de mission
│   ├── manager.md                      # Personnalité de l'Agent Manager
│   └── visionnaire.md                  # Personnalité de l'Agent Visionnaire
└── README.md                           # Ce fichier
```
*(Note : Le fichier `visionaire.md` semble être un doublon ou une coquille et a été omis pour plus de clarté.)*

## 🧠 Concepts Fondamentaux

Pour comprendre la logique de ce framework, consultez la documentation :

- **Protocole à Double Boucle :** (`docs/protocol-double-loop-audit.mmd`) Explique notre méthodologie QA (Contrôle Qualité) qui valide la requête avant d'exécuter la tâche.
- **Protocole KGB :** (`docs/formalisation_protocole-kgb.md`) Formalise le dialogue "contradictoire" mais constructif entre les agents pour affiner les spécifications.

## 📜 Licence

Ce projet et son contenu sont distribués sous la licence **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International**.

[![Licence Creative Commons](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

En résumé, vous êtes libre de :
- **Partager** — copier et redistribuer le matériel sur n'importe quel support ou format.
- **Adapter** — remixer, transformer et construire à partir du matériel.

Sous les conditions suivantes :
- **Attribution** — Vous devez créditer l'auteur.
- **Pas d'Utilisation Commerciale** — Vous ne pouvez pas faire un usage commercial de ce travail.
- **Partage dans les Mêmes Conditions** — Si vous modifiez ce travail, vous devez distribuer vos contributions sous la même licence.

### Pour plus de détails, consultez le fichier `LICENSE` du dépôt

  > https://creativecommons.org/licenses/by-nc-sa/4.0/deed.fr
