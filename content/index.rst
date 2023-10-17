Introduction to GPU Programming
===============================

Graphical processing units (GPUs) are the workhorse of many high performance
computing (HPC) systems around the world. The number of GPU-enabled supercomputers
on the `Top500 <https://www.top500.org/>`__ has been steadily increasing in recent years
and this development is expected to continue. In the near future, the majority of HPC
computing power available to researchers and engineers is likely to be provided by GPUs
or other types of accelerators. Programming GPUs and other accelerators is thus crucial
to developers of software run on HPC systems.

However, the landscape of GPU hardware, software and programming environments is complicated.
Multiple vendors compete in the high-end GPU market, with each vendor providing its own software
stack and development toolkits, and even beyond that, there is a proliferation of tools,
languages and frameworks that can be used to write code for GPUs.
It can thus be difficult for individual developers and project owners to know how to
navigate across this landscape and select the most appropriate GPU programming framework for their
projects based on the requirements of a given project and technical requirements of any existing code.

This material covers the basic introduction to GPU programming including:

- `Why GPUs? <https://enccs.github.io/intro-gpu-programming/1-gpu-history/>`__
- `The GPU hardware and software ecosystem <https://enccs.github.io/intro-gpu-programming/2-gpu-ecosystem/>`__
- `What problems fit to GPU? <https://enccs.github.io/intro-gpu-programming/3-gpu-problems/>`__
- `GPU programming concepts <https://enccs.github.io/intro-gpu-programming/4-gpu-concepts/>`__

Within this lesson, you will:

- Understand why and when to use GPUs;
- Become comfortable with key concepts in GPU programming.

After this lesson, you can continue on concrete topics for GPU programming at intermediate and advanced levels.

- `GPU Programming: When, Why and How? <https://enccs.github.io/gpu-programming/>`__
- `CUDA training materials <https://enccs.github.io/cuda/>`__
- `OpenMP for GPU offloading <https://enccs.github.io/openmp-gpu/>`__
- `OpenACC for GPU programming (beginner level) <https://enccs.github.io/openacc/>`__
- `OpenACC for GPU programming (intermediate level) <https://enccs.github.io/OpenACC-CUDA-intermediate/>`__
- `Heterogeneous programming with SYCL <https://enccs.github.io/sycl-workshop/>`__

These materials are developed to help both software developers and decision makers navigate the
GPU programming landscape and make more informed decisions on which languages or frameworks
to learn and use for their projects. From these lessons, you could acquire a comprehensive overview of
different software frameworks, and also learn the fundamentals in at least one of the frameworks
mentioned above to a level which will enable you to quickly become a productive GPU programmer.

.. prereq::

   Familiarity with one or more programming languages like C/C++, Fortran, Python or
   Julia is recommended.

.. toctree::
   :maxdepth: 1
   :caption: Prerequisites

   0-setup

.. toctree::
   :maxdepth: 1
   :caption: The lesson

   1-gpu-history
   2-gpu-ecosystem
   3-gpu-problems
   4-gpu-concepts

.. toctree::
   :maxdepth: 1
   :caption: Instructor’s guide

   guide

.. toctree::
   :maxdepth: 1
   :caption: About

   All lessons <https://enccs.se/lessons/>
   ENCCS <https://enccs.se/>


Who is the course for?
----------------------

This material is most relevant to researchers and engineers who already develop software
which runs on CPUs in workstations or supercomputers, but also to decision makers or
project managers who don't write code but make strategic decisions in software projects,
whether it's in academia, industry or the public sector.


About the course
----------------

This training material is the result of a multilateral effort by GPU programming experts from:

- `Aalto University in Finland <https://www.aalto.fi/en>`_
- `Aarhus University in Denmark <https://www.au.dk/>`__
- `CSC in Finland <https://csc.fi/>`__
- `ENCCS in Sweden <https://enccs.se/>`__
- `HPC2N centre in Umeå, Sweden <https://www.hpc2n.umu.se/>`__
- `KTH Royal Institute for Technology in Sweden <https://www.kth.se/>`__
- `NRIS in Norway <https://www.sigma2.no/nris>`__
- `Vilnius University in Lithuania <https://www.vu.lt/en/>`__ and `NCC Lithuania <https://www.eurocc-lithuania.lt/>`__


Credits
-------

Several sections in this lesson have been adapted from the following sources created by
`ENCCS <https://enccs.se/>`__ and `CSC <https://csc.fi/>`__, which are
all distributed under a
`Creative Commons Attribution license (CC-BY-4.0) <https://creativecommons.org/licenses/by/4.0/>`__:

- `High Performance Data Analytics in Python <https://enccs.github.io/hpda-python/>`__
- `Julia for High-Performance Scientific Computing <https://enccs.github.io/julia-for-hpc/>`__
- `Julia for High-Performance Data Analytics <https://enccs.github.io/julia-for-hpda/>`__

The lesson file structure and browsing layout is inspired by and derived from
`work <https://github.com/coderefinery/sphinx-lesson>`__ by `CodeRefinery
<https://coderefinery.org/>`__ licensed under the `MIT license
<http://opensource.org/licenses/mit-license.html>`__. We have copied and adapted
most of their license text.


Instructional Material
^^^^^^^^^^^^^^^^^^^^^^

This instructional material is made available under the
`Creative Commons Attribution license (CC-BY-4.0) <https://creativecommons.org/licenses/by/4.0/>`__.
The following is a human-readable summary of (and not a substitute for) the
`full legal text of the CC-BY-4.0 license <https://creativecommons.org/licenses/by/4.0/legalcode>`__.
You are free to:

- **share** - copy and redistribute the material in any medium or format
- **adapt** - remix, transform, and build upon the material for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow these license terms:

- **Attribution** - You must give appropriate credit (mentioning that your work
  is derived from work that is Copyright (c) ENCCS and individual contributors and, where practical, linking
  to `<https://enccs.github.io/sphinx-lesson-template>`_), provide a `link to the license
  <https://creativecommons.org/licenses/by/4.0/>`__, and indicate if changes were
  made. You may do so in any reasonable manner, but not in any way that suggests
  the licensor endorses you or your use.
- **No additional restrictions** - You may not apply legal terms or
  technological measures that legally restrict others from doing anything the license permits.

With the understanding that:

- You do not have to comply with the license for elements of the material in
  the public domain or where your use is permitted by an applicable exception or limitation.
- No warranties are given. The license may not give you all of the permissions
  necessary for your intended use. For example, other rights such as
  publicity, privacy, or moral rights may limit how you use the material.


Software
^^^^^^^^

Except where otherwise noted, the example programs and other software provided
with this repository are made available under the `OSI <http://opensource.org/>`__-approved
`MIT license <https://opensource.org/licenses/mit-license.html>`__.
