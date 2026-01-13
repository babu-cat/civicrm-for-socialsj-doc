# Relacions

> Vegeu més informació sobre les relacions a [CiviCRM > Relacions](../civicrm/relacions.md).

Definirem un seguit de relacions que ens permetran establir les diverses connexions entre els diferents tipus de contactes dels programes d'infància de l'entitat.

## Familiars

### Relació de tutela legal

- Contacte A: Infant / Jove
- Contacte B: Persona
- Relació A>B: té de tutor/a legal a
- Relació B>A: és tutor/a legal de

### Relació de guarda administrativa

- Contacte A: Infant / Jove
- Contacte B: Organització
- Relació A>B: es troba sota la guarda administrativa de
- Relació B>A: té la guarda administrativa de

## Acompanyament des de l'entitat

### Relació de referent infant/jove

- Contacte A: Infant/Jove
- Contacte B: Treballador
- Relació A>B: té de referent infant/jove a
- Relació B>A: és referent infant/jove de

## Escolarització

### Relació de tutoria *

- Contacte A: Infant / Jove
- Contacte B: Docent
- Relació A>B: té de tutor/a a
- Relació B>A: és tutor/a de

### Relació d'estudis infantils	*

- Contacte A: Infant / Jove
- Contacte B: Centre educació infantil
- Relació A>B: estudia infantil a
- Relació B>A: té com a estudiant d'infantil a

### Relació d'estudis primaris *

- Contacte A: Infant / Jove
- Contacte B: Centre educació primària
- Relació A>B: estudia primària a
- Relació B>A: té com a estudiant de primària a

### Relació d'estudis secundaris *

- Contacte A: Infant / Jove
- Contacte B: Centre educació secundària
- Relació A>B: estudia secundària a
- Relació B>A: té com a estudiant de secundària a

### Relació d'estudis de batxillerat *

- Contacte A: Infant / Jove
- Contacte B: Centre de batxillerat
- Relació A>B: estudia batxillerat a
- Relació B>A: té com a estudiant de batxillerat a

### Relació d'estudis UEC *

- Contacte A: Infant / Jove
- Contacte B: UEC
- Relació A>B: estudia a la UEC
- Relació B>A: té com a estudiant de la UEC a

### Relació d'estudis d'adults

- Contacte A: Infant / Jove
- Contacte B: Centre formació d'adults
- Relació A>B: estudia al centre de formació d'adults
- Relació B>A: té com a estudiant del centre de formació d'adults a

### Relació d'atenció logopèdica a primària *

- Contacte A: Infant / Jove
- Contacte B: Centre educació primària
- Relació A>B: rep atenció logopèdica al centre d'educació primaria de
- Relació B>A: proporciona atenció logopèdica al centre d'educació primària a

### Relació d'atenció logopèdica a secundària *

- Contacte A: Infant / Jove
- Contacte B: Centre educació secundària
- Relació A>B: rep atenció logopèdica al centre d'educació secundària de
- Relació B>A: proporciona atenció logopèdica al centre d'educació secundària a

### Relació d'aula d'acollida a primària *

- Contacte A: Infant / Jove
- Contacte B: Centre educació primària
- Relació A>B: participa a l'aula d'acollida de primària de
- Relació B>A: té a l'aula d'acollida de primària a

### Relació d'aula d'acollida a secundària *

- Contacte A: Infant / Jove
- Contacte B: Centre educació secundària
- Relació A>B: participa a l'aula d'acollida de secundària de
- Relació B>A: té a l'aula d'acollida de secundària a

### Relació de participació a l'USEE a primària *

- Contacte A: Infant / Jove
- Contacte B: Centre educació primària
- Relació A>B: participa a l'USEE de primària de
- Relació B>A: té a l'USEE de primària a

### Relació de participació a l'USEE a secundària	*

- Contacte A: Infant / Jove
- Contacte B: Centre educació secundària
- Relació A>B: participa a l'USEE de secundària de
- Relació B>A: té a l'USEE de secundària a

### Relació de participació a l'aula oberta a secundària *

- Contacte A: Infant / Jove
- Contacte B: Centre educació secundària
- Relació A>B: participa a l'aula oberta de
- Relació B>A: té a l'aula oberta a

## CaixaProInfància

### Relació de beca CPI *

- Contacte A: Fundació la Caixa
- Contacte B: Infant / Jove
- Relació A>B: concedeix una beca CPI a
- Relació B>A: és beneficiari d'una beca CPI per

## Altres tipus de relacions

### Relació d'acompanyant

- Contacte A: Infant / Jove
- Contacte B: Persona
- Relació A>B: pot marxar acompanyat per
- Relació B>A: pot recollir a

> \* Les relacions marcades amb un asterisc tenen definits camps personalitzats.

## Camps personalitzats

### Relació de tutoria

#### Tutoria

- **Centre educatiu**

    Contacte de referència (centres educatius)

### Relació d'estudis infantils

#### Estudis infantil

- **Curs**

    Selecció múltiple - P3; P4; P5

### Relació d'estudis primaris

#### Estudis primària

- **Curs**

    Selecció múltiple - 1r; 2n; 3r; 4t; 5è; 6è

- **Repeteix**

    Selecció múltiple - 1r; 2n; 3r; 4t; 5è; 6è

### Relació d'estudis secundaris

#### Estudis secundària obligatòria

- **Curs**

    Selecció múltiple - 1r; 2n; 3r; 4t

- **Repeteix**

    Selecció múltiple - 1r; 2n; 3r; 4t

### Relació d'estudis UEC

#### Estudis UEC

- **Curs**

    Selecció múltiple - 1r; 2n; 3r; 4t

- **Repeteix**

    Selecció múltiple - 1r; 2n; 3r; 4t

- **Derivat per**

    Contacte de referència (professional)

- **Motius**

    Àrea de text	 

### Relacions d'atenció logopèdica a primaria i secundària

#### Atenció professional

- **Especialista de referència**

    Contacte de referència (professional)

- **Motius**

    Àrea de text	 

### Relacions de participació a l'aula d'acollida, a l'USEE i a l'aula oberta

#### Atenció docent

- **Docent de referència**

    Contacte de referència (docent)

- **Motius**

    Àrea de text

### Relació beca CPI

#### Beca CPI

- **Servei CPI**

    Selecció - Atenció psicoterapèutica; Atenció psicoterapèutica personalitzada; Atenció terapèutica a famílies - baixa; Atenció terapèutica a famílies - mitjana; Atenció terapèutica a famílies - alta; Tallers terapèutics grupals; Atenció logopèdica; Suport psicomotriu; Aula oberta - 8 mesos primària; Aula oberta - 8 mesos secundària; Aula oberta - 7 mesos primària; Aula oberta - 7 mesos secundària; Aula oberta - 6 mesos primària; Aula oberta - 6 mesos secundària; Aula oberta - 5 mesos primària; Aula oberta - 5 mesos secundària; Aula oberta - 4 mesos primària; Aula oberta - 4 mesos secundària; Aula oberta - 3 mesos primària; Aula oberta - 3 mesos secundària; Aula oberta - 2 mesos primària; Aula oberta - 2 mesos secundària; Aula oberta - 1 mes primària; Aula oberta - 1 mes secundària; Grup d'estudi assistit - 8 mesos primària; Grup d'estudi assistit - 8 mesos secundària; Grup d'estudi assistit - 7 mesos primària; Grup d'estudi assistit - 7 mesos secundària; Grup d'estudi assistit - 6 mesos primària; Grup d'estudi assistit - 6 mesos secundària; Grup d'estudi assistit - 5 mesos primària; Grup d'estudi assistit - 5 mesos secundària; Grup d'estudi assistit - 4 mesos primària; Grup d'estudi assistit - 4 mesos secundària; Grup d'estudi assistit - 3 mesos primària; Grup d'estudi assistit - 3 mesos secundària; Grup d'estudi assistit - 2 mesos primària; Grup d'estudi assistit - 2 mesos secundària; Grup d'estudi assistit - 1 mes primària; Grup d'estudi assistit - 1 mes secundària; Reforç individual - 8 mesos primària; Reforç individual - 8 mesos secundària; Reforç individual - 7 mesos primària; Reforç individual - 7 mesos secundària; Reforç individual - 6 mesos primària; Reforç individual - 6 mesos secundària; Reforç individual - 5 mesos primària; Reforç individual - 5 mesos secundària; Reforç individual - 4 mesos primària; Reforç individual - 4 mesos secundària; Reforç individual - 3 mesos primària; Reforç individual - 3 mesos secundària; Reforç individual - 2 mesos primària; Reforç individual - 2 mesos secundària; Reforç individual - 1 mes primària; Reforç individual - 1 mes secundària; Centre obert - 9 mesos; Centre obert - 8 mesos; Centre obert - 7 mesos; Centre obert - 6 mesos; Centre obert - 5 mesos; Centre obert - 4 mesos; Centre obert - 3 mesos; Centre obert - 2 mesos; Centre obert - 1 mes; Colònies urbanes; Campaments - 3 dies; Campaments - 5 dies; Campaments - 7 dies; Campaments - 15 dies; Espais familiars; Centre materno infantil - continuïtat; Tallers educatius familiars; Tallers educatius familiars - continuïtat

- **Codi beca**

    Text
