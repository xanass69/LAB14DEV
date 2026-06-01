# LAB14DEV

Lab 14 : Persistance Locale Sécurisée sous Android (Java)
Ce projet implémente une solution complète de stockage local pour Android, couvrant différents types de persistance tout en respectant les meilleures pratiques de sécurité.

Objectifs d'apprentissage
Utilisation des SharedPreferences pour les paramètres non sensibles

Mise en œuvre de EncryptedSharedPreferences pour sécuriser les secrets (tokens)

Gestion du stockage interne (fichiers texte UTF-8 et JSON via org.json)

Gestion du cache temporaire et purge manuelle

Exportation de fichiers vers le stockage externe spécifique à l'application

Application d'une checklist sécurité (évitement des logs sensibles, MODE_PRIVATE)

Fonctionnalités
Préférences Standards : Enregistre le nom, la langue et le thème

Stockage Chiffré : Utilise androidx.security:security-crypto pour chiffrer l'API Token sur le disque

Fichiers Internes :

students.json : Liste d'objets Student sérialisée

note.txt : Journal d'opérations en UTF-8

Gestion du Cache : Stockage de l'état de l'interface dans le répertoire cache

Nettoyage Complet : Bouton permettant de supprimer toutes les données locales (fichiers, cache et préférences)
