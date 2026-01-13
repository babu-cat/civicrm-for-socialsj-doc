# Relacions

El CiviCRM permet representar connexions entre contactes a través de relacions. Per exemple, per defecte és possible establir relacions laborals entre una persona i una organització, o bé també establir una relació de parentiu entre una mare i un fill, com també una relació de pertinença entre una persona i una llar.

A part d'aquestes relacions preestablertes en definirem unes de noves que ens permetran completar tot el ventall de relacions que volem reflectir entre els contactes de la nostra entitat.

> Algunes relacions poden estar vinculades a un programa en concret de l'entitat. En aquests casos recollirem aquesta informació en un camp personalitzat.

## Familiars

### Relació pares/fills

- Contacte A: Persona
- Contacte B: Persona
- Relació A>B: és fill/a de
- Relació B>A: és pare/mare de

### Relació de germans

- Contacte A: Persona
- Contacte B: Persona
- Relació A>B: és germà/ana de
- Relació B>A: és germà/ana de

### Relació avis/nets

- Contacte A: Persona
- Contacte B: Persona
- Relació A>B: és avi/àvia de
- Relació B>A: és nét/eta de

### Relació oncles/nebots

- Contacte A: Persona
- Contacte B: Persona
- Relació A>B: és oncle/tieta de
- Relació B>A: és nebot/da de

### Relació de cosins

- Contacte A: Persona
- Contacte B: Persona
- Relació A>B: és cosí/ina de
- Relació B>A: és cosí/ina de

### Relació padrastres/fillastres

- Contacte A: Persona
- Contacte B: Persona
- Relació A>B: és fillastre/a de
- Relació B>A: és padrastre/madrastra de

### Relació de germanastres

- Contacte A: Persona
- Contacte B: Persona
- Relació A>B: és germanastre/a de
- Relació B>A: és germanastre/a de

## Convivència

### Relació de pertinença a una llar

- Contacte A: Persona
- Contacte B: Llar
- Relació A>B: és membre de la llar
- Relació B>A: té de membre de la llar a

### Relació de cap d'una llar

- Contacte A: Persona
- Contacte B: Llar
- Relació A>B: és cap de la llar de
- Relació B>A: té de cap de la llar a

## Altres tipus de relacions

### Relació de treball	*

- Contacte A: Persona
- Contacte B: Organització
- Relació A>B: treballa a
- Relació B>A: té treballant a

### Relació de treball externalitzat *

- Contacte A: Persona
- Contacte B: Organització
- Relació A>B: treballa per
- Relació B>A: té de treballador extern a

### Relació de patronat *

- Contacte A: Persona
- Contacte B: Organització
- Relació A>B: és patró de
- Relació B>A: té de patró a

### Relació de pertinença a una organització

- Contacte A: Persona
- Contacte B: Organització
- Relació A>B: és membre de
- Relació B>A: té de membre a

### Relació de col·legiat. *

- Contacte A: Persona
- Contacte B: Col·legi professional
- Relació A>B: està col·legiat/da a
- Relació B>A: té de col·legiat/da a

### Relació d'atenció. *

- Contacte A: Tots els contactes (no hauria de ser una organització)
- Contacte B: Organització
- Relació A>B: rep atenció per part de
- Relació B>A: proporciona atenció a

### Relació de vinculació.

- Contacte A: Organització
- Contacte B: Organització
- Relació A>B: està vinculat/da a
- Relació B>A: està vinculat/da a

## Acompanyament des de l'entitat

### Relació de referent familiar

- Contacte A: Unitat familiar i de convivència
- Contacte B: Treballador
- Relació A>B: té de referent familiar a
- Relació B>A: és referent familiar de

> \* Les relacions marcades amb un asterisc tenen definits camps personalitzats.

## Camps personalitzats

### Relacions vinculades als programes o departaments de l'entitat

#### Vinculació a un programa o departament de l'entitat (relacions)

- **Programa o departament** - Programa o departament al qual queda vinculada la relació.

    Selecció - *llistat personalitzat per entitat*

### Relació de treball

#### Lloc de treball

- **Càrrec** - Càrrec que ocupa el treballador en l'organització.

    Text

### Relació de patronat

#### Lloc de patró

- **Càrrec** - Càrrec que ocupa el patró en l'organització.

    Selecció - President/a; Vicepresident/a; Secretari/ària; Tresorer/a; Vocal

- **En condició de** - Condició de patró.

    Selecció - Persona física; representant de persona jurídica

- **Representant de** - En cas de ser patró en condició de representant d'una persona jurídica especifiqueu quina.

    Contacte de referència (organització)

### Relació de col·legiat

#### Dades col·legiat

- **Número de col·legiat**

    Text

### Relació d'atenció

#### Atenció professional

- **Especialista de referència**

    Contacte de referència (professional)

- **Motius**

    Àrea de text
