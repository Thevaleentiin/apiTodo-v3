## Install projet
# 1- composer install
# 2- php bin/console doctrine:database:create
# 3- php bin/console make:migration
# 4- php bin/console doctrine:make:migration
# 5- Si impossible de lancer le serveur avec php bin/console s:r
    composer req api
    composer require symfony/orm-pack
    composer require --dev symfony/maker-bundle
    composer req server --dev
# 6- Se rendre sur l'adresse localhost/api