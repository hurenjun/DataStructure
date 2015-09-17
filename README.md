# DataStructure
Creator: Renjun Hu
Date: 2015/9/17

Description: Codes of Advanced Data Structure

Reference: online course of MIT by Professor Erik Demaine
url: https://courses.csail.mit.edu/6.851/

2015/9/17 update LinkCutTree (dynamic trees)
LinkCutTree maintains a forest of rooted trees whose each node has an arbitrary numver of unordered child nodes. The data structure has to support make_tree(), link(v, w), cut(v), find_root(v) and path_aggregate(v) in O(lg n) amortized time. Here n is the number of nodes in the forest.
For more details please refer to LinkCutTree.pdf by Prof. Eric Demaine and his T.A.s.
