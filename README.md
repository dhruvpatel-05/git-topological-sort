# git-topological-sort
CS35L Project

The topo_order_commits.py script constructs a directed acyclic graph (DAG) of commits by parsing Git objects and branch references without using Git commands. It uses depth-first search (DFS) to traverse the commit history and generate a topological ordering that maintains ancestor-descendant relationships. The output includes commit hashes along with "sticky starts" and "sticky ends" to clearly indicate branch merges and splits in the history.
