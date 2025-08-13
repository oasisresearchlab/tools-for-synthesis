---
Type: Technical Primitive
---

Depth of focus is a setting found in some [[Graph view]] implementations that controls how many “hops” away from the currently focused node are shown. It’s essentially a distance filter: when the depth is set to _X_, the system will display only the nodes that are at most _X_ edges (links) away from the focused node.

For example, with a depth of focus of 1, you’d see only the directly connected nodes. At 2, you’d see those nodes plus all of _their_ immediate connections, and so on. This lets users control the complexity of the visualization, either by narrowing the focus to reduce visual noise or widening it to explore larger structural patterns.

Most tools that offer this feature let you adjust it dynamically—often via a slider—so you can quickly expand or contract the visible neighborhood of the focused node while exploring the graph.

Tools that support the Depth of Focus:
- [[Roam Research]] and [[Obsidian]]'s graph views
- [[Cosma]]