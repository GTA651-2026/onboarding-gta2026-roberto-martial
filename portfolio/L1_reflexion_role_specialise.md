# L1 — Fiche d'opportunite agentique

> Choisissez UN des trois cas (Klarna, GitHub Copilot Enterprise, Morgan Stanley).
> Remplissez les 6 champs ci-dessous en langage executif (pas technique).
> Exportez en PDF et deposez `L1_reflexion_role_specialise.pdf` dans ce dossier.

---

## Cas choisi

_GitHub Copilot Enterprise

## 1. Probleme d'affaires resolu
La croissance du portefeuille applicatif dans les organisations technologiques engendre un écart croissant entre la capacite des equipes techniques et le volume de travail attendu. Les ingenieurs consacrent une portion significative de leur journée a des activités a faible valeur ajoutée 
— recherche de documentation, ecriture de tests unitaires, reformulation de code existant au detriment de la conception et de l'innovation. GitHub a deploye Copilot Enterprise pour combler cet ecart sans recourir a une augmentation des effectifs.

## 2. Fonction d'affaires ciblee

Ingenierie logicielle — specifiquement les activités de conception, d'écriture et de validation du code source au sein des équipes de developpement produit et de maintenance des systemes éxistants

## 3. Role specialise que l'agent orchestre

Agent programmeur assiste : un systeme d'IA conversationnelle et prédictive intégré directement dans l'environnement de developpement (IDE), qui anticipe les intentions du developpeur, génere des blocs de code contextuellement pertinents, redige la documentation associee et repond aux questions techniques en langage naturel. Il joue le role d'un collaborateur technique senior disponible en permanence, sans remplacer le jugement humain.


## 4. Valeur creee — quantifiee avec donnees publiques

Les mesures publiées par GitHub et Microsoft sur les deployements enterprise indiquent : une acceleration de 55 % de la vitesse d'execution des taches de codage ; un taux de satisfaction de 88 % parmi les developpeurs utilisateurs, qui se déclarent nettement plus efficaces. En moyenne, 30 % du code valide en production est directement issu de suggestions acceptées par l'agent. Le groupe Accenture, qui a déployé l'outil aupres de 50 000 collaborateurs techniques, rapporte une reduction tangible du temps de cycle de developpement, avec un impact direct sur la capacite de livraison trimestrielle.

## 5. Risque principal et mitigation concrete

Risque principal : adoption passive du code suggéré sans validation critique, conduisant a l'introduction de failles de sécurite ou de logique defectueuse en production, et potentiel de divulgation involontaire de code propriétaire vers des infrastructures externes.
Mitigation concréte : mettre en oeuvre la politique d'isolation du code source (code exclusion settings) pour empecher toute transmission hors du perimetre sécurise ; formaliser une charte de revue IA obligatoire avant toute fusion de code assiste ; instrumenter le pipeline de livraison avec des controles de securite automatises (analyses SAST/DAST) afin de detecter les vulnerabilites en amont de la mise en production.

## 6. Condition de succes pour votre organisation
Le succés du déploiement repose sur trois piliers fondamentaux : (1) une cartographie prealable des donnees sensibles — identifier quels referentiels et bases de code peuvent interagir avec le modele et etablir des perimetres d'accés clairs avant tout lancement ; (2) un programme d'habilitation des equipes — former les developpeurs a évaluer critiquement les propositions de l'agent plutot qu'a les accepter systematiquement, en instaurant un reflexe de validation active ; (3) une compatibilité technique verifiée — s'assurer que Copilot Enterprise s'integre sans friction dans la chaine d'outils en place (environnements de developpement, gestionnaires de versions, plateformes de deploiement continu) pour garantir l'adoption et eviter les resistances operationnelles.

---

> **Rappel :** mettez a jour `ai-usage.md` a la racine du depot, meme si vous n'avez utilise aucun outil IA.
