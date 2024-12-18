# back-Systeme-de-Suivi-de-Commandes
### README pour le Projet Backend (Java Spring Boot)

# Système de Suivi de Commandes - Backend

## Description
Ce projet backend est une API REST développée avec Spring Boot qui permet de gérer le suivi des commandes. Il offre des fonctionnalités pour créer, lire, mettre à jour et supprimer des commandes, tout en intégrant des notifications en temps réel via Kafka.

## Fonctionnalités
- **Gestion des Commandes** : CRUD complet pour les commandes.
- **Affichage des Détails** : Visualisez l'historique et les informations sur les commandes.
- **Modification de Statut** : Changez le statut des commandes (En attente, Expédiée, Livrée, Annulée).
- **Notifications** : Envoi de notifications aux utilisateurs lors des changements de statut (fonctionnalité optionnelle utilisant Kafka).
- **Gestion des Utilisateurs** : Authentification et autorisation (facultatif).

## Technologies Utilisées
- Java
- Spring Boot
- Spring Data JPA
- Kafka (optionnel)
- H2/MySQL (base de données)

## Installation
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/suivi-commandes-backend.git
   cd suivi-commandes-backend
2. Ouvrez le projet dans votre IDE (comme IntelliJ IDEA ou Eclipse).
3. Compilez et exécutez l'application :
   ```bash
    ./mvnw spring-boot:run

L'API sera disponible à http://localhost:8080/api/orders.
Configuration de Kafka (facultatif)
Assurez-vous que Kafka est installé et en cours d'exécution.
Configurez les propriétés de Kafka dans application.properties.
