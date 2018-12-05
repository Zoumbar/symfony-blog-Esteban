 Bonjour, voici mon projet symfony 

Faire cette liste de commande pour que ca marche



composer require server --dev
Php bin/console server:run

php bin/console doctrine:database:create
php bin/console doctrine:migration:migrate
php bin/console doctrine:fixtures:load


php bin/console make:migration

Normalement le blog devrait s'afficher correctement à l'adresse :
http://127.0.0.1:8000
