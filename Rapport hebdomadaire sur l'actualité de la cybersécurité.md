## Rapport hebdomadaire sur l'actualité de la cybersécurité

Ce tutoriel vous guide dans la création d'un agent automatisé qui :

S'exécute chaque lundi à 9h GMT
Scrape les actualités cybersécurité de sources multiples
Analyse et sélectionne les 10 articles les plus pertinents avec l'IA
Envoie un rapport détaillé par email

# Prérequis
- Compte Pipedream
- Compte Gmail (pour l'envoi d'emails)
- Compte OpenAI (pour l'analyse IA)

# Architecture de l'Agent
Timer (Lundi 9h GMT) → Scraping → Analyse IA → Email Gmail

# Prompt 

Chaque lundi à 9h GMT, effectuer les actions suivantes :
Consulter les actualités de cybersécurité publiées au cours de la semaine précédente sur les sites suivants :
Krebs on Security
The Hacker News
Bleeping Computer
et dautre site qui offre ce meme service.
Sélectionner les 10 actualités les plus pertinentes parmi celles publiées, et pour chacune, fournir les éléments suivants :
- Titre de l’article
- Résumé bref et clair de l’information
- Identifiants CVE associés (s’il y en a)
- Score CVSS (s’il est disponible)
- Entreprise(s) ou produit(s) concerné(s)
- Envoyer l’analyse complète par email en utilisant Gmail

# Approuvé le résumé du plan

Pipedream vous présentera un résumé détaillé de votre plan. Vous pourrez l’approuver ou le rééditer. Ensuite, il se chargera de créer votre workflow et vous proposera d’effectuer un test pour chaque étape.

# Agent déployé

Enfin, cliquez sur le bouton Déployer pour déployer votre agent afin qu’il puisse exécuter automatiquement les tâches prévues.
