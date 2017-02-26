# Larave 5.4 Openshift
This repo contains larave 5.4 project to work on openshift. uses postgress database.

- has deployment action hooks to install composer dependencies and set up environment variables
- the gear must have the following cartridges
  - php7 (which installs nginx too)
  - postgress 9.2
- for now the APP_KEY is setup statical inside .openshift/action_hooks/deploy
  - to modify this add your key or modify the deploy actionhook to generate a new key each time it is deployed 
 
