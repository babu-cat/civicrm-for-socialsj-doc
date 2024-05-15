# Guia d'ús

## Gestió de socis i contribucions recurrents

!!! note "Nota"
    En un futur no gaire llunyà es té previst automatitzar alguns dels processos
    de gestió de socis i contribucions de tal manera que definint una pertinença
    de tipus soci amb un import periòdic associat es vagin generant periòdicament
    les seves respectives contribucions i inclús es puguin generar els fitxers de
    domiciliació per poder enviar al banc.

Quan no es disposa d'un sistema integrat de gestió de contribucions recurrents,
com per exemple les domiciliacions dels socis de l'entitat, i es desitja mantenir
dins del CRM el registre de contribucions, fer el manteniment manual d'aquest
registre de contribucions es pot convertir en una tasca tediosa.

Per això el CiviCRM ofereix algunes eines que ens poden ajudar a facilitar aquesta
gestió. A continuació descriurem alguns dels processos previstos per a la gestió
de socis i contribucions recurrents.

### Alta de socis nous

Els socis es defineixen al CiviCRM mitjançant les pertinences.

!!! info "Info"
    Quan avancem en l'automatització de les domiciliacions definirem amb més
    precisió les pertinences. Per ara només ens hem de preocupar de crear-les
    i cancel·lar-les quan s'escaigui per reflectir l'estat dels socis (actual i
    històric) de l'entitat.

L'alta de socis nous es pot produir per dues vies:

- **En línia** per la qual és el mateix soci que mitjançant el formulari de la web
es dona d'alta i es genera un registre al CRM amb la seva corresponent pertinença.

!!! attention "Atenció"
    Actualment quan un soci es dona d'alta a través de la web es crea un contacte
    al CRM amb les seves dades i una contribució amb estat pendent i tipus
    financer corresponent. Cal afegir manualment la pertinença com a soci
    de l'entitat.

- **Manual** per la qual es crea el contacte en el CRM directament i se li afegeix
la pertinença com a soci.

#### Revisió de contactes duplicats

Quan es produeix una alta de soci a través d'un formulari de la web el CRM sempre
genera un contacte nou amb l'ànim de no trepitjar mai cap dada existent al CRM
i delegant en una posterior revisió la verificació de les dades introduïdes i
la possible combinació de contactes duplicats quan es doni el cas.

### Baixa de socis

> PENDENT DE DOCUMENTAR

### Generació de contribucions anuals de socis

#### Manual

Si volem generar una contribució corresponent a la quota de soci d'un contacte
hem d'afegir una contribució amb **tipus financer** corresponent, definir
la **data de recepció** prevista, l'**import** de la contribució en qüestió i el
**mètode de pagament** corresponent a la vegada que definirem l'**estat
de la contribució** actual bé sigui 'Pendent' o bé 'Completat'.

#### En lots

Per tal d'agilitzar l'entrada de les contribucions recurrents vinculades als socis
ens podem valer de l'eina d'**Importació de contribucions** que ens proporciona
el CiviCRM.

D'aquesta manera podem introduir d'una tacada totes les contribucions previstes
per un any dels socis actuals (com a pendents) per posteriorment poder anar
actualitzant el seu estat com a completat a mesura que anem rebent els pagaments
corresponents.

Per importar les contribucions ens caldrà un fitxer CSV amb les següents columnes:

- **Identificador del contacte**
- **Import total**
- **Data de la contribució** - format ```dd-mm-YYYY``` o ```dd/mm/YYYY``` (en la importació posterior caldrà especificar el format escollit)
- **Estat de la contribució** - valors possibles: ```Completed``` i ```Pending```
- **Tipus financer** - valor per defecte: *El tipus financer corresponent tal com apareix al CRM*
- **Mètode de pagament** - valor per defecte: *El nom del mètode de pagament corresponent (normalment de tipus domiciliació) tal com apareix al CRM*
- **És un pagament diferit** - valor per defecte: ```1``` (sí)
- **Demana desgravar l'aportació a la declaració de la renda** - valors possibles ```1``` (sí) o ```0``` (no)

Un cop tinguem el fitxer CSV amb les contribucions a importar ja podrem procedir
amb la importació accedint-hi des del menú **Contribucions > Importació de contribucions**.

En el primer pas "Carrega les dades" haurem de:

1. Carregar el fitxer CSV com a **Fitxers de dades d'importació**
2. Marcar que **La primera fila conté les capçaleres de les columnes**
3. Marcar el **Tipus de contacte** com a ```Persona``` o ```Organització```, és indiferent quin seleccionem, podem importar de cop contribucions de persones i organitzacions
4. Seleccionar el **Mode d'importació** ```Afegir contribucions noves```
5. Indicar el **Separador dels camps d'importació** que utilitza el fitxer CSV, normalment si s'ha generat amb Microsoft Excel serà amb ```;``` i si s'ha fet amb LibreOffice serà amb ```,```
6. Seleccionar el **Format de data** utilitzat en el fitxer CSV

> Vegeu [CiviCRM - Guia de l'usuari > Fluxos de treball comuns > Importació de dades
en el CiviCRM - Importació de contribucions](https://docs.civicrm.org/user/ca/latest/common-workflows/importing-data-into-civicrm/#importacio-de-contribucions) per a més informació de com importar contribucions al CRM.

### Registre d'un pagament d'una contribució pendent

Per registrar un pagament d'una contribució pendent es pot fer

- o bé clicant a "més" en les opcions de la contribució

![Registre de pagament pendent més opcions de contribució](/captacio-de-fons/images/registre-pagament-mes.png)

- o bé desplegant la contribució i clicant a l'opció "Registra un pagament"

![Registre de pagament pendent contribució desplegada](/captacio-de-fons/images/registre-pagament.png)

No és aconsellable registrar el pagament editant la contribució i canviant l'estat a completada.

### Registre de pagaments de contribucions en bloc

Els pagaments de les contribucions de socis programades i registrades com a pendents
es poden anar actualitzant a mesura que es vagin rebent. Normalment farem
l'actualització un cop al mes quan el banc hagi domiciliat els imports del mes
actual. Per tal de no haver de fer aquesta acció manualment contacte a contacte i
contribució a contribució el CRM ofereix una eina per poder fer aquesta acció en
bloc.

Per fer-ho ens cal cercar les contribucions que volem actualitzar (per exemple les
contribucions de **tipus financer** corresponent amb **data de recepció** 'El mes actual' i amb **estat de la contribució** 'Pendent') i utilitzar
l'acció **Registra pagaments de contribucions**.

> Vegeu [CiviCRM - Guia de l'usuari > Contribucions > Cerca i visualització de contribucions](https://docs.civicrm.org/user/ca/latest/contributions/finding-and-viewing-contributions/) per a més informació de com actualitzar l'estat de les contribucions pendents.

## Gestió de donatius en espècie

Per tal d'identificar tots aquells contactes que sense fer una aportació directa sí que col·laboren amb l'entitat amb altres tipus d'aportacions considerades donacions en espècie, podrem registrar contribucions d'aquest tipus i posteriorment identificar-les.

### Registre de contribució en espècie

Des del contacte que fa l'aportació, crearem una nova contribució on especificarem almenys els següents camps:

- **Tipus financer:** ```Donatius en espècie```
- **Import** (el corresponent al valor de l'aportació)
- **Estat de la contribució:** ```Completat```
- **Data de recepció**
- **Mètode de pagament:** ```En espècie```
- **Preferències fiscals** indicar (si es sap) si demana o no desgravar el donatiu
- **Detalls agència tributària** indicar si no es vol declarar en el Model 182 l'aportació realitzada.
