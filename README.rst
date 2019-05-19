Same Game
=========

A grid strategy game for one player.

Rules
-----

- grid is filled with colored circles
- when cells are connected TRBL, they're part of a "cluster"
- clicking on a cluster removes that cluster & cells fall down to fill
- when a col is emptied, cols move over to fill
- score: for each cluster: ncells-in-cluster ^ 2
- end game: score + 100/cell removed under 50
- game ends when no more clusters are present [no more moves]
