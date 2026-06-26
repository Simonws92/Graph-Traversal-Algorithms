An algorithms which traverses a hierarchical-based graph.

E.G: Node G -> node C -> Node (C,D) -> Node A -> node B -> (Node E,F).

If the traversal start at node A, a backtracking will occur to compute Node G->C -> C->A and D->A before computing A->B and B->E & B->F.
