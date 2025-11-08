# Echo - Que leur voix résonne

## Présentation

**Echo** est né d’un constat simple mais alarmant : les adolescents, de plus en plus exposés au harcèlement — qu’il soit scolaire, social ou numérique —, ne disposent aujourd’hui d’aucun outil réellement sûr, neutre et autonome pour documenter les faits et préserver leurs droits. Les solutions existantes sont très souvent proposées in-app, ou complexes à accéder. On pense notamment aux outils tels que les surveillances Instagram, Snapchat, ou encore des instances officielles (Pharos). 

> ### Important
> Afin de lutter contre le harcèlement en milieu scolaire et le cyberharcèlement, le ministère de l'Éducation nationale a lancé le **3018**. Ce numéro gratuit, anonyme et confidentiel est disponible 7j/7 de 9h à 23h. Il s'adresse aux enfants, aux parents et aux professionnels pour tout renseignement ou signalement.


Les solutions de collecte sont souvent trop techniques, centralisées ou inadaptées à leur âge, sans garantie de confidentialité ni de recevabilité juridique.

Echo propose une alternative : un **écosystème open source, souverain et éthique**, qui respecte l’autonomie des jeunes tout en leur permettant de rassembler des éléments de preuve solides, à valeur probante, sans compromettre leur intimité.


## Le constat

Aujourd’hui :

* Les victimes mineures de harcèlement n’ont **aucun contrôle** sur les plateformes où les preuves se trouvent (réseaux sociaux, messageries, etc.).
* Les parents, les établissements et les institutions manquent **d’outils fiables** pour recueillir et conserver les preuves de manière sûre et encadrée.
* Les démarches judiciaires se heurtent à l’absence de preuves recevables ou à la perte de données.
* Les adolescents, par peur ou méfiance, hésitent à **partager leurs données sensibles** avec les adultes, craignant un usage détourné ou une exposition publique.

Echo répond à ces limites en offrant un cadre **technologique, éducatif et juridique cohérent**, fondé sur la confiance, la transparence et le respect de la vie privée.

---

## La problématique adressée

Comment permettre à un jeune de **documenter un harcèlement** sans qu’il se mette lui-même en danger, sans trahir sa confidentialité, et tout en rendant ses éléments exploitables s’il décide, un jour, de porter plainte ou d’en parler ?

Echo ne se limite pas à une simple application : c’est une **infrastructure de confiance** qui concilie trois besoins fondamentaux :

1. **Protection de la vie privée** : chiffrement local, absence de serveur central obligatoire, aucun tracking.
2. **Crédibilité juridique** : horodatage, empreinte cryptographique, traçabilité des métadonnées.
3. **Soutien éducatif** : accompagnement des jeunes, des enseignants, des parents et des associations pour comprendre les enjeux du signalement.

---

## Les niveaux d’adoption possibles

Echo est conçu pour être adaptable, selon le contexte :

1. **Usage individuel** : l’adolescent télécharge l’application et l’utilise de façon autonome, avec contrôle total sur ses données.
2. **Usage encadré** : l’application est déployée dans un **établissement scolaire, une collectivité ou une association**, avec un cadre éthique et des garants identifiés (référents harcèlement, médiateurs, etc.).
3. **Usage institutionnel** : intégration dans des politiques publiques locales ou nationales de prévention du harcèlement, en partenariat avec des acteurs juridiques, éducatifs et sociaux.

Chaque niveau d’adoption repose sur la **souveraineté de l’utilisateur** et le respect strict des principes de **non-ingérence et de consentement éclairé**.

---

## La question de l’accès parental

Une dimension essentielle du projet est la **conscience que les parents ne doivent pas avoir un accès illimité aux données** de leurs enfants. La confidentialité n’est pas une défiance, mais une **condition de confiance** : pour que les adolescents puissent parler, ils doivent se sentir protégés, entendus, non surveillés.

Echo met donc en œuvre une **gestion différenciée des accès** :

* L’enfant reste **maître de ses données** et choisit **quand et à qui** les partager.
* Les parents ou responsables légaux peuvent être **informés ou accompagnés** dans un cadre convenu (scolaire, psychologique, juridique) sans accès direct au contenu.
* Les structures éducatives ou associatives servent de **tiers de confiance**, garants du respect de cette confidentialité.

---

## Mon ambition technique

L’ambition technique de Echo est d’être une **référence en matière d’architecture souveraine, résiliente et auditable**. L’objectif est de prouver qu’il est possible de concilier **sécurité, simplicité et souveraineté** dans une application citoyenne et éthique.

Les grands axes techniques du projet sont :

### 1. Architecture modulaire et open source

* **Backend Spring Boot** : robuste, extensible, auditable et interopérable.
* **Frontend Angular / Android** : interface fluide et adaptée à la jeunesse, sans tracking ni dépendance propriétaire.
* **APIs standardisées** (REST + futur support GraphQL) pour l’intégration avec des tiers de confiance (associations, institutions, outils de signalement officiels).

### 2. Sécurité et intégrité

* **Chiffrement de bout en bout (AES-256)**, avec clés générées localement.
* **Horodatage et empreinte cryptographique** via hash SHA-256 + signature numérique.
* **Stockage local chiffré** avec possibilité de sauvegarde sur serveur souverain ou espace personnel chiffré.
* **Audit trail exportable** assurant la recevabilité juridique des éléments.

### 3. Souveraineté et résilience

* Aucun service tiers imposé (Google, Apple, AWS, etc.).
* Infrastructure compatible **auto-hébergement** et **fédérée** (instances communautaires ou institutionnelles).
* CI/CD avec pipelines open source, vérification de signatures, et publication transparente.

### 4. Portabilité et interopérabilité

* Formats ouverts (JSON, ZIP, PDF avec métadonnées intégrées).
* Mécanisme d’export « preuve » avec certificat d’intégrité et empreinte vérifiable.
* Connecteurs potentiels avec outils publics (signalement, justice, éducation nationale, etc.).

### 5. Accessibilité et pédagogie

* Interface adaptée à tous les âges (mode simplifié et mode expert).
* Guides intégrés, tutoriels vidéo et accompagnement contextualisé.
* Multilingue, offline-first, et optimisée pour terminaux modestes.

---

## Une vision collective et évolutive

Echo ne se veut pas seulement un outil, mais un **projet de société**. Il cherche à :

* Redonner du **pouvoir d’agir** aux jeunes.
* Offrir aux institutions un **cadre éthique d’action** contre le harcèlement.
* Encourager un **écosystème souverain** de solutions technologiques au service du bien commun.

C’est un projet ouvert, transparent et participatif : il évoluera avec la communauté, les chercheurs, les éducateurs, les juristes, et surtout, les jeunes eux-mêmes.

---

## Conclusion

Echo, c’est la volonté d’apporter une réponse concrète à un enjeu humain et sociétal : permettre aux victimes de harcèlement de reprendre le contrôle de leur histoire, de leurs preuves et de leur sécurité. Un pas vers une société numérique plus juste, où la technologie protège avant tout les plus vulnérables.

---

*Dernière mise à jour : 8 novembre 2025.*
