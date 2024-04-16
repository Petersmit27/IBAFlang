# IBAFlang (Imperative But Also Functional language)
This repo contains the language definition for IBAF, a language defined in the CBS meta-language. CBS's component-based approach allowed me to define this language with relative ease and generate an editor for syntax highlighting. I highly recommend checkout out the project [at this URL](https://plancomps.github.io/CBS-beta/).

As you may realise from reading the language definition, the language for now is more I than F. That's why this is just version 0.1 of IBAF. If you're interested in seeing how a more complex language can be defined, I recommend taking a look at the language definitions for [MiniJava](https://plancomps.github.io/CBS-beta/math/Languages-beta/MiniJava/) or [OCaml-Light](https://plancomps.github.io/CBS-beta/math/Languages-beta/OCaml-Light/).

## Project structure

In the repo there are three projects that can be opened in [Spoofax](https://spoofax.dev/)
- `IBAF-cbs` is the project that contains the source `.cbs` files that defines the language.
- `IBAF-Editor` is the Spoofax project that can be used to build the IDE for IBAF.
- `IBAF-Tests` is a project containing some example programs and the funcon terms they compile to.

To actually compile the language yourself you will need to set up the CBS workbench locally. You can find out more on [the CBS-IDE page](https://plancomps.github.io/cbs-ide/docs/)

## Some relevant papers:
- CBS introduction: [Software meta-language engineering and CBS](https://doi.org/10.1016/j.jvlc.2018.11.003)
- In-depth look at funcons: [Fundamental Constructs in Programming Languages](https://doi.org/10.1007/978-3-030-89159-6_19)
- In-depth look at the CBS workbench/editor: [A Component-Based Formal Language Workbench](https://doi.org/10.4204/eptcs.310.4)
