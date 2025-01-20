# FineTuning NLP pour algo de trading avec MT5
Suite à mon premier projet d'IA de trading algorithmique, j'ai décider de créer un nouveau projet plus complet/complexe. Le premier projet était assez brouillons, comme un gros paté, j'aimerai struturé quelque chose de plus simple et rapide a mettre en place.

## 🚀 Objectif :

Fine-tuner un modèle NLP (LLaMa 2) pour lui permettre de faire des prédictions en trading grâce aux informations économiques en direct. Ce modèle devra être connecté à MT5 (via un serveur local) et envoyer des prédictions de trade en fonction des nouvelles annonces économiques(API d'instituion financière/écoute active de réseau sociaux d'investisseur ou d'institution) et des données boursière entrainer(Historique de bougies chandelier). L'objectif et d'avoir un model léger permettant de se stabiliser sur des config plus ou moins faible, et de prendre des décision de trading en autonomie en respectant certaines contrainte technique et un "garde fou" accésible via Telegram et une API Rest(Flask).

Chaque jour vous partagerai l'avancé de ce projet en précisant les étapes de développement, les contrainte, et les découverte.
