# Declaració i certificació de donatius (182 i 993)

Les persones físiques amb residència fiscal a l'estat espanyol tenen dret a desgravar els donatius. Si l'entitat està adherida al cens d’entitats que promocionen l’ús de la llengua catalana, els que tinguin residència fiscal a Catalunya també poden desgravar els donatius de la part autonòmica corresponent a aquest concepte.

Cal presentar 2 models informatius: el 182 a l’agència tributària de l’estat (de l’1 al 30 de gener) i el 993 a l’agència tributària catalana (de l’1 al 20 de gener). Ambdós terminis poden variar d'un any a l'altre i per això convé confirmar-los cada any. Posteriorment, habitualment cap al març abans que comenci el període per poder presentar la declaració de la renda, cal procedir amb l’enviament dels certificats fiscals a tots aquells donants declarats al 182.

!!! Tip "Terminis de presentació"
    Tot i que el termini de presentació del model 993 acaba abans que el del model 182, és altament recomanable presentar-los els dos al mateix moment, o en el seu defecte, en el moment de presentar el 182, per així assegurar-se que tots els declarats en el 182 han estat declarats prèviament en el 993, i viceversa.

El CRM incorpora una extensió que permet, a través d'un informe, generar els fitxers necessaris per a presentar el **model 182**, com també facilitar la presentació, si cal, del **model 993** i l'obtenció de les dades necessàries per tal de generar els **certificats fiscals** de donacions.

## Previs a la presentació dels models 182 i 993

Abans de procedir amb la generació dels fitxers o dades necessàries és necessari assegurar-nos, no només que les dades estan introduïdes, sinó que ho estan de forma correcte. Per això l'extensió preveu tot un seguit de validacions que faciliten part de les comprovacions necessàries d'aquests processos.

Des de l'informe del 182 habilitat en el CRM i abans de procedir a la presentacio de qualsevol dels dos models caldrà:

1. Revisar els avisos (en groc) que es mostren en la pantalla de l'informe
2. Prémer el botó **Validate 182** i corregir els errors (en vermell) que es mostrin en la pantalla de l'informe

Més enllà d'aquestes dues principals indicacions cal tenir en compte també aquestes altres:

- Tots els contactes amb **donatius han de tenir una adreça amb com a mínim el país informat**, altrament l'informe no té manera de saber si es tracta d'un donatiu Espanyol i per tant no el té en compte.
- Les contribucions de **contactes sense NIF/NIE/CIF** registrat no s'inclouen en l'informe.
- Els donatius dels **donants dels quals no es sàpiga la província**, inferida dels 2 primers dígits del codi postal, no es poden declarar. Si no aconseguim disposar del codi postal abans de fer la presentació del model, podrem indicar en la contribució del CRM de no declarar-la.
- **Validar amb comptabilitat** els números que es mostren a l'informe 182, els totals de número de donatius i d'imports que es mostren un cop valida l'informe.
- Marcar tots els **donatius que no es volen declarar**, si és que n'hi ha.
- És especialment recomanable assegurar-se que no es tenen **contactes duplicats** entre els donants del període a presentar, per evitar incórrer en errors de càlculs de recurrència de donatius o per exemple també deixar de declarar donatius per manca de NIF o codi postal quan algun dels seus contactes duplicats té la informació. Pot ser suficient fer una cerca de contactes duplicats amb diferents regles sobre contactes amb donatius de l'any anterior.
- Assegurar-se que estan entrats els donatius dels **tres períodes impositius anteriors** al període a declarar (dos a partir dels donatius fets de l'1 de gener del 2024 en endavant). En general ho estaran si ja s'ha presentat el període anterior des del CRM.

!!! info "Validacions"
    L'informe fa les següents comprovacions i mostra els corresponents avisos en pantalla:

    - Contactes amb identificadors fiscals duplicats
    - Validesa dels camps NIF, NIE i CIF
    - Validesa del camp codi postal
    - Correspondència entre el codi postal i la provincia

## Presentació del model 182

Veure la [documentació oficial](https://sede.agenciatributaria.gob.es/Sede/ca_es/ayuda/consultas-informaticas/declaraciones-informativas-ayuda-tecnica/modelos-181-189/modelo-182-formulario.html) a la web de l'Agència Tributària 182

Passos per a presentar el model 182:

1. Quan haguem corregit tots els errors, després de prémer el botó **Validate 182** ens apareixerà el resum del resultat de la declaració i podrem procedir a prémer el botó **Export 182**.
2. Es descarregarà un fitxer. Aquest és el que hem de pujar a Hisenda.
3. Exportar, des d'accions, el fitxer CSV corresponent a l'informe com a comprovant i per poder-lo utilitzar a posteriori per a la [generació dels certificats fiscals](#gestio-de-certificats-fiscals). Aquest llistat ha d’incloure les columnes tipus de contacte, idioma i percentatge autonòmic per poder segmentar correctament l'enviament de certificats fiscals.

    !!! danger "Atenció!"
        No utilitzar l'exportació a Excel des de l'informe 182. Podria ser que no funcionés correctament. Només exportar els registres mitjançant CSV.

4. Anar a la [pàgina de presentació del Model 182](https://sede.agenciatributaria.gob.es/Sede/va_es/procedimientoini/GI02.shtml) de la web d'Hisenda
5. Seleccionar la presentació fins a 40.000 registres
6. Importar el fitxer anteriorment descarregat
7. En el cas que ens doni errors corregir-los (al CRM) i tornar a repetir els passos del 3 al 7.

     En aquest punt és comú que trobem errors de NIF/NIE que no coincideixen amb el nom informat. Per ajudar a identificar-los l’agència tributària proporciona una [eina de verificació](https://www1.agenciatributaria.gob.es/wlpl/BUGC-JDIT/Cnec) que es pot utilitzar amb l’ajuda de certificat. Un cas com a exemple, “Concepcions” que tenim identificades com a “Conxites”.

8. Un cop no tinguem errors al importar el fitxer, introduir manualment si n’hi ha, els donatius en espècie i prémer a Signar i Enviar.

!!! question "Puc rectificar una declaració del 182 ja presentada?"
    Si es vol fer qualsevol modificació s'ha de presentar de nou la declaració completa. Dit d'una altra manera, la darrera declaració presentada és la que preval.

## Presentació del model 993

Abans de procedir amb la presentació del model 993, és molt important fer els [7 primers passos](#presentacio-del-model-182) de la presentació del model 182 que ens permeten assegurar que no tenim errors en les dades a presentar. Un cop fetes les corresponents verificacions podrem procedir amb els següents passos:

1. Accedir a l'informe del 182 del CRM
2. Filtrar per les províncies `Barcelona`, `Tarragona`, `Lleida` i `Girona` i per tipus de contacte `Persona`
3. Prémer el botó **Export 993**. El botó apareix un cop premut el botó "Validate 182" sempre que estiguin definits els filtres.
4. Exportar, des d'accions, el fitxer CSV corresponent a l'informe com a comprovant.
5. Anar a la [pàgina de presentació del Model 993](https://atc.gencat.cat/es/tributs/irpf/deduccions-autonomiques-irpf) de la web de l'Agència Tributària de Catalunya.
6. Importar el fitxer anteriorment descarregat
7. Clicar el botó de Validar i revisar si hi ha errors. En cas d'haver-hi, corregir-los al CRM i tornar a començar pel punt 1
8. Un cop validat, acceptar el quadre de condicions que apareix
9. Per finalitzar guardar el justificant de la Declaració

!!! question "Puc rectificar una declaració del 993 ja presentada?"
    Es poden presentar registres “descuidats” en presentacions prèvies mentre s'estigui dintre de termini. El que no és possible és fer rectificacions sobre registres de donants ja declarats o almenys aquest és el missatge de l'aplicatiu quan en una ocasió vam intentar presentar una complementària:

    ```
    La declaración complementaria debe contener únicamente los nuevos registros no incluidos en la declaración presentada previamente, dado que los registros anteriores ya se han comunicado a la AEAT.
    ```

## Gestió de certificats fiscals

Els certificats fiscals convé enviar-los **durant la segona quinzena del mes de març** (abans que s’activi la campanya de la declaració de la Renda). No obstant això, les dades les obtindrem en el mateix moment que presentem el 182.