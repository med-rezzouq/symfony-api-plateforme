# symfony-api-plateforme

# configurations and yaml or xml files

metadata_backward_compatibility_layer: false (this when to show our endpoints details in the api interface documentation)

# The usual commands

symfony console doctrine:database:create (to create the database it will take the configuration from env as following for mysql)  
DATABASE_URL="mysql://root:@localhost:3306/symfonyapi"

symfony console doctrine:schema:create  
symfony new project-name (to create project)
symfony composer require api (to create the api platform)

composer self-update 1.8.0 (to update for a specific version)  
composer self-update --rollback (to cancel the latest composer update)

php bin/console cache:clear  
php bin/console d:s:u --force  
composer dump-autoload (this and the above when we remove manually any class or entity from project)

composer remove BundleName (to remove a bundle )

php bin/console debug:router (to show current routes)

composer require symfony/maker-bundle --dev --with-all-dependencies (install maker bundle)

php bin/console make:entity --api-resource (then follow instruction in terminal for entity name and fields and relation)  
php bin/console make:migration (it will create migration from entities)

php bin/console doctrine:migrations:migrate (it will execute queries inside the migration files)
