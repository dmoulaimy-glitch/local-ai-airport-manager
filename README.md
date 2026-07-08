# ✈️ Airport Report Automation - Application de Gestion des Rapports Techniques

Une application locale sécurisée (Local-First) conçue spécialement pour la modernisation de la gestion, de l'extraction et du suivi des rapports techniques au sein de l'**Aéroport Hassan Ier de Laâyoune**.

---

## 🛠️ Stack Technique & Détails d'Implémentation

Pour garantir la souveraineté numérique et la sécurité des données de l'infrastructure aéroportuaire, l'application repose entièrement sur des technologies locales et open-source :

* **Interface Utilisateur (IHM) :** **Streamlit** (Python), offrant une interface web moderne, réactive et fluide pour les agents techniques.
* **Base de Données :** **SQLite**, une base relationnelle légère, locale et embarquée, assurant un stockage sécurisé sans dépendance cloud.
* **Traitement de l'Intelligence Artificielle :** **Ollama (Modèle LLM Mistral)**, déployé localement pour l'extraction intelligente des données des rapports PDF sans qu'aucune donnée ne quitte le réseau de l'aéroport.
* **Sécurité & Authentification :** Algorithmes de hachage cryptographique pour la protection des mots de passe et gestion des accès basés sur les rôles (**RBAC**).

---

## ✨ Caractéristiques Majeures & Optimisation du Temps

L'application transforme la gestion opérationnelle du Service Technique grâce à des fonctionnalités clés :

1. **Gain de Temps Majeur (Automatisation) :** L'IA extrait instantanément les informations critiques des fichiers PDF complexes (pannes, heures de shift, composants). Plus besoin de saisie manuelle fastidieuse.
2. **Contrôle d'Accès Strict (RBAC) :** Un cloisonnement des privilèges garantit que les **Ingénieurs** soumettent les rapports techniques et partagent des notes de shift publiques, tandis que le **Chef de Service** valide ou renvoie les dossiers.
3. **Fluidification des Missions :** Grâce à un tableau de bord dynamique, le suivi du statut des workflows (En attente, Approuvé, Renvoyé) est instantané, éliminant les pertes de documents traditionnels.
4. **Souveraineté des Données :** Fonctionnement 100% hors-ligne (Offline), protégeant l'historique des pannes et des interventions des réseaux extérieurs.

---

## 🚀 Guide d'Installation et d'Utilisation

Suivez ces étapes simples pour installer et lancer l'application sur n'importe quel ordinateur du service technique :

### 1. Prérequis
* **Python 3.10 ou supérieur** installé sur la machine.
* **Ollama** installé localement (avec le modèle Mistral téléchargé via la commande `ollama run mistral`).

### 2. Installation
Ouvrez votre terminal (ou invite de commande) et suivez les instructions suivantes :

```bash
# Clonez le dépôt ou téléchargez les fichiers du projet
git clone [https://github.com/VOTRE_NOM_UTILISATEUR/REPO_NAME.git](https://github.com/VOTRE_NOM_UTILISATEUR/REPO_NAME.git)
cd REPO_NAME

# Installez les dépendances Python requises
pip install -r requirements.txt
