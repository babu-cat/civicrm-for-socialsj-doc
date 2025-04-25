# Permisos

El CiviCRM permet definir diferents nivells d'accés a les dades pels diferents tipus d'usuaris que l'han d'utilitzar. Aquests diferents nivells d'accés es corresponen a diferents rols que s'assignen a uns grups d'usuaris.

En aquesta pàgina definim els permisos globals tant a nivell de Drupal com de CiviCRM
i la resta de permisos queden definits en els respectius mòduls.

## Rols

Rol **tècnic administrador** El tècnic administrador té la capacitat de fer qualsevol acció i visualitzar totes les dades de la plataforma exceptuant aquelles estrictament relacionades amb la configuració i administració del CiviCRM.

## Permisos Drupal

|                                          |     usuari anònim       | usuari autenticat  | tècnic administrador |
|:---------------------------------------- |:-----------------------:|:------------------:|:--------------------:|
| CiviCRM: Afegeix contactes               |            No           |         No         |           Si         |
| CiviCRM: Visualitza tots els contactes   |            No           |         No         |           Si         |
| CiviCRM: Edita tots els contactes        |            No           |         No         |           Si         |
| CiviCRM: Elimina contactes               |            No           |         No         |           Si         |
| CiviCRM: Accés als contactes eliminats   |            No           |         No         |           Si         |
| CiviCRM: Importa contactes               |            No           |         No         |           Si         |
| CiviCRM: Edita grups                     |            No           |         No         |           Si         |
| CiviCRM: Administrar el CiviCRM          |            No           |         No         |           No         |
| CiviCRM: Accés als arxius pujats         |            Si           |         Si         |           Si         |
| CiviCRM: Fitxes de perfil i formularis   |            No           |         No         |           No         |
| CiviCRM: Fitxes de perfil                |            No           |         No         |           No         |
| CiviCRM: Crea un perfil                  |            ?            |         Si         |           Si         |
| CiviCRM: Edita un perfil                 |            ?            |         Si         |           Si         |
| CiviCRM: Visualitza un perfil            |            ?            |         Si         |           Si         |
| CiviCRM: Accedeix a totes les dades personalitzades|  No           |         No         |           Si         |
| CiviCRM: Visualitza totes les activitats |           No            |         No         |           Si         |
| CiviCRM: Elimina activitats              |            No           |         No         |           Si         |
| CiviCRM: Ometre verificació IDS          |            No           |         No         |           Si         |
| CiviCRM: Accés al CiviCRM                |            No           |         No         |           Si         |
| CiviCRM: Accés al tauler del contacte    |            No           |         No         |           Si         |
| CiviCRM: Traduir el CiviCRM              |            No           |         No         |           No         |
| CiviCRM: Administra grups reservats      |            No           |         No         |           Si         |
| CiviCRM: Administra Etiquetes            |            No           |         No         |           Si         |
| CiviCRM: Administra Etiquetes Reservades |            No           |         No         |           Si         |
| CiviCRM: Administra normes de deduïts    |            No           |         No         |           Si         |
| CiviCRM: Fusiona contactes duplicats     |            No           |         No         |           Si         |
| CiviCRM: Veure sortida de depuració      |            No           |         No         |           No         |
| CiviCRM: Visualitza totes les notes      |            No           |         No         |           Si         |
| CiviCRM: Accedeix a l'API d'AJAX         |            No           |         No         |           No         |
| CiviCRM: Accedeix als camps de referència del contacte|    No      |         No         |           Si         |
| CiviCRM: Crea un lot manual              |            No           |         No         |           No         |
| CiviCRM: Edita lots de manuals propis    |            No           |         No         |           No         |
| CiviCRM: Edita tots els lots de manuals  |            No           |         No         |           No         |
| CiviCRM: Visualitza lots de manuals propis    |       No           |         No         |           No         |
| CiviCRM: Visualitza tots els lots de manuals  |       No           |         No         |           No         |
| CiviCRM: Esborra lots de manuals propis    |          No           |         No         |           No         |
| CiviCRM: Esborra tots els lots de manuals  |          No           |         No         |           No         |
| CiviCRM: Exporta lots de manuals propis    |          No           |         No         |           No         |
| CiviCRM: Exporta tots els lots de manuals  |          No           |         No         |           No         |
| CiviEvent: Accedeix al CiviEvent           |          No           |         No         |           Si         |
| CiviEvent: Edita participants de l'esdeveniment |      No           |         No         |           Si         |
| CiviEvent: Edita tots els esdeveniments    |            No           |         No         |           Si         |
| CiviEvent: Registrar-se per esdeveniments  |            Si           |         Si         |           Si         |
| CiviEvent: Veure informació dels esdeveniments  |       Si           |         Si         |           Si         |
| CiviEvent: Veure participants de l'esdeveniment |       Si           |         Si         |           Si         |
| CiviEvent: Esborra al CiviEvent            |            No           |         No         |           Si         |
| CiviContribute: Accedeix al CiviContribute |            No           |         No         |           Si         |
| CiviContribute: Edita contribucions        |            No           |         No         |           Si         |
| CiviContribute: Fer contribucions online   |            No           |         No         |           No         |
| CiviContribute: Esborra al CiviContribute  |            No           |         No         |           Si         |
| CiviMail: Accedeix  al CiviMail            |            No           |         No         |           No         |
| CiviMail: Accedeix a les pàgines de subscripció/anul·lació de CiviMail|         Si         |        Si        |       Si       |
| CiviMail: Esborra al CiviMail              |            No           |         No         |           No         |
| CiviMail: Veure contingut públic al CiviMail|          No           |         No         |           No         |
| CiviReport: Accedeix al CiviReport         |            No           |         No         |           Si         |
| CiviReport: Accedeix al Report Criteria    |            No           |         No         |           Si         |
| CiviReport: Administra informes reservats  |            No           |         No         |           Si         |
| CiviReport: Administra informes            |            No           |         No         |           Si         |

## Permisos CiviCRM

| Rol             | Descripció permís                  | Operació      | Tipus de dades                               | Objecte                     |
|:----------------|:---------------------------------- |:------------- |:-------------------------------------------- |:--------------------------- |
