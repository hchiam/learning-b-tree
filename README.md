# Learning B-tree

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Rule of thumb: [B-tree is good for big database-level data or some slow storage](https://stackoverflow.com/questions/1589556/when-to-choose-rb-tree-b-tree-or-avl-tree/1589587#1589587). In other cases, you might want to use a [splay tree](https://github.com/hchiam/learning-splay-tree) instead.

Interactive visualization: <https://www.cs.usfca.edu/~galles/visualization/BTree.html>

<https://www.reddit.com/r/explainlikeimfive/comments/wfz52/eli5_btree/> -> a B-tree is like filing cabinets with A-E, F-M, etc., except it automatically adjusts the cabinets as data is added, with multiple sub-levels.

<https://www.cs.cornell.edu/courses/cs3110/2012sp/recitations/rec25-B-trees/rec25.html> -> Few "disk reads" with high locality (search in close-together addresses) and high branching (up to `m`). Actual data is only in the leaves.

<https://triplebyte.com/blog/triplebyte-s-way-too-long-technical-interview-prep-guide> -> Apparently database indexes are usually implemented using B-trees. [Used in databases and file systems](https://en.wikipedia.org/wiki/B-tree).

Further reading:

- <https://courses.cs.washington.edu/courses/cse373/02au/lectures/lecture09l.pdf>
- <https://en.wikipedia.org/wiki/B-tree>
