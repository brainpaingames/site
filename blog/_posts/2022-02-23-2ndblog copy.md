---
title: "Creating simple 4d objects in hypershack"
date: 2019-01-21
category: Tutorials
---

In this post we see how to create some simple objects into the 4 dimensional world of hypershack.

3 dimensional Tetrahedron
-------------------------

We start by creating a 3 dimensional tetrahedron. when moving around in hypershack, the slice of 3d tetrahedron we actually can see is a plane of a shape of a triangle or a convex quadrilateral. 

```json
[
    {
        "objecttype":"fivecell",
        "gameobjectname":"Fivecell",
        "colr":[1.0,0.0,0.0,0.0],
        "points4d":[  
            [0.0,0.0,5.0,2.0],
            [0.0,2.0,5.0,2.0],
            [2.0,0.0,5.0,2.0],
            [0.0,0.0,7.0,2.0],
            [0.0,0.0,5.0,-1.0]
        ]
    }
]

```
