# Banc d'aliments - Definició

## Tipus de contactes

El mòdul Banc d'Aliments implica als següents 3 tipus de contacte:

- **Organització:** com a receptora de derivacions del banc d'aliments.
- **Usuària Adulta:** com a beneficiari de la derivació del banc d'aliments.
- **Professional** com a treballador social de referència responsable de la derivació al banc d'aliments.

## Relacions

Les derivacions del banc d'aliments queden definides pel següent tipus de relació que permet establir la vinculació entre l'adult beneficiari i l'organització que gestiona la derivació.

### Relació de derivació d'aliments
- Contacte A: Usuària Adulta
- Contacte B: Organització
- Relació A>B: té una derivació d'aliments a
- Relació B>A: rep una derivació d'aliments de
- Conjunt de camps personalizats: [Derivació banc d'aliments](#derivacio-banc-daliments)

### Relació de derivació de targeta moneder
- Contacte A: Usuària Adulta
- Contacte B: Organització
- Relació A>B: té una derivació de targeta moneder a
- Relació B>A: rep una derivació de targeta moneder de
- Conjunt de camps personalizats: [Derivació banc d'aliments](#derivacio-banc-daliments)

### Conjunts de camps personalitzats

#### Derivació banc d'aliments

| Camp                         | Descripció                                   | Tipus de camp  |
|:-----------------------------|:---------------------------------------------|:---------------|
| Adults                       | Nombre d'adults a la llar                    | Numèric         |
| Menors de 17 a 3 anys        | Nombre de menors a la llar majors de 3 anys  | Numèric         |
| Menors de 3 anys             | Nombre de menors de 3 anys de la llar        | Numèric         |
| Nombre de persones a la llar | Correspon a la suma d'adults, menors de 17 a 3 anys i menors de 3 anys de la llar  | Numèric         |
| Treballador social           | Treballadora que fa la derivació             | Contacte de referència<br>*(de tipus Professional)*         |
| Recollides previstes         | Nombre de recollides previstes durant la derivació  | Numèric         |

## Activitats

### :shopping_cart: [Adult] Recollida d'aliments

S'efectua la recollida d'aliments on el contacte de l'activitat correspon al titular de la corresponent derivació del Banc d'Aliments.

Conjunt de camps personalitzats: [Recollida d'aliments/targeta](#recollida-dalimentstargeta)

### :credit_card: [Adult] Recollida targeta moneder

S'efectua la recollida de la targeta moneder on el contacte de l'activitat correspon al titular de la corresponent derivació del Banc d'Aliments.

Conjunt de camps personalitzats: [Recollida d'aliments/targeta](#recollida-dalimentstargeta)

### Conjunt de camps personalitzats

#### Recollida d'aliments/targeta

| Camp              | Descripció                | Tipus de camp          |
|:------------------|:--------------------------|:-----------------------|
| Centre que deriva | Organització responsable de la derivació del Banc d'Aliments.  | Contacte de referència<br>*(de tipus Organització)* |
