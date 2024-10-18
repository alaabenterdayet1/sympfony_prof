# Mon Projet

Ce dépôt contient le code source de mon projet Symfony.

## Backend Symfony

### Installation

1. Accédez au répertoire backend :
    ```bash
    cd SYMPONY
    ```
2. Installez les dépendances :
    ```bash
    composer install
    ```

### Démarrage du serveur

Le serveur Symfony sera démarré à l'adresse [http://localhost:8000](http://localhost:8000).

```bashµ
symfony serve
  ```
3.CONFIGRATION BASE DONNEE 
```bash

php bin/console doctrine:database:create

```
```bash

php bin/console doctrine:schema:update --force



