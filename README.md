# A repository of packages for OCaml with modular macros

A repository of [OPAM][opam] packages for [Modular Macros][modular-macros]
(MacoCaml).

![GitHub Actions status](https://github.com/modular-macros/modular-macros-opam/workflows/Build/badge.svg)

### Setting up

Installing the MacoCaml prototype compiler:
```
opam switch create macocaml \
  --packages=ocaml-variants.5.5.0+macocaml-prototype-2026-08-06 \
  --repos=default,macocaml=git+https://github.com/modular-macros/modular-macros-opam.git
```

The compiler is built from the
[macocaml-prototype-2026-08-06](https://github.com/modular-macros/ocaml-macros/tree/macocaml-prototype-2026-08-06)
branch of the
[modular-macros/ocaml-macros](https://github.com/modular-macros/ocaml-macros)
repository.

[modular-macros]: https://www.cl.cam.ac.uk/~jdy22/projects/modular-macros/
[opam]: https://opam.ocaml.org/
