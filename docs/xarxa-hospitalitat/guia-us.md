# Guia d'ús

!!! info "Cal tenir en compte"
    - Abans de donar d'alta cap contacte al CRM cal mirar abans que no existeixi.
    - La comunicació per correu electrònic l'establirem amb les persones responsables
    de la llar. Per aquest motiu el correu electrònic de contacte ha d'estar definit
    en la fitxa de la persona i no en la de la llar.

## Famílies interessades

### Família interessada nova

En general quan una família mostra el seu interès en ser família acollidora
procedirem de la següent manera:

1. Donar d'alta el contacte del tipus `Llar`
2. Donar d'alta el contacte tipus `Persona`
3. Crear una relació entre la llar i la persona del tipus `té de responsable de
la llar a`
4. Crear una activitat `[Xarxa Hospitalitat] Família interessada` a la llar interessada

    - Posar la data en que ha mostrat l'interès al camp `Data de l'activitat`
    - Definir el camp `Estat` com a
        - `Pendent de contactar` si no s'ha contactat encara amb el responsable de la llar
        - `Pendent de resoldre` altrament, per indicar que la família està en procés de
    decidir si passa a ser família acollidora

### Seguiment famílies interessades

En l'informe que podem trobar a **Informes personalitzats > Xarxa d'Hospitalitat >
Famílies interessades** podem veure el llistat de totes les famílies que han mostrat
el seu interès en ser famílies d'acollida. En el mateix informe podem filtrar per
l'`Estat de l'activitat` per veure les famílies que es troben

* Pendents de contactar (`Pendent de contactar`)
* Pendents de decidir si passen a ser família d'acollida o no (`Pendent de resoldre`)
* Han decidit ser família d'acollida (`Completat`)
* Han descartat ser família d'acollida però encara els hi volem oferir una alternativa
(`Cancel·lat pendent de donar alternatives`)
* Han descartat ser família d'acollida (`Cancel·lat`)

### Contactar amb famílies interessades

Quan ens posem en contacte amb una família acollidora cal modificar l'estat de
l'activitat `[Xarxa Hospitalitat] Família interessada` de `Pendent de contactar` a
`Pendent de resoldre`.

#### Enviament de correu electrònic a famílies interessades

Es pot enviar un correu electrònic aprofitant una plantilla predefinida a cada
responsable de la llar de les famílies interessades. Depenent de si tenim moltes
famílies per contactar ho farem mitjançant un correu electrònic individual o bé
programant un mailing.

Podem fer una cerca ràpida sobre el grup `Responsables famílies interessades en XH pendents de contactar` i triar l'acció que més ens convingui sobres tots els contactes
o bé sobre una selecció.

Tant si contactem per correu electrònic com si ho fem d'alguna altre manera, un cop
establert el contacte amb la família, com dèiem en el punt anterior, haurem de
modificar l'estat de l'activitat `[Xarxa Hospitalitat] Família interessada` a
`Pendent de resoldre`.

### Resolució

Quan la família, un cop fet el procés amb l'entitat, manté l'interès i vol iniciar
el procés per ser família acollidora canviarem l'estat de l'activitat `[Xarxa
Hospitalitat] Família interessada` de `Pendent de resoldre` a `Completat`.

Altrament si la família descarta finalment passar a ser família acollidora canviarem
l'estat de l'activitat a `Cancel·lat pendent de donar alternatives` si desitgem oferir
a la família a posteriori la possibilitat de col·laborar d'alguna altra manera amb la
Xarxa d'Hospitalitat, o bé a `Cancel·lat` en cas contrari.

## Acollida en famílies

### Família d'acollida nova

1. Donar d'alta el contacte del tipus `Llar d'acollida`. Si el contacte ja
existeix com a `Llar` assignar-li el tipus de contacte `Llar d'acollida`.
2. Donar d'alta tants contactes del tipus `Voluntari` com es vulguin identificar en aquesta llar d'acollida nova. Si els contactes ja existeixen però no són del tipus `Voluntari` cal assignar-los-hi el tipus de contacte.
3. Crear una relació del tipus `és voluntari a` entre el voluntari i l'organització.
4. Crear una relació del tipus `és responsable de la llar de` o `és membre de la llar
de` segons correspongui entre la llar d'acollida i cada membre de la família amb el
qual es vulgui mantenir algun tipus d'interacció amb el CRM, p.ex. enviaments de
correus electrònics d'agraïment.

!!! question "Relacions de voluntariat"
    Potser podríem simplificar aquest procediment i estalviar-nos de crear les
    relacions de voluntariat per a cada membre de la família en tant en quant que
    tots els membres d'una família d'acollida ja són considerats de per si voluntaris.

### Persona acollida nova

1. Donar d'alta el contacte del tipus `Persona migrant` i `Usuària adulta`. Si el contacte ja existeix però no és del tipus `Persona migrant` o `Usuària adulta` cal assignar-li aquests
tipus de contacte.
2. Crear una relació del tipus `és acollida en Xarxa d'Hospitalitat a` entre la persona acollida i la llar d'acollida corresponent.

### Acompanyament nou

1. Donar d'alta el contacte de tipus `Voluntari`. Si el contacte ja existeix però
no és del tipus `Voluntari` cal assignar-li aquest tipus de contacte.
2. Crear una relació del tipus `acompanya en Xarxa d'Hospitalitat a` entre la persona
acollida i el voluntari que ofereix l'acompanyament.

!!! question "Relacions de voluntariat"
    Potser podríem simplificar aquest procediment i estalviar-nos de crear les
    relacions de voluntariat en tant en quant que les persones que fan
    l'acompanyament són considerades de per si voluntàries.

### Seguiment

1. Crear una activitat del tipus `[Xarxa Hospitalitat] Seguiment` en el contacte
a qui es fa el seguiment, especificar l'`Àmbit` si és en relació a `Acompanyament` o `Acollida` i emplenar les observacions del mateix.

## Famílies interessades que finalment no acullen

### Enviament de correu electrònic per donar alternatives a famílies interessades

Es pot enviar un correu electrònic aprofitant una plantilla predefinida a cada
responsable de la llar de les famílies interessades. Depenent de si tenim moltes
famílies per contactar ho farem mitjançant un correu electrònic individual o bé
programant un mailing.

Podem fer una cerca ràpida sobre el grup `Responsables famílies interessades en XH pendents d'alternativa` i triar l'acció que més ens convingui sobres tots els contactes
o bé sobre una selecció.

Tant si contactem per correu electrònic com si ho fem d'alguna altre manera, un cop
la família ha estat informada de les alternatives que té per col·laborar amb la
Xarxa d'Hospitalitat haurem de modificar l'estat de l'activitat `[Xarxa Hospitalitat]
Família interessada` de `Cancel·lat pendent de donar alternatives` a `Cancel·lat`.
