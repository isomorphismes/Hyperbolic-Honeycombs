# Books and long-form references

This bibliography contains links and original reading notes, not copies of copyrighted papers.

## Peter Scott — *The Geometries of 3-Manifolds* (1983)

**Unbuilt integration:** [navigable H^3 honeycomb feature, tracked in knot-complement #14](https://github.com/isomorphismes/knot-complement/issues/14), supported by [certified reflection-chamber work in coxeter #10](https://github.com/isomorphismes/coxeter/issues/10). Issues are disabled in this repository, so feature tracking lives in those repositories.

**Peter Scott**, “The Geometries of 3-Manifolds,” *Bulletin of the London Mathematical Society* **15** (1983), no. 5, 401–487. [DOI](https://doi.org/10.1112/blms/15.5.401). A foundational **survey paper**, included here as a companion to visual experiments.

- **§4:** the eight three-dimensional model geometries are `S^3`, `E^3`, `H^3`, `S^2 × R`, `H^2 × R`, `~SL_2(R)`, Nil and Sol.
- **§5:** the classification of the model geometries; §6 puts their role in geometrization into context.
- **Connection to this code:** reflection-group honeycombs in hyperbolic space are instances of the `H^3` model; they do not by themselves visualize the other seven geometries.
- **Question for future experiments:** how do geodesics, anisotropy, and observer frames differ in Nil and Sol from a ray-marched `H^3` honeycomb?

Technical counterpart: Coulon, Matsumoto, Segerman and Trettel, [*Ray-marching Thurston geometries*](https://arxiv.org/abs/2010.15801). Neither reference establishes that the current fragment shaders implement all eight geometries.
