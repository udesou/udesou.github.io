---
layout: default
title: Projects
tags: projects
permalink: /projects/
js:
- js/gh_projects.js
- js/util_buttons.js
---



{:refdef: style="text-align: center; display:block; margin-left: auto; margin-right: auto;"}
![MMTk]({{ site.baseimg }}../images/logos/mmtk-black-rust-trans.png){:width="20%"} ![Julia]({{ site.baseimg }}../images/logos/julia-logo-color.png){:width="15%"}
{: refdef}

[MMTk-Julia](https://www.mmtk.io) - I have contributed to developing small parts of mmtk-core, a memory management framework with a multi-runtime language-agnostic platform for implementing garbage collection. In particular I also worked on [`mmtk-julia`](https://github.com/mmtk/mmtk-julia), which is a binding for the Julia programming language, enabling further research into Julia's requirements for a performant garbage collector.

{:refdef: style="text-align: center;"}
![Mu]({{ site.baseimg }}../images/logos/microvm-logo.jpg)
{: refdef}

[The Mu MicroVM](http://microvm.github.io) - I have worked on the Mu MicroVM project by adding support for a LLVM backend, i.e., translating Mu code into LLVM IR ([`mu-aot-llvm`](https://gitlab.anu.edu.au/mu/mu-aot-llvm)). I've also added initial support for using MMTk as a GC framework for Mu (for the code, see the [`Mu`](https://gitlab.anu.edu.au/mu/mu-impl-fast/-/tree/rust-2018/)'s latest implementation). 

{:refdef: style="text-align: center;"}
![Spoofax]({{ site.baseimg }}../images/logos/spoofax3_64.png)
{: refdef}

[The Spoofax Language Workbench](https://spoofax.dev) - Inside Spoofax I worked developing a parse table generator written in Java to fully support declarative disambiguation of operator precedence using contextual grammars, and layout sensitive parsing. I also worked developing and improving SDF3, the latest version of the syntax definition formalism SDF, which can be used to declaratively specify the syntax of programming languages.

