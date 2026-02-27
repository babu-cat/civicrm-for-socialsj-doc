# Permisos

## Rols

Rol **tècnic infància** El tècnic infància, en canvi, només està capacitat per operar amb aquells contactes estrictament lligats amb els programes d'infància de l'entitat:

## Permisos Drupal

|                                          |     usuari anonim       |
|:---------------------------------------- |:-----------------------:|
| CiviCRM: Afegeix contactes               |            No           |
| CiviCRM: Visualitza tots els contactes   |            No           |
| CiviCRM: Edita tots els contactes        |            No           |
| CiviCRM: Elimina contactes               |            No           |
| CiviCRM: Accés als contactes eliminats   |            No           |
| CiviCRM: Importa contactes               |            No           |  
| CiviCRM: Edita grups                     |            No           |  
| CiviCRM: Administrar el CiviCRM          |            No           |  
| CiviCRM: Accés als arxius pujats         |            Si           |
| CiviCRM: Fitxes de perfil i formularis   |            No           |
| CiviCRM: Fitxes de perfil                |            No           |  
| CiviCRM: Crea un perfil                  |            Si           |
| CiviCRM: Edita un perfil                 |            Si           |
| CiviCRM: Visualitza un perfil            |            Si           |
| CiviCRM: Accedeix a totes les dades personalitzades|  No           |  
| CiviCRM: Visualitza totes les activitats |           Si            |  
| CiviCRM: Elimina activitats              |            Si           |  
| CiviCRM: Accés al CiviCRM                |            Si           |
| CiviCRM: Accés al tauler del contacte    |            Si           |
| CiviCRM: Traduir el CiviCRM              |            No           |  
| CiviCRM: Administra grups reservats      |            No           |  
| CiviCRM: Administra Etiquetes            |            No           |  
| CiviCRM: Administra Etiquetes Reservades |            No           |
| CiviCRM: Administra normes de deduïts    |            No           |
| CiviCRM: Fusiona contactes duplicats     |            No           |  
| CiviCRM: Veure sortida de depuració      |            No           |
| CiviCRM: Visualitza totes les notes      |            No           |
| CiviCRM: Accedeix a l'API d'AJAX         |            No           |
| CiviCRM: Accedeix als camps de referència del contacte|    No      |
| CiviCRM: Crea un lot manual              |            No           |
| CiviCRM: Edita lots de manuals propis    |            No           |
| CiviCRM: Edita tots els lots de manuals  |            No           |
| CiviCRM: Visualitza lots de manuals propis    |       No           |
| CiviCRM: Visualitza tots els lots de manuals  |       No           |
| CiviCRM: Esborra lots de manuals propis    |          No           |
| CiviCRM: Esborra tots els lots de manuals  |          No           |
| CiviCRM: Exporta lots de manuals propis    |          No           |
| CiviCRM: Exporta tots els lots de manuals  |          No           |
| CiviEvent: Accedeix al CiviEvent           |          Si           |
| CiviEvent: Edita participants de l'esdeveniment |      No           |  
| CiviEvent: Edita tots els esdeveniments    |            No           |  
| CiviEvent: Registrar-se per esdeveniments  |            Si           |  
| CiviEvent: Veure informació dels esdeveniments  |       Si           |  
| CiviEvent: Veure participants de l'esdeveniment |       Si           |  
| CiviEvent: Esborra al CiviEvent            |            No           |
| CiviContribute: Accedi al CiviContribute   |            No           |
| CiviContribute: Edita contribucions        |            No           |
| CiviContribute: Fer contribucions online   |            No           |
| CiviContribute: Esborra al CiviContribute  |            No           |
| CiviMail: Accedeix  al CiviMail            |            No           |
| CiviMail: Accedeix a les pàgines de subscripció/anul·lació de CiviMail|         Si         |
| CiviMail: Esborra al CiviMail              |            No           |
| CiviMail: Veure contignut públic al CiviMail|          No           |      
| CiviReport: Accedieix al CiviReport         |            Si           |   
| CiviReport: Accedieix al Report Criteria    |            Si           |   
| CiviReport: Administra informes reservats  |            No           |
| CiviReport: Administra informes            |            No           |


## Permisos CiviCRM

| Rol            |     Descripció permís              | Operació      | Tipus de dades                               | Objecte                     |
|:---------------|:---------------------------------- |:------------- |:-------------------------------------------- |:--------------------------- |
|Tècnic Infància | Edita contactes infància           | Edita         | Un grup de contactes                         | Contactes infància                 |
|Tècnic Infància | Edita contactes tècnics infància   | Edita         | Un grup de contactes                         | Contactes treballadors actius      |
|Tècnic Infància | Edita contactes tècnics infància   | Edita         | Un grup de contactes                         | Contactes treballadors històric    |
|Tècnic Infància | Edita documentació                 | Edita         | Un conjunt de camps de dades personalitzades       | Documentació   |
|Tècnic Infància | Edita perfil demogràfic usuari/a   | Edita         | Un conjunt de camps de dades personalitzades       | Perfil demogràfic usuari/a   |
|Tècnic Infància | Edita genograma                    | Edita         | Un conjunt de camps de dades personalitzades       | Genograma  |
|Tècnic Infància | Edita genograma adult - infància   | Edita         | Un conjunt de camps de dades personalitzades       | Genograma adult - infància  |
|Tècnic Infància | Edita NESE                         | Edita         | Un conjunt de camps de dades personalitzades       |  Necessitats Específiques de Suport Educatiu Especials |
|Tècnic Infància | Edita salut i alimentació          | Edita         | Un conjunt de camps de dades personalitzades       | Salut i alimentació  |
|Tècnic Infància | Edita autoritzacions               | Edita         | Un conjunt de camps de dades personalitzades       | Autoritzacions registrades |
|Tècnic Infància | Edita perfil adult                 | Edita         | Un conjunt de camps de dades personalitzades       | Perfil adult |
|Tècnic Infància | Edita perfil lingüístic            | Edita         | Un conjunt de camps de dades personalitzades       | Perfil lingüístic|
|Tècnic Infància | Edita perfil acadèmic i professional | Edita         | Un conjunt de camps de dades personalitzades       | Perfil acadèmic i professional|
|Tècnic Infància | Edita perfil migratori             | Edita         | Un conjunt de camps de dades personalitzades       | Perfil migratori|
|Tècnic Infància | Edita perfil professional          | Edita         | Un conjunt de camps de dades personalitzades       | Perfil professional|
|Tècnic Infància | Edita perfil unitat familiar i de convivència             | Edita         | Un conjunt de camps de dades personalitzades | Perfil unitat familiar i de convivència|
|Tècnic Infància | Edita perfil centre educatiu       | Edita         | Un conjunt de camps de dades personalitzades | Perfil centre educatiu|
|Tècnic Infància | Edita documentació registrada – infant / jove | Edita         | Un conjunt de camps de dades personalitzades | Documentació registrada – infant / jove|
|Tècnic Infància | Edita documentació registrada – UFC | Edita         | Un conjunt de camps de dades personalitzades | Documentació registrada – UFC|
|Tècnic Infància | Edita resultats acadèmics registrats | Edita         | Un conjunt de camps de dades personalitzades | Resultats acadèmics registrats|
|Tècnic Infància | Edita situació menjador escolar registrada | Edita         | Un conjunt de camps de dades personalitzades | Situació menjador escolar registrada|
|Tècnic Infància | Edita situació laboral registrada  | Edita         | Un conjunt de camps de dades personalitzades | Situació laboral registrada|
|Tècnic Infància | Edita ingressos registrats         | Edita         | Un conjunt de camps de dades personalitzades | Ingressos registrats|
|Tècnic Infància | Edita despeses registrades         | Edita         | Un conjunt de camps de dades personalitzades | Despeses registrades|
|Tècnic Infància | Edita seguiment psicoterapèutic    | Edita         | Un conjunt de camps de dades personalitzades | Seguiment psicoterapèutic|
|Tècnic Infància | Edita bé CPI                      | Edita         | Un conjunt de camps de dades personalitzades | Bé CPI|
|Tècnic Infància | Edita adreça antiga                | Edita         | Un conjunt de camps de dades personalitzades | Adreça antiga|
|Tècnic Infància | Edita derivació                    | Edita         | Un conjunt de camps de dades personalitzades | Derivació|
|Tècnic Infància | Edita migració                     | Edita         | Un conjunt de camps de dades personalitzades | Migració|
|Tècnic Infància | Edita beca CPI                     | Edita         | Un conjunt de camps de dades personalitzades | Beca CPI|
|Tècnic Infància | Edita tutoria                      | Edita         | Un conjunt de camps de dades personalitzades | Tutoria|
|Tècnic Infància | Edita estudis infantil, primària i secundària      | Edita         | Un conjunt de camps de dades personalitzades | Estudis infantil|
|Tècnic Infància | Edita estudis primària             | Edita         | Un conjunt de camps de dades personalitzades | Estudis primària|
|Tècnic Infància | Edita estudis secundària           | Edita         | Un conjunt de camps de dades personalitzades | Estudis secundària|
|Tècnic Infància | Edita estudis UEC                  | Edita         | Un conjunt de camps de dades personalitzades | Estudis UEC|
|Tècnic Infància | Edita lloc de treball              | Edita         | Un conjunt de camps de dades personalitzades | Lloc de treball|
|Tècnic Infància | Edita dades estudiant en pràctiques| Edita         | Un conjunt de camps de dades personalitzades | Dades estudiant en pràctiques|
|Tècnic Infància | Edita atenció professional         | Edita         | Un conjunt de camps de dades personalitzades | Atenció professional|
|Tècnic Infància | Edita atenció docent               | Edita         | Un conjunt de camps de dades personalitzades | Atenció docent|
|Tècnic Infància | Edita seguiment infant / jove      | Edita         | Un conjunt de camps de dades personalitzades | Seguiment infant / jove|
|Tècnic Infància | Edita seguiment voluntaris         | Edita         | Un conjunt de camps de dades personalitzades | Seguiment voluntaris|
|Tècnic Infància | Edita derivació acollida           | Edita         | Un conjunt de camps de dades personalitzades| Derivació acollida|
|Tècnic Infància | Gestiona perfil nou professional   | All         | Un perfil| Nou professional|
|Tècnic Infància | Gestiona perfil nou docent         | All         | Un perfil| Nou docent|
|Tècnic Infància | Edita documentació organitzacions  | Edita       | Un conjunt de camps de dades personalitzades| Documentació organitzacions|
|Tècnic Infància | Edita autoritzacions i acords      | Edita       | Un conjunt de camps de dades personalitzades| Autoritzacions i acords|
|Tècnic Infància | Edita protecció de dades           | Edita       | Un conjunt de camps de dades personalitzades| Protecció de dades|
|Tècnic Infància | Edita vinculació a programes o departaments de l'entitat | Edita       | Un conjunt de camps de dades personalitzades | Vinculació a programes o departaments de l'entitat
