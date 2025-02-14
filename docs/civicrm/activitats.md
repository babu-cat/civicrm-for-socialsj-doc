# Activitats

Les activitats són un concepte clau en el CiviCRM que ofereixen la possibilitat de registrar i visualitzar la història de les interaccions entre l'entitat i els seus contactes. Per definició, les activitats succeeixen en un moment específic en el temps, involucren almenys a un contacte i poden ser assignades a algun treballador de l'entitat o voluntari.

> Les activitats estan vinculades a un o més programes o departaments de l'entitat. Recollirem aquesta informació en un camp personalitzat.

## Estats d'activitat

Una activitat per defecte té els següents possibles estats:

- Programat (una activitat es pot deixar programada per una data futura marcant-la com a programada)
- Completat (l'activitat ja s'ha realitzat)
- Cancel·lat (l'activitat s'havia programat i s'ha cancel·lat)
- Missatge deixat
- Inassumible
- No requerit

Afegim un nou estat d'activitat que ens permeti marcar una activitat com a pendent de revisar:

- Pendent de revisar (és necessari completar o revisar algun camp abans de deixar l'activitat com a completada)

## Activitats amb contactes

- **Canvi d'adreça: **\* Registre d'un canvi d'adreça d'un contacte.

- **Col·laboració esporàdica:**  Registre d'una col·laboració esporàdica amb algun voluntari, tallerista o professional que fa alguna xerrada, taller o altre activitat no directament relacionada amb els projectes i cursos de l'entitat.

- **Coordinació [gestió i administració]: **\* Coordinació amb un contacte amb contingut sensible o privat només accessible per a perfils administradors.

## Activitats amb usuaris

> Infants / Joves i Adults infància del [mòdul infància](../infancia/index.md).

> Adults del [mòdul adults](../adults/index.md).

- **Acollida: **\* Registre d'una acollida d'un usuari a l'entitat amb o sense derivació.

- **Derivació: **\* Registre d'una derivació d'un usuari de l'entitat cap a una altra organització.

- **Migració: **\* Registre d'un desplaçament migratori d'un usuari de l'entitat.

## Activitats amb usuaris adults

> Adults infància del [mòdul infància](../infancia/index.md).

> Adults del [mòdul adults](../adults/index.md).

- **Registre de situació laboral: **\* Registre de situació laboral d'un usuari de l'entitat adult.

> \* Les activitats marcades amb un asterisc tenen definits camps personalitzats.

## Camps personalitzats d'activitats

### Activitats vinculades als programes o departaments de l'entitat

#### Vinculació a programes o departaments de l'entitat (activitats)

- **Programa o departament** - Programa o departament al qual queda vinculada l'activitat.

    Selecció múltiple - *llistat personalitzat per entitat*

### Canvi d'adreça

#### Canvi d'adreça

- **Adreça antiga**

    Àrea de text

### Coordinació [gestió i administració]

#### Coordinació

- **Modalitat**

    Selecció - Presencial; Trucada; Correu electrònic; Altres

- **Convocant** - Persona qui convoca la coordinació

    Contacte de referència

- **Temes tractats**

    Àrea de text

- **Acords**

    Àrea de text

### Acollida

#### Derivació acollida

- **Derivació** - L'usuari/ària ve derivat per una altra organització o per algun professional?

    Resposta Sí/No

- **Organització** - En cas de derivació indiqueu, si s'escau, l'organització que el deriva.

    Contacte de referència (organització)

- **Contacte** - En cas de derivació indiqueu, si s'escau, el professional que el deriva.

    Contacte de referència (professional)

- **Motius** - Indiqueu, si s'escau, els motius i detalls de la derivació.

    Àrea de text

### Derivació

#### Derivació

- **Organització** - Indiqueu l'entitat a la qual se'l deriva.

    Contacte de referència (organització)

- **Motius** - Indiqueu els motius de la derivació.

    Àrea de text

### Migració


#### Migració

- **País d'orígen** - Especifiqueu quin és el país origen de la migració.

    Selecció de país

- **Lloc d'origen** - Especifiqueu quina és la població o regió origen de la migració.

    Text

- **País de destí** - Especifiqueu quin és el país destí de la migració.

    Selecció de país

- **Lloc de destí** - Especifiqueu quina és la població o regió destí de la migració.

    Text

### Registre de situació laboral

#### Situació laboral registrada

- **Situació laboral** -

    *Ocupats*: Són les persones de 16 i més anys que durant la setmana de referència, han estat treballant – al menys durant una hora- per compte aliè (assalariats) o han exercit una activitat per compte propi.

    *Aturats*: Es consideren aturades, les persones de 16 o més anys que durant la setmana de referència han estat sense treball, estan disponibles per treballar i estan cercant activament treball.

    *Inactius*: Abasta a les persones de 16 o més anys no classificades com ocupades o aturades durant la setmana de referència. Comprèn les següents categories: Persones que s'ocupen de la seva llar, estudiants, jubilats o retirats, altres pensionistes, incapacitats per treballar i altres situacions.

    Selecció - Ocupat; Aturat; Inactiu

- **CV**

    Fitxer

- **Observacions situació laboral**

    Àrea de text
