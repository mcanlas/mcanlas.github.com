* minimax seems to be a general strategy for a certain class of games (as opposed to random move selection)
* alpha beta pruning is a way of reducing the search space (like a search heuristic) while preserving the optimality given by minimax
* the key is that really far away optimal targets are gate kept by the opposing player
  * if the opposing player was also playing optimally (by the same fitness function as the maximizing player), then the opposing player would never LET the maximizing player have access to that value
  * so for all intents and purposes, the peer options are not worth exploring
  * unless the player is a total "idiot" and plays off book (presumably in search of some greater secret deep value beyond the reach of the original maximizing player)
* possibly an even better way of looking at this is not even viewing the search space as options
 * for the minimizing player, the river will always flow one way, so assumptions can be made about what potential values remain in the space
