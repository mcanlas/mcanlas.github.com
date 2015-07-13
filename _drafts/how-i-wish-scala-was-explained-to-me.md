* the difference between explicit and implicit static annotation (conflating sexy syntax with dynamism)
* scala is java under the hood
  * such that it is easy to map functional concepts to imperative building blocks
* immutability is actually about the isolation of side effects (moving them to known boundaries rather than sprinkling them), keeping a functional core
* the collections library is born out of mutability (traversable)
* don't chain collections operations eagerly
* scala's success is the choices they made for syntax
  * no blessed/collections literals
  * vals are defs
  * operators are defs
  * apply is blessed
  * right colon is blessed (dumb)
  * operator precedence?
  * point free notation
  * implicits
* an implicit is always resolved statically and can be injected manually
