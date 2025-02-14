# Mòdul Xarxa d'Hospitalitat

!!! info "Dependències amb altres mòduls"
    - Mòdul adults
    - Mòdul de voluntariat

## Contactes

!!! info ""
    Vegeu més informació sobre els contactes a [CiviCRM > Contactes](../civicrm/contactes.md).

Crearem un nou tipus de contacte `Llar` que ens permetrà identificar un dels 3 actors
que conformen el mòdul de Xarxa d'Hospitalitat. Els altres dos tipus de contactes
`Persona migrant + Adult` i `Voluntari` ja queden definits per les dependències del
mòdul Xarxa d'Hospitalitat.

### Persones

!!! info "Adult"
    Vegeu a [Mòdul adults > Contactes](../adults/contactes.md#persones)

!!! info "Persona migrant"
    Vegeu a [CiviCRM > Contactes](../civicrm/contactes.md#persones)

!!! info "Voluntari"
    Vegeu a [CiviCRM > Mòdul voluntariat, pràctiques i educació en el lleure > Voluntariat > Contactes](../voluntariat-practiques-educacio-lleure/voluntariat/contactes.md).

### Llars

#### Llar d'acollida

Llar implicada en l'acollida de persones migrants.

#### Espai comunitari

Espai implicat en l'acollida de persones migrants.

## Activitats

### [Xarxa Hospitalitat] Família interessada

Primer contacte d'una família amb interès d'acollir una persona migrada.

**Possibles estats de l'activitat**

- Pendent de contactar
- Pendent de resoldre
- Completat
- Cancel·lat pendent de donar alternatives
- Cancel·lat

### [Xarxa Hospitalitat] Seguiment

**Camps personalitzats**

* Seguiment Xarxa Hospitalitat

    * **Àmbit**

        Selecció múltiple - Acompanyament, Acollida

    * **Observacions**

        Resposta oberta

## Relacions

### Relació d'acompanyament Xarxa d'Hospitalitat

Característiques | &nbsp;
---------------- | ------------
Contacte A       | Voluntari     
Contacte B       | Persona migrant       
Relació A-B      | acompanya en Xarxa d'Hospitalitat a
Relació B-A      | és acompanyat en Xarxa d'Hospitalitat per

### Relació d'acollida en llar de Xarxa d'Hospitalitat

Característiques | &nbsp;
---------------- | ------------
Contacte A       | Persona migrant     
Contacte B       | Llar d'acollida       
Relació A-B      | és acollida en Xarxa d'Hospitalitat a
Relació B-A      | acull en Xarxa d'Hospitalitat a

### Relació de responsable de la llar

Utilitzarem la relació de responsable de la llar `és responsable de la llar de`
per indicar les persones responsables de la llar amb les quals l'organització
estableix comunicació en el procés d'acollida.

### Relació de pertinença a la llar

Utilitzarem la relació de pertinença a la llar `és membre de la llar de` per indicar
les persones amb les quals volem poder establir algun tipus d'interacció amb el
CRM però que no són les responsables o interlocutores directes de l'acollida.

### Relació de voluntariat

!!! info ""
    Vegeu a [CiviCRM > Mòdul voluntariat, pràctiques i educació en el lleure > Voluntariat > Relacions](../voluntariat-practiques-educacio-lleure/voluntariat/relacions.md#es-voluntariaria-a-te-de-voluntariaria-a).

## Grups

!!! info ""
    Vegeu més informació sobre els grups a [CiviCRM > Grups](../civicrm/grups.md).

El mòdul definirà per defecte la següent jerarquia de grups:

- **Xarxa d'Hospitalitat**

    - **Llars d'acollida en Xarxa d'Hospitalitat**
        - **Llars d'acollida en Xarxa d'Hospitalitat - actives (grup intel·ligent)**
        - **Llars d'acollida en Xarxa d'Hospitalitat - històriques (grup intel·ligent)**
    - **Voluntaris d'acollida en Xarxa d'Hospitalitat**
        - **Voluntaris d'acollida en Xarxa d'Hospitalitat - actius (grup intel·ligent)**
        - **Voluntaris d'acollida en Xarxa d'Hospitalitat - històrics (grup intel·ligent)**
    - **Voluntaris d'acompanyament en Xarxa d'Hospitalitat**
        - **Voluntaris d'acompanyament en Xarxa d'Hospitalitat - actius (grup intel·ligent)**
        - **Voluntaris d'acompanyament en Xarxa d'Hospitalitat - històrics (grup intel·ligent)**
    - **Persones acollides en Xarxa d'Hospitalitat**
        - **Persones acollides en Xarxa d'Hospitalitat - actius (grup intel·ligent)**
        - **Persones acollides en Xarxa d'Hospitalitat - històric (grup intel·ligent)**
    - **Famílies interessades en XH pendents de contactar**
    - **Responsables famílies interessades en XH pendents de contactar**
    - **Famílies interessades en XH pendents d'alternativa**
    - **Responsables famílies interessades en XH pendents d'alternativa**

## Informes

### Acollides en Xarxa d'Hospitalitat - actives

* Menú

    Informes personalitzats > Xarxa d'Hospitalitat > Acollides en Xarxa d'Hospitalitat - actives

* Tipus d'informe

    Informe de relacions

* Columnes

    * Relació A-B
    * Data d'inici de la relació
    * Data de finalització de la relació

* Filtres

    * Relació = `és acollida en Xarxa d'Hospitalitat a`
    * Grup = `persones acollides en Xarxa d'Hospitalitat - actives`


### Famílies interessades

* Descripció

    Famílies que tenen una activitat `[Xarxa Hospitalitat] Família interessada`

* Menú

    Informes personalitzats > Xarxa d'Hospitalitat > Famílies interessades

* Tipus d'informe

    Informe de detalls d'activitat

* Columnes

    * Nom del contacte destí
    * Tipus d'activitat
    * Data de l'activitat
    * Estat de l'activitat
    * Detalls de l'activitat

* Ordenació

    * Data de l'activitat *(Descendent)*

* Filtres

    * Tipus d'activitat = `[Xarxa Hospitalitat] Família interessada`
