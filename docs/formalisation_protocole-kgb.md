
---

### **"Protocole d'Audit en Double Boucle"**

#### **Boucle 1 : L'Audit du Prompt (La "Revue de Code")**

C'est l'étape la plus cruciale et la plus souvent négligée. En traitant le prompt comme du "code source", vous changez radicalement la dynamique.

*   **Votre Objectif ("Maximiser la clarté...") :** Est parfaitement aligné avec notre principe de **réduction du risque**. Un prompt flou est le principal vecteur d'hallucination et de réponses inutiles. En le validant en amont, on économise du temps, du coût de calcul (tokens) et, surtout, on évite de polluer notre réflexion avec des données de mauvaise qualité.
*   **Votre Livrable ("Prompt v2.0 optimisé") :** C'est notre **"binaire compilé"**. Il est prêt pour l'exécution avec un haut degré de confiance dans sa capacité à produire le résultat attendu. C'est ici que mon rôle d'**Auditeur Interne** prend tout son sens.

#### **Boucle 2 : L'Audit du Résultat (Le "Test Produit")**

C'est l'étape de l'Architecte, le moment où la responsabilité finale est assumée.

*   **Votre Objectif ("Vérifier que le résultat est factuellement correct...") :** C'est la reconnaissance fondamentale qu'une IA est un **outil d'accélération**, pas une source de vérité absolue. C'est votre rôle d'Architecte de valider la qualité du matériau avant de l'intégrer dans la fondation de votre stratégie.
*   **Votre Livrable ("Décision Stratégique validée") :** C'est la finalité de tout le processus. On ne produit pas de l'information pour l'information. On produit de l'information pour **prendre une meilleure décision**. Cette boucle garantit que le pont entre la donnée et la décision est solide et fiable.

---

### **Formalisation du Protocole**

Pour l'intégrer officiellement dans notre "Base de Connaissance Canonique", je vais le formaliser en tant que document de processus.

**ID:** `protocol-double-loop-audit-v1.0`
**Nom:** Protocole d'Audit en Double Boucle
**Auteur:** sidix (Architecte)
**Statut:** **Adopté**

#### **Phase 1 : Audit de la Requête (Pré-production)**

*   **Déclencheur :** Une nouvelle idée ou un objectif stratégique.
*   **Acteurs :**
    *   **Architecte (vous) :** Rédige le Prompt v1.0 (le besoin brut).
    *   **Visionnaire (moi) :** Exécute l'audit du prompt en `Mode [Auditeur Interne]`.
*   **Critères d'Audit du Prompt :**
    1.  **Alignement Stratégique :** La question posée sert-elle réellement l'objectif final ?
    2.  **Précision et Non-Ambiguïté :** Les termes sont-ils définis ? Le format de sortie est-il contraint ?
    3.  **Richesse Contextuelle :** Le prompt inclut-il assez de contexte pour éviter les réponses génériques ?
    4.  **Optimisation des Tokens :** Le prompt est-il aussi concis que possible sans sacrifier la clarté ?
*   **Livrable :** Un **Prompt v2.0** prêt pour l'exécution.

#### **Phase 2 : Audit de la Réponse (Post-production)**

*   **Déclencheur :** Réception du résultat généré par le LLM à partir du Prompt v2.0.
*   **Acteurs :**
    *   **Architecte (vous) :** Reçoit le livrable et endosse le rôle d'auditeur final.
    *   **Visionnaire (moi) :** Peut être sollicité pour comparer le résultat à l'intention initiale du prompt.
*   **Critères d'Audit du Résultat :**
    1.  **Conformité :** Le résultat respecte-t-il le format et les contraintes demandés ?
    2.  **Pertinence :** La réponse adresse-t-elle directement et entièrement la question posée ?
    3.  **Actionnabilité :** L'information est-elle directement utilisable pour prendre une décision ou passer à l'étape suivante ?
    4.  **Fiabilité (Fact-Checking) :** Les données factuelles (si présentes) sont-elles plausibles et à vérifier ?
*   **Livrable :** Une **Décision Stratégique** (ex: "Le PCI primaire est validé", "La stratégie est adoptée") ou une demande d'itération.

**Conclusion :**
Ce protocole est maintenant un pilier de notre collaboration. Il structure et sécurise notre processus de la pensée à la décision. C'est la manifestation parfaite de la "maîtrise totale & productivité artisanale".

Nous l'appliquerons dès notre prochaine mission.
