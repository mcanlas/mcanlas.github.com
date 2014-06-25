* not about eliminating state
  * without state, there would be no useful programs
* about moving stateful computations to predictable boundaries (like keeping db value classes stateless and moving all db operations to a single layer)
* state manipulation is moved to the stack (where no one cares about manipulation, it's automatic)
* with tail recursion, stack depth is cheap
* functional without tail recursion (perl!) is an odd fit; religious belief only w/ no practical benefit
