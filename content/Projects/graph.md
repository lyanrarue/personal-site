---
title: Graph
draft: false
tags:
  - for-mobile
  - d3
  - computational-geometry
---

![A Graph](_assets/graph-example.png)

See the deployed site [Here](https://lyanrarue.github.io/graph)!

## Overview

I've always wanted to play around with d3.js, but never really took the time to dive in. I recently had a free evening, and figured I'd give it a shot. I decided to build a basic site in vanilla js to test out and learn some of the functionality with d3 force simulations.

Today, this little site does the following:

- Any click, not on an node, will generate an existing node and generate N edges at random
- Any click on a node will update the node's color
- Dragging the nodes will apply some minor force to the nodes with some reactive animation

I originally wanted to expand this to become a visual demonstration of DFS/BFS Graph Traversal, similar to [Quickhull Pedagogical Aide](/Projects/quickhull_pedagogical_aide.md), but I really enjoy this project as-is and may end up creating a fork to expand on for the future.
