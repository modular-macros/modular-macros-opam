# A repository of packages for OCaml with modular macros

A repository of [OPAM][opam] packages for [Modular Macros][modular-macros].

![GitHub Actions status](https://github.com/modular-macros/modular-macros-opam/workflows/Macros/badge.svg)

### Setting up

Installing the 4.04.0 variant:
```
opam switch create macros --repos default,macros=git+https://github.com/modular-macros/modular-macros-opam.git ocaml-variants.4.04.0+macros
```

Installing the 5.3.0 variant:
```
opam switch create macocaml --packages=ocaml-variants.5.3.0+macocaml-branch --repos=default,macocaml=git+https://github.com/modular-macros/modular-macros-opam.git
```

[modular-macros]: https://www.cl.cam.ac.uk/~jdy22/projects/modular-macros/
[opam]: https://opam.ocaml.org/

### Current packages:

* [staged-streams](https://github.com/modular-macros/staged-streams.ocaml-macros),
  for stream computations with fusion
