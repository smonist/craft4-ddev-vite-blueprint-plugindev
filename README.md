# Craft CMS Dev Environment

Combine the power of Craft CMS and Vite.js with zero configuration setup and incredible fast paced development 😎
  

This repository is a fork of the original blueprint with added support for local plugin development. Adjust local plugin path to your needs in the following files:  
``.ddev/docker-compose.mounts.yaml``  
``composer.json - repositories section``  



## Quickstart

1.  ``make install``
2.  ``make dev``
3.  open https://craft4-ddev-vite-blueprint-plugindev.ddev.site

## XDebug & PHPStorm
https://ddev.readthedocs.io/en/stable/users/debugging-profiling/step-debugging/#phpstorm-debugging-setup  
TLDR: map project root to /var/www/html (do not map web directory)

## Requirements

-   Docker, https://www.docker.com
-   DDEV, https://ddev.com


## Credits
The team behind the magic ✨ 🪄 🦄

-  https://github.com/thomasbendl
-  https://github.com/smonist