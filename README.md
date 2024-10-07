# Awesome E-Graphs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources related to e-graphs, equality saturation, and their applications. Contributions are welcome! Thanks to [Yihong Zhang](https://effect.systems/) for initial list.

## Table of Contents

- [Awesome E-Graphs ](#awesome-e-graphs-)
  - [Table of Contents](#table-of-contents)
  - [Community](#community)
  - [Projects](#projects)
  - [Papers](#papers)
  - [Applications](#applications)
    - [Hardware](#hardware)
    - [Program Synthesis](#program-synthesis)
    - [Program Optimization](#program-optimization)
    - [ML Systems](#ml-systems)
    - [Security](#security)
    - [Databases](#databases)
    - [Verification](#verification)
    - [Theorem Proving](#theorem-proving)
    - [Differentiable Programming](#differentiable-programming)
    - [Quantum Computation](#quantum-computation)
    - [Fabrication](#fabrication)
    - [Genomics](#genomics)
    - [Software Engineering](#software-engineering)
    - [Library Learning](#library-learning)
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
- [PLDI EGRAPHS Workshop](https://pldi24.sigplan.org/home/egraphs-2024)

## Projects

- **[egg](https://egraphs-good.github.io/)**
- **[egglog](https://github.com/egraphs-good/egglog)**
- **[egglog-python](https://github.com/egraphs-good/egglog-python)**
- **[snake-egg](https://github.com/egraphs-good/snake-egg)**
- **[Metatheory.jl](https://github.com/JuliaSymbolics/Metatheory.jl)** Julia Library
- **[hegg](https://hackage.haskell.org/package/hegg)** Haskell library
- **[ego](https://github.com/verse-lab/ego)** OCaml library
- **[quiche](https://github.com/riswords/quiche)**
- **[egraphs.cpp](https://github.com/can-lehmann/egraphs.cpp)
- **[eqsat](https://github.com/taktoa/eqsat)**

## Papers

- [Fast Decision Procedures Based on Congruence Closure](https://dl.acm.org/doi/10.1145/322186.322198)
- [egg](https://arxiv.org/abs/2004.03082) Fast and Extensible Equality Saturation
- [egglog](https://dl.acm.org/doi/abs/10.1145/3591239) Better Together: Unifying Datalog and Equality Saturation
- [Colored Egraphs](https://github.com/eytans/easter-egg)

## Applications

A reverse search on the [egg paper](https://scholar.google.com/scholar?oi=bibs&hl=en&cites=4026737513542519986) on Google Scholar is a good way to stay up to date

### Hardware

- **[Isaria](https://dl.acm.org/doi/10.1145/3617232.3624873)**: Automatic Generation of Vectorizing Compilers for Customizable Digital Signal Processors.  
  *ASPLOS 2024*. Best paper.

- **[ROVER](https://arxiv.org/abs/2404.12336)**: Combining Power and Arithmetic Optimization via Datapath Rewriting.  
  *ARITH 2024*.

- **[Diospyros](https://dl.acm.org/doi/10.1145/3445814.3446707)**: Vectorization for Digital Signal Processors via Equality Saturation.  
  *ASPLOS 2021*.

- **[Infinity Stream](https://dl.acm.org/doi/10.1145/3582016.3582032)**: Portable and Programmer-Friendly In-/Near-Memory Fusion.  
  *ASPLOS 2023*.

- [Lakeroad](https://github.com/gussmith23/lakeroad)
...

### Program Synthesis

- **[Ruler](https://ztatlock.net/pub-2021-oopsla-ruler.html)**: Rewrite Rule Inference Using Equality Saturation.  
  *OOPSLA 2021*. Distinguished paper.

- **[CCLemma](https://dl.acm.org/doi/10.1145/3674653)**: E-Graph Guided Lemma Discovery for Inductive Equational Proofs.  
  *ICFP 2024*.

- **[enumo](https://dl.acm.org/doi/10.1145/3622834)**: Equality Saturation Theory Exploration à la Carte.  
  *OOPSLA 2023*.

...

### Program Optimization

- **[Herbie](https://herbie.uwplse.org/pldi15-paper.pdf)**: Automatically Improving Accuracy for Floating Point Expressions.  
  *PLDI 2015*. Distinguished paper.

- **[MegaLibm](https://dl.acm.org/doi/pdf/10.1145/3632874)**: Implementation and Synthesis of Math Library Functions.  
  *POPL 2024*. Distinguished paper.

- **[Felix](https://dl.acm.org/doi/10.1145/3620666.3651348)**: Optimizing Tensor Programs with Gradient Descent.  
  *ASPLOS 2024*.

- [aegraphs](https://cfallin.org/pubs/egraphs2023_aegraphs_slides.pdf) ægraphs: Acyclic E-graphs
for Efficient Optimization in a Production Compiler <https://vimeo.com/843540328>

- [peggy](https://cseweb.ucsd.edu/~rtate/publications/eqsat/) Equality Saturation: A New Approach to Optimization

- RVSDG

- [Denali](https://dl.acm.org/doi/abs/10.1145/1186632.1186633)  A practical algorithm for generating optimal code

- Glenside

- [Simplifying MBA Expression Using E-Graphs](https://arxiv.org/abs/2404.05431)
...

### ML Systems

- **[TenSat](https://proceedings.mlsys.org/paper_files/paper/2021/file/cc427d934a7f6c0663e5923f49eba531-Paper.pdf)**: Equality Saturation for Tensor Graph Superoptimization.  
  *MLSys 2021*.

- **[PolyJuice](http://www.wingtecher.com/themes/WingTecherResearch/assets/papers/paper_from_24/polyjuice_oopsla24.pdf)**: Detecting Mis-compilation Bugs in Tensor Compilers with Equality Saturation Based Rewriting.  
  *OOPSLA 2024*.

...

### Security

- **[MetaEmu](https://dl.acm.org/doi/10.1145/3548606.3559338)**: An Architecture Agnostic Rehosting Framework for Automotive Firmware.  
  *CCS 2022*.

- **[wasm-evasion](https://www.sciencedirect.com/science/article/pii/S0167404823002067)**: WebAssembly diversification for malware evasion.  
  *COSE 2023*.

...

### Databases

- **[RisingLight](https://rustmagazine.org/issue-2/write-a-sql-optimizer-using-egg/)**: Write a SQL Optimizer using Egg.  
  *EGRAPHS 2023*.

- **[Hydro](https://arxiv.org/abs/2306.10585)**: Optimizing Stateful Dataflow with Local Rewrites.  
  *EGRAPHS 2023*.

...

### Verification

- **[KestRel](https://arxiv.org/abs/2404.08106)**: Relational Verification Using E-Graphs for Program Alignment.  
  *EGRAPHS 2023*.

### Theorem Proving

- **[lean-egg](https://cfaed.tu-dresden.de/files/Images/people/chair-cc/theses/2407_Rossel_MA.pdf)**: An Equality Saturation Tactic for Lean.  
  *Thesis 2023*.
- [cyclegg](https://github.com/nadia-polikarpova/cyclegg)
- [coq congruence](https://coq.inria.fr/doc/v8.12/refman/proof-engine/tactics.html#coq:tacn.congruence)

...

### Differentiable Programming

- **[∇SD](https://ieeexplore.ieee.org/document/10444787)**: A Tensor Algebra Compiler for Sparse Differentiation.  
  *CGO 2024*.

...

### Quantum Computation

- **[VyZX](https://arxiv.org/abs/2311.11571)**: Formal Verification of a Graphical Quantum Language with automated structural rewrites.  
  *Thesis 2023*.

...

### Fabrication

- **[Szalinski](https://dl.acm.org/doi/10.1145/3385412.3386012)**: Synthesizing Structured CAD Models with Equality Saturation and Inverse Transformations.  
  *PLDI 2020*.

...

### Genomics

- **[Maletskyi and Shymanskyi](https://ceur-ws.org/Vol-3609/paper21.pdf)**: Genome Compression Using Program Synthesis.  
  *IDDM 2023*.

...

### Software Engineering

- **[Cornelius](https://github.com/bkushigian/cornelius)**: Equivalent and redundant mutant detection with e-graphs!!!

...

### Library Learning

- **[babble](https://dl.acm.org/doi/abs/10.1145/3571207)**: Learning Better Abstractions with E-Graphs and Anti-unification.  
  *POPL 2023*.

## EGRAPHS Workshop

### EGRAPHS 2024

### EGRAPHS 2023

### EGRAPHS 2022

## Blog Posts

- [The e-graph data structure: A gradual introduction](https://www.cole-k.com/2023/07/24/e-graphs-primer/)
- [The Theoretical Aspect of Equality Saturation](https://uwplse.org/2023/11/14/Eqsat-theory-i.html)
- [Acyclic Egraphs and Smart Constructors](https://www.philipzucker.com/smart_constructor_aegraph/)
- [Gauss and Groebner Egraphs: Intrinsic Linear and Polynomial Equations](https://www.philipzucker.com/linear_grobner_egraph/)
- [What's in an e-graph?](https://bernsteinbear.com/blog/whats-in-an-egraph/)
- [Improving MBA Deobfuscation using Equality Saturation](https://secret.club/2022/08/08/eqsat-oracle-synthesis.html)
