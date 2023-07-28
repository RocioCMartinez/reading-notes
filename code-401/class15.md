# Trees

## Resources

<https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html>

## WHAT, WHY, HOW

**What**: Trees!
There are three main types: Binary Trees, Binary Search Trees, and K-ary Trees

**Why**: Trees are an important data structure that can organize data in a very concise way.

There are important topics to note here:

They are composed of nodes which of course hold a value and a reference to the next node.

They have a root (starting point like head, top, or front in other similar structures). *Root is also often the way to refer to the current value when traversing.

'K' is the number of children a node can have.

Left, Right are positions in relation to the 'root'.

Edge is how the link is described between nodes.

Height is determined by number of edges.

Leaf is a node within the structure that does not have children.

**How**: Can be traversed in 2 manners, *Depth First* or *Breath First*.

Key notes for depth first traversal

> Focus is depth(height) and use of call stack

- Pre-order: `root >> left >> right`
- In-order: `left >> root >> right`
- Post-order: `left >> right >> root`

Key note for breath first traversal

>Traditionally, breadth first traversal uses a queue (instead of the call stack via recursion) to traverse the width/breadth of the tree.

There are a lot of images and pseduo code related to this topic so use the reference!
