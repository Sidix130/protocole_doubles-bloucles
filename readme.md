
---

<div align="center">

# 🏛️ Koru Audit Framework

*Un système de gouvernance pour LLM/SLM dédié aux analyses stratégiques et à la création de produits.*

[![Licence: CC BY-NC-SA 4.0](https://img.shields.io/badge/Licence-CC%20BY--NC--SA%204.0-ef9421.svg?style=for-the-badge&logo=creative-commons)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Status](https://img.shields.io/badge/Status-En%20Développement-2ea44f?style=for-the-badge&logo=github)](https://github.com/votre-utilisateur/votre-repo)
[![Version](https://img.shields.io/badge/Version-0.1.0-0052cc?style=for-the-badge&logo=git)](https://github.com/votre-utilisateur/votre-repo/releases)
*<p>Sidix130 @Coquery Robin</p>*

</div>

## ✨ Philosophie

Koru n'est pas une simple collection de prompts, mais un **cadre opérationnel** complet qui traite l'interaction avec les IA comme une discipline d'ingénierie. Son but est de transformer une intention stratégique en une analyse factuelle et actionnable, en minimisant le risque d'hallucination grâce à une structure et un processus rigoureux.

<div align="center">

| 🔍 Analyse Stratégique | 🛡️ Contrôle Qualité | 🤖 Architecture d'Agents |
|:--------------------:|:-----------------:|:-----------------------:|
| Traduit une idée brute en un plan d'action validé. | Applique un audit en double boucle pour garantir la pertinence et la fiabilité. | Repose sur une hiérarchie d'agents spécialisés en dialogue constant. |

</div>

---

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
      <img src="docs/assets/protocol-double-loop-audit.svg" alt="Schéma du Processus en Boucle">
    </td>
    <td valign="top">
      <img src="docs/assets/architecture.svg" alt="Schéma de l'Architecture des Agents">
    </td>
  </tr>
</table>

## 🚀 Démarrage Rapide

Suivez ces étapes pour mener votre première analyse structurée.

#### 1. Initialisation des Agents
Chargez les personnalités des agents dans votre outil LLM (via les "Custom Instructions" ou en tant que premier prompt système).

- **Agent Manager Technique :** `equipe-d'audit_prompt kgb/manager.md`
- **Agent Visionnaire :** `equipe-d'audit_prompt kgb/visionnaire.md`

#### 2. Lancement de l'Analyse de Conjoncture
Toute mission commence par établir un contexte partagé. Envoyez le contenu de ce fichier comme tout premier message.

- `equipe-d'audit_prompt kgb/conjoncture-audit.md`

#### 3. Définition de la Mission
Une fois la conjoncture établie, formulez votre besoin précis dans le message suivant.

> **Exemple :** *"Je veux une analyse de marché sur les outils de productivité basés sur l'IA pour les freelances en Europe."*

### 📂 Structure du Dépôt
![!\[alt text\](image.png)
](docs/assets/arboressence.html-1366x768.png)

## 🧠 Concepts Fondamentaux

Pour approfondir la logique de ce framework, consultez la documentation dédiée :

- **Protocole à Double Boucle :** (`docs/protocol-double-loop-audit.mmd`) Détaille la méthodologie de contrôle qualité.
- **Protocole KGB :** (`docs/formalisation_protocole-kgb.md`) Formalise le dialogue contradictoire pour affiner les spécifications.

## 📜 Licence

Ce projet est distribué sous la licence **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International**.

[![Licence Creative Commons](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

Vous êtes libre de **partager** et **d'adapter** ce travail à des fins **non commerciales**, à condition de **créditer l'auteur** et de **partager vos créations sous la même licence**.

Pour le texte légal complet, consultez le fichier `LICENSE` inclus dans ce dépôt.
