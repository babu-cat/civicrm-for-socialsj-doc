# Contactes

En el CiviCRM els contactes són totes aquelles persones físiques, famílies, entitats, organitzacions, empreses, etc. que tenen un tipus de relació determinada amb l'entitat. Una de les tasques més importants per implementar el CRM és identificar quins són aquests contactes, quines són les dades que ens interessen de cada un d'ells i quines activitats i relacions estableixen aquests amb la mateixa entitat i la resta de contactes.

Per defecte es distingeixen els contactes en tres tipus bàsics: **persona**, **llar** i **organització**. A partir d'aquí definim la resta de tipus de contactes que tenen relació amb l'entitat.

## Persones

- **Persona: **\* qualsevol persona que té vinculació directa o indirecta amb l'entitat.
- **Persona migrant: **\* persona usuària de l'entitat que ha realitzat un procés migratori cap al nostre país.
- **Professional: **\* professionals que presten o poden prestar assistència a participants dels diferents programes de l'entitat.
- **Usuaris: **\* en els mòduls definim diferents tipus de persones usuàries de l'entitat que actuen com a tipus de contactes.
- **Usuaris adults: **\* en els mòduls definirem diferents tipus de persones adultes usuàries de l'entitat que actuen com a tipus de contactes.
- **Treballador:** treballador de l'entitat.

### Perfil demogràfic

- Gènere: `Dona`; `Home`; `No-binari`;

## Organitzacions

- **Organització:** qualsevol organització que té vinculació directa o indirecta amb l'entitat.
- **Centre educació infantil: **\* centre d'educació infantil vinculat als participants dels diferents programes de l'entitat.
- **Centre educació primària: **\* centre d'educació primària vinculat als participants dels diferents programes de l'entitat.
- **Centre educació secundària: **\* centre d'educació secundària vinculat als participants dels diferents programes de l'entitat.
- **Centre de batxillerat: **\* centre de batxillerat vinculat als participants dels diferents programes de l'entitat.
- **Col·legi professional:** Col·legis de psicòlegs, psicopedagogs i d'altres professionals vinculats directament o indirecta amb els participants dels diferents programes de l'entitat.

## Llars

- **Llar:** qualsevol llar que té vinculació directa o indirecta amb l'entitat.

> \* Els contactes marcats amb un asterisc tenen definits camps personalitzats.

## Camps personalitzats

### Persona

#### Documentació

- **Tipus de document** - Seleccioneu el tipus de document que acrediti la identitat de la persona tenint en compte el següent ordre com a prioritat a l'hora de triar el tipus de document : NIF, NIE, Passaport, Altres, Sense documentació.

    Selecció - `NIF`; `NIE`; `Passaport`; `Altres`; `Sense documentació`

- **Número de document**

    Text

- **Observacions** - Si ho creieu oportú podeu afegir alguna observació que ajudi a complementar els camps anteriors.

    Àrea de text

### Persona migrant


#### Perfil migratori

- **Any d'arribada Espanya** - Especifiqueu quin any va arribar a Espanya.

    Data (any i mes)

- **Any d'arribada Catalunya** - Especifiqueu quin any va arribar a Catalunya.

    Data (any i mes)

- **Recorregut migratori**

    Àrea de text

- **Alfabetització llatina** - Coneix l'alfabet llatí?

    Resposta Sí/No

- **Ha estat menor tutelat**

    Resposta Sí/No

- **Situació administrativa**

    Selecció - `Irregular`; `Residència i treball temporal`; `Residència i treball permanent`; `Residència sense treball (temporal i/o permanent?)`; `Sol·licitant d'asil`; `Refugiat`; `Comunitari`; `Nacionalitat`;

- **Targeta sanitària**

    Selecció - `Regulada`; `En tramitació`; `Li falta algun document`; `No pot sol·licitar-la`;

- **Empadronat/da** - Està donat/da d'alta al padró d'algun municipi?

    Resposta Sí/No

- **Data primer empadronament** - Data del primer empadronament a algun municipi d'Espanya

    Data (any i mes)

- **Document de veïnatge** - (Barcelona) L'ajuntament li ha acreditat el veïnatge a la ciutat?

    Resposta Sí/No

- **Observacions**

  Àrea de text
  
#### Perfil acadèmic i professional persona migrant

- Homologació - Té el nivell d'estudis homologat?

    Resposta Sí/No

- Homologació (observacions)

    Àrea de text

### Professional

#### Perfil professional

- **Tipus de professional**

    Casella de selecció - `psicòleg/loga`; `psicopedagog/a`; `treballador/a social`; `educador/a social`; `inspector/a d'ensenyament`; `logopeda`; `psiquiatra`; `pediatra`

### Treballador

#### Dades del treballador

- **Número d'afiliació a la Seguretat Social**

    Text

### Usuaris

> Persones migrants

> Infants / Joves i Adults infància del [mòdul infància](/infancia).

> Adults del [mòdul adults](/adults).

> Persones grans del [mòdul gent gran](/gent-gran)

#### Perfil demogràfic usuari/ària

- **Nacionalitat** - Seleccioneu el país o països d'on té la nacionalitat el contacte.

    Multiselecció de país

- **País de naixement**

    Selecció de país

- **Lloc de naixement** - Indica la població o regió de naixement.

    Text

- **Llengua materna** -  Vegeu [Documentació - Annex: Llistat d'idiomes](http://docs.crm.socialsj.cat/civicrm/annex-idiomes).

    Selecció múltiple - *vegeu [Annex: Llistat d'idiomes](/civicrm/annex-idiomes)*

### Usuaris adults

> Adults infància del [mòdul infància](/infancia)..

> Adults del [mòdul adults](/adults).

#### Perfil adult

- **Estat civil**

    Casella de selecció - `Solter/a`; `Casat/da`; `Divorciat/da`; `Separat/da de fet`; `Separat/da`; `Parella de fet`; `Parella`; `Vidu/a`

#### Perfil lingüístic

- **Alfabetització** - Sap llegir i escriure en algun alfabet?

    Resposta Sí/No

- **Català** - Coneix el català?

    Resposta Sí/No

- **Nivell català** - Si coneix el català, especifiqueu orientativament quin nivell té segons el marc europeu comú de referència per a les llengües on:

    A - *Usuari bàsic* (engloba el nivell A1 i A2, inicial i bàsic respectivament)  

    B - *Usuari independent* (engloba el nivell B1 i B2, llindar i avançat respectivament)

    C - *Usuari experimentat* (engloba el nivell C1 i C2, domini funcional efectiu i domini respectivament)

    Selecció - Usuari/a bàsic; Usuari/a independent; Usuari/a experimentat

- **Castellà** Coneix el castellà?

    Resposta Sí/No

- **Nivell castellà** - Si coneix el castellà, especifiqueu orientativament quin nivell té segons el marc europeu comú de referència per a les llengües on:

    A - *Usuari bàsic* (engloba el nivell A1 i A2, inicial i bàsic respectivament)  

    B - *Usuari independent* (engloba el nivell B1 i B2, llindar i avançat respectivament)

    C - *Usuari experimentat* (engloba el nivell C1 i C2, domini funcional efectiu i domini respectivament)

    Selecció - `Usuari/a bàsic`; `Usuari/a independent`; `Usuari/a experimentat`

- **Altres idiomes** - Si coneix o domina altres idiomes especifiqueu quins. Vegeu [Documentació - Annex: Llistat d'idiomes](http://docs.crm.socialsj.cat/civicrm/annex-idiomes).

    Selecció múltiple - *vegeu [Annex: Llistat d'idiomes](/civicrm/annex-idiomes)*

### Adults, Adults - infància, Treballadors, Voluntaris i Estudiants en pràctiques

#### Perfil acadèmic i professional

- **Nivell d'estudis** - Indiqueu quin nivell d'estudis acabats té:

    *Estudis primaris*: corresponen a uns estudis iguals o equivalents a l'educació primària

    *Estudis secundaris*: corresponen a uns estudis d'educació secundaria obligatoria, batxillerat, formació professional de grau mig o equivalents

    *Estudis superiors*: corresponen a uns estudis de formació professional superior, universitaris o equivalents

    Selecció - `Sense estudis`; `Estudis primaris`; `Estudis secundaris`; `Estudis superiors`

- **Titulacions superiors o professionals** - Si ha cursat estudis superiors o professionals especifiqueu quines titulacions ha obtingut (p. ex. Llicenciatura en dret, Tècnic en gestió administrativa, Tècnic superior en manteniment electrònic, etc.) i, si s'escau, indiqueu si ha obtingut alguna titulació a l'estranger i especifiqueu si aquests estudis estan reconeguts en el nostre país.

    Àrea de text

- **Professió** - Especifiqueu quina o quines son les seves professions (p. ex. Mecànic, Mestre/a de primària, Arquitecte/a, Lampista, Auxiliar d'infermeria, Empleat/da de la llar)

    Àrea de text

### Organització

#### Documentació organitzacions

- **CIF** - Codi d'identificació fiscal

    Text

### Centres educatius (infantil, primària, secundària i batxillerat)

#### Perfil centre educatiu

- **Naturalesa del centre**

    Selecció - `pública`; `privada`

- **Titularitat del centre**

    Selecció - `laica`; `religiosa`
