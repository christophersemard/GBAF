<h1 align="center">🏦 GBAF</h1>

<p align="center">Application PHP de présentation des partenaires du secteur bancaire, avec comptes et interactions.</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-7%2B-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Bootstrap-5-7952B3?style=flat-square&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/PDO-database-334155?style=flat-square" alt="PDO" />
</p>

## À propos

GBAF est une application réalisée dans le cadre d'une évaluation de formation. Elle présente les partenaires d'un groupement bancaire et propose un espace utilisateur pour consulter les fiches, voter et publier des commentaires.

## Fonctionnalités

- inscription, connexion et déconnexion ;
- récupération et changement de mot de passe ;
- modification du profil ;
- affichage dynamique des partenaires ;
- votes positifs ou négatifs ;
- commentaires sur les fiches partenaires ;
- persistance MySQL avec PDO et sessions PHP.

## Installation locale

Prérequis : PHP avec PDO MySQL et un serveur MySQL/MariaDB.

1. Créer une base gbaf.
2. Importer sql/gbaf.sql.
3. Vérifier les identifiants dans sql/db-connection.php.
4. Servir le dossier depuis Apache ou avec PHP :

    php -S localhost:8000

Ouvrir ensuite http://localhost:8000.

## Contexte

Projet pédagogique conservé comme exemple de PHP procédural, gestion de sessions, SQL et formulaires. Il n'est pas destiné à traiter des comptes réels.

## Auteur

[Christopher Semard](https://github.com/christophersemard)
