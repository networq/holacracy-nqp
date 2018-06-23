networq:holacracy
====

This is the "networq:holacracy" package for [NetworQ](https://github.com/networq).

## Types

This package defines the following types that you can use in your own Networq:

### networq:holacracy:role type

Fields:

  * `circle`: *networq:holacracy:circle*
  * `role-assignments`: *networq:holacracy:role-assignment[]*

### networq:holacracy:circle type

Fields:

  * `purpose`: *string*
  * `circle`: *networq:holacracy:circle*
  * `circles`: *networq:holacracy:circle[]*
  * `roles`: *networq:holacracy:role[]*
  * `strategies`: *networq:holacracy:strategy[]*

### networq:holacracy:role-assignment type

Fields:

  * `role`: *networq:holacracy:role*
  * `partner`: *networq:holacracy:partner*
  * `focus`: *string*

### networq:holacracy:partner type

Fields:

  * `role-assignments`: *networq:holacracy:role-assignment[]*

### networq:holacracy:strategy type

Fields:

  * `circle`: *networq:holacracy:circle*


