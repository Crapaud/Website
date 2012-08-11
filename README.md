Website
Website's main structure built on top of Symfony

This repository is public and its main purpose is the Cornichon website. If you think it will useful for you, feel free to use it.

Cornichon Bundles Required:
* https://github.com/Cornichon/ForumBundle
* https://github.com/Cornichon/UserBundle

Make sure your environment fits Symfony's requirements.

[1] Add parameters_local.yml in app/config and set parameters to your local MySQL DB
[2] php app/console doctrine:database:create
[3] php app/console doctrine:schema:create