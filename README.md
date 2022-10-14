# A repository of packages for OCaml with modular macros

A repository of [OPAM][opam] packages for [Modular Macros][modular-macros].

![GitHub Actions status](https://github.com/modular-macros/modular-macros-opam/workflows/Macros/badge.svg)

### Setting up

```
opam switch create macros --repos default,macros=git+https://github.com/modular-macros/modular-macros-opam.git ocaml-variants.4.04.0+macros
```

[modular-macros]: https://www.cl.cam.ac.uk/~jdy22/projects/modular-macros/
[opam]: https://opam.ocaml.org/

### Current packages:

* [staged-streams](https://github.com/modular-macros/staged-streams.ocaml-macros),
  for stream computations with fusion
