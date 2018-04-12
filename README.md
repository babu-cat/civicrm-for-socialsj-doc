# CiviCRM per a entitats del sector social dels Jesuïtes de Catalunya - Documentació

Aquest repositori conté la documentació dels diferents CRMs de les entitats del sector social dels Jesuïtes i que és accessible a través de l'adreça http://docs.crm.socialsj.cat.

La documentació està construïda mitjançant [MkDocs](http://www.mkdocs.org/), un generador de llocs web especialment dirigit a l'elaboració de documentació i el codi font de la qual està escrit amb [Markdown](http://daringfireball.net/projects/markdown/) i configurat amb un únic fitxer de configuració YAML. S'utilitza [Mkdocs Material](https://github.com/squidfunk/mkdocs-material) com a tema visual de la documentació.

## Requirements

Instal·lar MkDocs i Mkdocs Material per poder compilar el projecte.

## Build

Per tal de generar la documentació en HTML tan sols cal llançar la següent ordre:

    mkdocs build --clean

## Deploy

Per tal de desplegar la documentació a GitHub Pages tan sols cal llançar la següent ordre:

    mkdocs gh-deploy
