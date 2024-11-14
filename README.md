# Awesome E-Graphs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources related to e-graphs, equality saturation, and their applications. Contributions are welcome! Thanks to [Yihong Zhang](https://effect.systems/) for the initial list.

## Table of Contents

- [Awesome E-Graphs ](#awesome-e-graphs-)
  - [Table of Contents](#table-of-contents)
  - [Community](#community)
  - [Implementations](#implementations)
  - [General](#general)
  - [Applications](#applications)
    - [Hardware](#hardware)
    - [Program Synthesis](#program-synthesis)
    - [Program Optimization](#program-optimization)
    - [Theorem Proving and Verification](#theorem-proving-and-verification)
    - [Other](#other)
  - [Extraction](#extraction)
  - [Scheduling](#scheduling)
  - [EGRAPHS Workshop](#egraphs-workshop)
    - [EGRAPHS 2024](#egraphs-2024)
    - [EGRAPHS 2023](#egraphs-2023)
    - [EGRAPHS 2022](#egraphs-2022)
  - [Blog Posts](#blog-posts)

---

## Community

- **[egraphs.org](https://egraphs.org/)**
- **[zulip](https://egraphs.org/zulip/)**
- **[Community Meetings](https://egraphs.org/meeting/)**
- **[PLDI EGRAPHS Workshop](https://pldi24.sigplan.org/home/egraphs-2024)**

## Implementations

- **[egg](https://egraphs-good.github.io/)**
- **[egglog](https://github.com/egraphs-good/egglog)**
- **[egglog-python](https://github.com/egraphs-good/egglog-python)**
- **[snake-egg](https://github.com/egraphs-good/snake-egg)**
- **[Metatheory.jl](https://github.com/JuliaSymbolics/Metatheory.jl)** Julia Library
- **[hegg](https://hackage.haskell.org/package/hegg)** Haskell library
- **[ego](https://github.com/verse-lab/ego)** OCaml library
- **[quiche](https://github.com/riswords/quiche)**
- **[egraphs.cpp](https://github.com/can-lehmann/egraphs.cpp)**
- **[eqsat](https://github.com/taktoa/eqsat)**
- **[eggmt](https://github.com/philzook58/eggmt)**
- **[ekege](https://github.com/miestrode/ekege)**
- **[Eqlog](https://github.com/eqlog/eqlog)**
- **[GATlab](https://github.com/AlgebraicJulia/GATlab.jl)**
- **[marktoberdorf-egglog](https://github.com/ztatlock/2024-marktoberdorf-egglog)**
- **[egraph-sqlite](https://github.com/yihozhang/egraph-sqlite)**
- **[egglog-speedrun](https://github.com/Alex-Fischman/egglog-speedrun)**

## General

- [Fast Decision Procedures Based on Congruence Closure](https://dl.acm.org/doi/10.1145/322186.322198)
- [Proof-Producing Congruence Closure](https://www.cs.upc.edu/~roberto/papers/rta05.pdf)
- [Efficient E-matching for SMT Solvers](https://leodemoura.github.io/files/ematching.pdf)
- [The Chase Revisited](https://dbucsd.github.io/paperpdfs/2008_8.pdf)
- [egg](https://arxiv.org/abs/2004.03082) Fast and Extensible Equality Saturation
- [egglog](https://dl.acm.org/doi/abs/10.1145/3591239) Better Together: Unifying Datalog and Equality Saturation
- [Small Proofs from Congruence Closure](https://arxiv.org/abs/2209.03398)
- [Colored E-Graphs](https://github.com/eytans/easter-egg)
- [Slotted E-Graphs](https://michel.steuwer.info/files/publications/2024/EGRAPHS-2024.pdf)
- [E-Graphs, VSAs, and Tree Automata: a Rosetta Stone](https://remy.wang/reports/dfta.pdf)
- [An Evaluation Algorithm for Datalog with Equality](https://www.mbid.me/eqlog-algorithm/)
- [Algebraic Semantics of Datalog with Equality](https://www.mbid.me/eqlog-semantics/)

## Applications

A reverse search on the [egg paper](https://scholar.google.com/scholar?oi=bibs&hl=en&cites=4026737513542519986) on Google Scholar is a good way to stay up to date

### Hardware

- **[ROVER](https://arxiv.org/abs/2404.12336)**: Combining Power and Arithmetic Optimization via Datapath Rewriting.   *ARITH 2024*.

- **[Infinity Stream](https://dl.acm.org/doi/10.1145/3582016.3582032)**: Portable and Programmer-Friendly In-/Near-Memory Fusion.  *ASPLOS 2023*.

- **[Lakeroad](https://arxiv.org/abs/2401.16526)** FPGA Technology Mapping Using Sketch-Guided Program Synthesis [repo](https://github.com/gussmith23/lakeroad)

- **[Multiplier Optimization via E-Graph Rewriting](https://ieeexplore.ieee.org/abstract/document/10476812)**

- **[SEER](https://dl.acm.org/doi/abs/10.1145/3620665.3640392)**  Super-Optimization Explorer for High-Level Synthesis using E-graph Rewriting

- **[ESFO](https://dl.acm.org/doi/abs/10.1145/3583781.3590239)**  Equality Saturation for FIRRTL Optimization

- **[There and Back Again](https://arxiv.org/abs/2404.00786)**  A Netlist's Tale with Much Egraphin'

### Program Synthesis

- **[Ruler](https://ztatlock.net/pub-2021-oopsla-ruler.html)**: Rewrite Rule Inference Using Equality Saturation.  *OOPSLA 2021*. Distinguished paper.

- **[CCLemma](https://dl.acm.org/doi/10.1145/3674653)**: E-Graph Guided Lemma Discovery for Inductive Equational Proofs.   *ICFP 2024*.

- **[enumo](https://dl.acm.org/doi/10.1145/3622834)**: Equality Saturation Theory Exploration à la Carte.  *OOPSLA 2023*.

- **[babble](https://dl.acm.org/doi/abs/10.1145/3571207)**: Learning Better Abstractions with E-Graphs and Anti-unification.  *POPL 2023*.

- **[MegaLibm](https://dl.acm.org/doi/pdf/10.1145/3632874)**: Implementation and Synthesis of Math Library Functions.  *POPL 2024*. Distinguished paper.

- **[Isaria](https://dl.acm.org/doi/10.1145/3617232.3624873)**: Automatic Generation of Vectorizing Compilers for Customizable Digital Signal Processors.   *ASPLOS 2024*. Best paper.

### Program Optimization

- **[Herbie](https://herbie.uwplse.org/pldi15-paper.pdf)**: Automatically Improving Accuracy for Floating Point Expressions.  
  *PLDI 2015*. Distinguished paper.

- **[Felix](https://dl.acm.org/doi/10.1145/3620666.3651348)**: Optimizing Tensor Programs with Gradient Descent.   *ASPLOS 2024*.

- **[aegraphs](https://cfallin.org/pubs/egraphs2023_aegraphs_slides.pdf)**: Acyclic E-graphs
for Efficient Optimization in a Production Compiler <https://vimeo.com/843540328>

- **[Sketch-Guided Equality Saturation](https://arxiv.org/abs/2111.13040)**:  Scaling Equality Saturation to Complex Optimizations of Functional Programs

- **[peggy](https://cseweb.ucsd.edu/~rtate/publications/eqsat/)** Equality Saturation: A New Approach to Optimization

- **[optir](https://github.com/jameysharp/optir/)** RVSDG optimizing intermediate representation

- **[eggcc](https://github.com/egraphs-good/eggcc)**

- **[Denali](https://dl.acm.org/doi/abs/10.1145/1186632.1186633)**  A practical algorithm for generating optimal code

- **[Glenside](https://arxiv.org/pdf/2105.09377)** Pure Tensor Program Rewriting via Access Patterns

- **[Simplifying MBA Expression Using E-Graphs](https://arxiv.org/abs/2404.05431)**

- **[SPORES](https://dl.acm.org/doi/10.14778/3407790.3407799)** sum-product optimization via relational equality saturation for large scale linear algebra

- **[∇SD](https://ieeexplore.ieee.org/document/10444787)**: A Tensor Algebra Compiler for Sparse Differentiation. *CGO 2024*.

- **[TenSat](https://proceedings.mlsys.org/paper_files/paper/2021/file/cc427d934a7f6c0663e5923f49eba531-Paper.pdf)**: Equality Saturation for Tensor Graph Superoptimization.   *MLSys 2021*.

- **[PolyJuice](http://www.wingtecher.com/themes/WingTecherResearch/assets/papers/paper_from_24/polyjuice_oopsla24.pdf)**: Detecting Mis-compilation Bugs in Tensor Compilers with Equality Saturation Based Rewriting.  *OOPSLA 2024*.

- **[RisingLight](https://rustmagazine.org/issue-2/write-a-sql-optimizer-using-egg/)**: Write a SQL Optimizer using Egg.  *EGRAPHS 2023*.

- **[Hydro](https://arxiv.org/abs/2306.10585)**: Optimizing Stateful Dataflow with Local Rewrites. *EGRAPHS 2023*.

- **[SpEQ](https://dl.acm.org/doi/10.1145/3656445)**: Translation of Sparse Codes using Equivalences

- **[ACC Saturator](https://arxiv.org/abs/2306.13002)** : Automatic Kernel Optimization for Directive-Based GPU Code

- **[High-performance symbolic-numerics via multiple dispatch](https://arxiv.org/abs/2105.03949)**

- **[Q-gym](https://people.csail.mit.edu/baghdadi/public/papers/qgym.pdf)**: An Equality Saturation Framework for DNN Inference Exploiting Weight Repetition

- **[Diospyros](https://dl.acm.org/doi/10.1145/3445814.3446707)**: Vectorization for Digital Signal Processors via Equality Saturation.   *ASPLOS 2021*.

- **[Chassis](https://arxiv.org/abs/2410.14025)** : Target-Aware Implementation of Real Expressions

- [Optimizing Tensor Computation Graphs with Equality Saturation and Monte Carlo Tree Search](https://dl.acm.org/doi/10.1145/3656019.3689611)

### Theorem Proving and Verification

- Most SMT solvers have an e-matching egraph implementation in them
- **[lean-egg](https://cfaed.tu-dresden.de/files/Images/people/chair-cc/theses/2407_Rossel_MA.pdf)**: An Equality Saturation Tactic for Lean. *Thesis 2023*. ([repo](https://github.com/marcusrossel/lean-egg))
- **[KestRel](https://arxiv.org/abs/2404.08106)**: Relational Verification Using E-Graphs for Program Alignment.  *EGRAPHS 2023*.
- **[cyclegg](https://github.com/nadia-polikarpova/cyclegg)**
- **[coq congruence](https://coq.inria.fr/doc/v8.12/refman/proof-engine/tactics.html#coq:tacn.congruence)**
- **[Fast Approximations of Quantifier Elimination](https://link.springer.com/chapter/10.1007/978-3-031-37703-7_4)**
- **[Congruence Closure in Intensional Type Theory](https://link.springer.com/chapter/10.1007/978-3-319-40229-1_8)**
- **[Congruence Closure in Cubical Type Theory](https://cs.au.dk/~spitters/Emil.pdf)**
- **[ZOMBIE](https://www.seas.upenn.edu/~sweirich/papers/congruence-extended.pdf)**: Programming up to Congruence
- **[GATlab](https://arxiv.org/pdf/2404.04837)**: Modeling and Programming with Generalized Algebraic Theories
- **[Transforming Optimization Problems into Disciplined Convex Programming Form](https://goens.org/publications/fernandez-mir-cicm-24/cicm24.pdf)**
- **[Coquetier](https://dspace.mit.edu/bitstream/handle/1721.1/150194/Bourgeat-bthom-PhD-EECS-2022-thesis.pdf)** a simplification tactic for our Coq toolbox

### Other

- **[YOGO](https://www.jameskoppel.com/files/papers/yogo-preprint.pdf)**  Semantic Code Search via Equational Reasoning

- **[VyZX](https://arxiv.org/abs/2311.11571)**: Formal Verification of a Graphical Quantum Language with automated structural rewrites.  
  *Thesis 2023*.

- **[Szalinski](https://dl.acm.org/doi/10.1145/3385412.3386012)**: Synthesizing Structured CAD Models with Equality Saturation and Inverse Transformations.  
  *PLDI 2020*.

- **[Maletskyi and Shymanskyi](https://ceur-ws.org/Vol-3609/paper21.pdf)**: Genome Compression Using Program Synthesis.  
  *IDDM 2023*.

- **[Cornelius](https://github.com/bkushigian/cornelius)**: Equivalent and redundant mutant detection with e-graphs!!!

- **[MetaEmu](https://dl.acm.org/doi/10.1145/3548606.3559338)**: An Architecture Agnostic Rehosting Framework for Automotive Firmware.  
  *CCS 2022*.

- **[wasm-evasion](https://www.sciencedirect.com/science/article/pii/S0167404823002067)**: WebAssembly diversification for malware evasion.  
  *COSE 2023*.

- **[Guided Equality Saturation](https://dl.acm.org/doi/10.1145/3632900)**: Improve performance/capabilities by using guides in a semi-automatic equality saturation process. *POPL 2024*.

- [Novel Algorithms for Computing Correlation Functions of Nuclei](https://arxiv.org/pdf/2201.04269)

## Extraction

- [extraction-gym](https://github.com/egraphs-good/extraction-gym)
- [E-Graphs as Circuits, and Optimal Extraction via Treewidth](https://arxiv.org/pdf/2408.17042)
- [Notes on the scheduling and extraction problems of EqSat](https://effect.systems/blog/eqsat-schedule-extract-notes.html)
- [Answer Set Programming for E-Graph DAG extraction](https://www.philipzucker.com/asp-for-egraph-extraction/)
- [Fast and Optimal Extraction for Sparse Equality Graphs](https://dl.acm.org/doi/10.1145/3689801)


## Scheduling

- **[Learned Graph Rewriting with Equality Saturation: A New Paradigm in Relational Query Rewrite and Beyond](https://arxiv.org/abs/2407.12794)**


## Talks

- [egg: Fast and Extensible Equality Saturation](https://www.youtube.com/watch?v=6cJMI9z2TeU&ab_channel=ACMSIGPLAN)
- [Better Together: Unifying Datalog and Equality Saturation (PLDI 2023)](https://www.youtube.com/watch?v=VZytqLrQvdY&ab_channel=YihongZhang)
- [egglog Tutorial (EGRAPHS 2023) | Next Generation Egraphs](https://www.youtube.com/watch?v=N2RDQGRBrSY&t=3s&ab_channel=oflatteducation)
- [egglog: E-Graphs in Python](https://www.youtube.com/watch?v=Pbi2uV9vWPg&t=2962s&ab_channel=OpenTeams)
- [ægraphs: Acyclic E-graphs for Efficient Optimization in a Production Compiler](https://vimeo.com/843540328)
- [E-Graphs and Automated Reasoning: Looking Back to Look Forward](https://www.youtube.com/watch?v=74VP0SbNHDE&t=149s&ab_channel=PhilipZucker)

## EGRAPHS Workshop

### EGRAPHS 2024

[Accepted Papers](https://pldi24.sigplan.org/home/egraphs-2024#event-overview)

[youtube](https://www.youtube.com/playlist?list=PLyrlk8Xaylp4UHRXP0VkuYen9nkn4bczW)

### EGRAPHS 2023

[Presentations](https://pldi23.sigplan.org/home/egraphs-2023#event-overview)

### EGRAPHS 2022

[Accepted papers](https://pldi22.sigplan.org/home/egraphs-2022#event-overview)

[youtube](https://www.youtube.com/watch?v=dbgZJyw3hnk&t=2725s&ab_channel=ACMSIGPLAN)
## Blog Posts

- [The e-graph data structure: A gradual introduction](https://www.cole-k.com/2023/07/24/e-graphs-primer/)
- [The Theoretical Aspect of Equality Saturation](https://uwplse.org/2023/11/14/Eqsat-theory-i.html)
- [Acyclic Egraphs and Smart Constructors](https://www.philipzucker.com/smart_constructor_aegraph/)
- [Gauss and Groebner Egraphs: Intrinsic Linear and Polynomial Equations](https://www.philipzucker.com/linear_grobner_egraph/)
- [What's in an e-graph?](https://bernsteinbear.com/blog/whats-in-an-egraph/)
- [Improving MBA Deobfuscation using Equality Saturation](https://secret.club/2022/08/08/eqsat-oracle-synthesis.html)
- [Automating Transport with Univalent E-Graphs](https://taliasplse.wordpress.com/2020/02/02/automating-transport-with-univalent-e-graphs/)
- [Co-Egraphs: Streams, Unification, PEGs, Rational Lambdas](https://www.philipzucker.com/coegraph/)
- [Binding in E-graphs](https://pavpanchekha.com/blog/egg-bindings.html)
