# Topology - How many holes does a straw have?

- Shapes are flexible, as if made from rubber
- The Topologist is free to stretch and twist the shape
- Even cutting and gluing is allowed as long as the cut is precisely reglued
- For a topologist, a sphere and a cube are indistinguishable
- Suppose we make a polyhedron of clay and mark the edges, roll into a ball - the faces and edges become curved but their number doesnot change

![illustration](https://d2r55xnwy6nx47.cloudfront.net/uploads/2021/01/Topology_figures_1_MOBILE.svg)

- For any shape that is topologically a sphere, its Euler number is 2; for a donut-like torus, it’s 0; for a flat disk it’s 1
- Riemann observed that one way of counting holes was by seeing how many times the object could be cut without producing two pieces.
- For a surface with boundary, such as a straw with its two boundary circles, each cut must begin and end on a boundary. So, according to Riemann, because a straw can be cut only once — from end to end — it has exactly one hole.
- If the surface does not have a boundary, like a torus, the first cut must begin and end at the same point. A hollow torus can be cut twice — once around the tube and then along the resulting cylinder — so by this definition, it has two holes.
- Homology, which Poincaré introduced to generalize Riemann’s ideas to higher dimensions
-  Through homology, Poincaré aimed to capture everything from Riemann’s one-dimensional circle-like holes in a straw or binder paper, to the two-dimensional cavity-like holes inside Swiss cheese, and beyond to higher dimensions.
-  We’ll start by looking at loops on a surface. The rules are simple: The loops can slip and slide around, and can even cross themselves, but they cannot leave the surface. On some surfaces, like a circular disk or a sphere, any loop can shrink down to a single point. Such spaces have trivial homology. But other surfaces, like a straw or a torus, have loops that wrap around their holes. These have nontrivial homology.
-  Let’s call a loop that goes through the central hole and around the tube once “a.” That now serves as the basis for more loops. Since a loop can go around the tube once, twice or any number of times, and direction matters, we can represent those loops as a, 2a, –a,
-  Not every loop is a multiple of a, however, such as the loop going around the central hole along the tube’s long circumference, which we can call “b”.
-  Any loop on the torus can be deformed to follow loops a and b some integer number of times.
-  The torus has infinitely many different loops on its surface. The oriented loops a, b, and c are all different, but c can be deformed to obtain the union of loops a and b.

![figure](https://d2r55xnwy6nx47.cloudfront.net/uploads/2021/01/Topology_figures_4_MOBILE.svg)

- So on the torus, for example, the one-dimensional homology group consists of expressions such as 7a + 5b, 2a – 3b, and so on.
- For instance, we can say with mathematical certainty that a straw, a T-shirt and a pair of pants are all topologically different objects because their homology groups are different. In particular, they have a different number of holes.
- So, finally, how do topologists count holes? Using the Betti numbers. The zeroth Betti number, b0, is sort of a special case. It simply counts the number of objects. So for a single connected shape, b0 = 1. As we just saw, the first Betti number, b1, is the number of circular holes in a shape — like the circle around the cylindrical straw, the three holes in binder paper and the two circular directions of the torus. And Poincaré showed us how to compute homology, and thus the associated Betti numbers, in higher dimensions as well: The second Betti number, b2, is the number of cavities — like those inside a sphere, a torus and Swiss cheese. More generally, $b_n$ counts the number of n-dimensional holes
- Just as Euler’s number for a surface can be computed with vertices, edges and faces, it can also be computed with its Betti numbers: b0 – b1 + b2. The torus, for instance, is connected, so b0 = 1; it has b1 = 2, as we’ve seen; and, because it has one internal cavity, b2 = 1. Just as Lhuilier noted, the Euler number of the torus is 1 – 2 + 1 = 0.