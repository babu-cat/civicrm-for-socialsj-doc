# Mòdul esdeveniments

A CiviCRM, un esdeveniment és quelcom que succeeix en un moment determinat en el temps, té un procés d'inscripció i té un seguit de participants.

Els esdeveniments ens serviran per gestionar la relació dels cursos, programes, projectes i altres esdeveniments de l'entitat amb els seus respectius participants. Per fer-ho, el CiviCRM defineix els següents elements que seran desenvolupats per a cada entitat en els següents apartats segons les seves especificitats.

## Tipus d'esdeveniments

El CiviCRM permet definir diferents tipus d'esdeveniments com ara cursos, trobades i conferències, entre d'altres. Aquesta categorització dels esdeveniments resulta útil per exemple per cercar participants en els esdeveniments o bé per crear camps personalitzats per desar i mostrar informació addicional referent al tipus d'esdeveniment.

Per defecte, habilitarem els següents tipus d'esdeveniments:

- **Preinscripció:** Tipus d'esdeveniment que ens permetrà gestionar processos de preinscripció a altres esdeveniments quan aquests ho requereixin. D'aquesta manera serem capaços de mantenir informació de totes les persones que s'han acostat interessades a l'entitat però que pel motiu que sigui (places cobertes, impediments d'horaris, manca d'interès, etc.) al final no han arribat a inscriure's a l'esdeveniment.
- **Esdeveniment intern:** Esdeveniment de caràcter intern, formacions, trobades, dinars, reunions d'equip, etc.
- **Esdeveniment públic:** Esdeveniment de caràcter públic, actes, conferències i altres esdeveniments.

## Rols de participant

En el moment d'inscriure una persona a un esdeveniment, se li assigna un rol de participant, d'aquesta manera els rols ens permeten segmentar els participants en categories basades en la seva implicació en l'esdeveniment i aprofitar-les per exemple per enviar correus electrònics als voluntaris o generar una llista de tots els assistents d'un tipus concret d'esdeveniment.

Per defecte, habilitarem els següents tipus de rols:

- **Participant**

El CiviCRM també permet crear camps personalitzats que s'apliquin únicament a rols específics per desar i mostrar informació addicional referent al rol del participant.

## Estats de participant

L'estat del participant permet fer un seguiment individual i col·lectiu del procés d'inscripció d'un esdeveniment. A continuació es llista el conjunt de possibles estats de participant junt amb una breu explicació de cada un d'ells.

- **Inscrit (pagat, gratuït o NA)** - El contacte està inscrit a l'esdeveniment i ha pagat o bé no s'aplica cap import o tarifa en aquesta inscripció.
- **Inscrit (pendent de pagament)** - El contacte està inscrit a l'esdeveniment però encara ha d'efectuar el pagament corresponent.
- **Inscrit (parcialment impagat)** - El contacte ha participat a l'esdeveniment però no ha pagat la totalitat de l'import corresponent i ja no s'espera que ho faci.
- **Inscrit (impagat)** - El contacte ha participat a l'esdeveniment però no ha pagat i ja no s'espera que ho faci.
- **No mostris** - No es desitja comptabilitzar la inscripció per aquest contacte per exemple en el cas d'un professor o d'un voluntari.
- **Cancel·lat** - S'ha cancel·lat la inscripció del contacte a l'esdeveniment.
- **Baixa** - El contacte ha estat inscrit a l'esdeveniment però causa baixa un cop ja ha començat.
- **A la llista d'espera** - El contacte està a la llista d'espera de l'esdeveniment.
- **Expirat** - Ha expirat el període que tenia el contacte per completar la inscripció.
- **Parcialment pagat** - El contacte està inscrit a l'esdeveniment però encara no ha pagat la totalitat de la inscripció.
- **Pendent de reembossament** - El contacte és baixa o vol cancel·lar la inscripció a l'esdeveniment i està pendent de rebre el reembossament corresponent.
- **Transferit** - El contacte ha cedit la seva inscripció a un altre contacte.
- **Pendent al cistell** - En el cas de tenir habilitada l'opció d'inscripcions per cistell de la compra (per defecte es troba deshabilitada) aquest estat indica que el contacte ha afegit la inscripció a l'esdeveniment al cistell.
- **Convidat** - El contacte ha estat convidat a participar de l'esdeveniment.
- **No vindrà** - El contacte ha manifestat que no podrà participar a l'esdeveniment.
- **Confirmat** - El contacte ha manifestat la seva participació a l'esdeveniment.
- **Ha assistit** - El contacte ha participat a l'esdeveniment.
- **No ha assistit** - El contacte no ha participat a l'esdeveniment.

Els següents estats de participant tan sols tenen sentit quan intervé un processador de pagament en el procés d'inscripció.

- **Pendent (pagament diferit)** - El contacte ha sol·licitat la inscripció i ha escollit l'opció de fer el pagament més tard.
- **Pendent (transacció incompleta)** - El contacte ha sol·licitat la inscripció i ha tingut algún problema a l'hora de fer el pagament.

## Tarifes

El mòdul d'esdeveniments del CiviCRM, juntament amb el mòdul de contribucions, permet recopilar i fer el seguiment de pagaments de tarifes d'esdeveniments. Quan es configura un esdeveniment s'hi pot assignar una tarifa per a què posteriorment, en el moment de la inscripció, s'hi pugui registrar un pagament.

Les tarifes provinents dels esdeveniments són analitzades com a contribucions utilitzant el mòdul de contribucions del CiviCRM.

## Camps personalitzats a nivell d'esdeveniment

Utilitzarem els següents camps personalitzats per a tots els esdeveniments.

## Protecció de dades

- **Avís legal**

    Àrea de text

## Camps personalitzats a nivell d'inscripció a l'esdeveniment

Utilitzarem els següents camps personalitzats per a tots aquells esdeveniments que requereixin del registre del nombre d'assistents a l'esdeveniment i que no facin la inscripció dels participants a través del CRM.

### Resum de l'esdeveniment

- **Nombre d'assistents** - Nombre final d'assistents a l'esdeveniment.

    Numèric

- **Observacions** - Altres observacions posteriors a la celebració de l'esdeveniment.

    Àrea de text

Utilitzarem els següents camps personalitzats per a tots aquells esdeveniments que requereixin de la digitalització de la justificació de les inscripcions i baixes als esdeveniments.

### Inscripció

- **Inscripció** - Fitxa d'inscripció a l'esdeveniment digitalitzada.

    Fitxer

Utilitzarem els següents camps personalitzats per a tots aquells esdeveniments que requereixin de l'acceptació d'un contracte pedagògic associat a l'esdeveniment en el qual es fa la inscripció.

### Contracte pedagògic

- **Contracte pedagògic** - Contracte pedagògic digitalitzat.

    Fitxer
