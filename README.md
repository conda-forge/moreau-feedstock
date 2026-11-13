About moreau-feedstock
======================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/moreau-feedstock/blob/main/LICENSE.txt)


About moreau
------------

Home: https://moreau.so/

Package license: Apache-2.0

Summary: Metapackage selecting the CPU build of moreau

Development: https://github.com/moreau-project/moreau

Documentation: https://moreau.so/

Moreau solves quadratic cone programs with a Rust CPU backend and a
C++/CUDA GPU backend behind one Python API, with support for batching
and differentiation through the solution.

About moreau-runtime
--------------------

Home: https://moreau.so/

Package license: Apache-2.0 AND BSD-3-Clause AND MIT

Summary: Compiled CPU and optional CUDA backends for moreau

Development: https://github.com/moreau-project/moreau

Documentation: https://moreau.so/

Moreau solves quadratic cone programs with a Rust CPU backend and a
C++/CUDA GPU backend behind one Python API, with support for batching
and differentiation through the solution.

About moreau
------------

Home: https://moreau.so/

Package license: Apache-2.0

Summary: Moreau: conic optimization solver with CPU and optional GPU backends

Development: https://github.com/moreau-project/moreau

Documentation: https://moreau.so/

Moreau solves quadratic cone programs with a Rust CPU backend and a
C++/CUDA GPU backend behind one Python API, with support for batching
and differentiation through the solution.

About moreau-gpu
----------------

Home: https://moreau.so/

Package license: Apache-2.0

Summary: Metapackage selecting the CUDA build of moreau

Development: https://github.com/moreau-project/moreau

Documentation: https://moreau.so/

Moreau solves quadratic cone programs with a Rust CPU backend and a
C++/CUDA GPU backend behind one Python API, with support for batching
and differentiation through the solution.

About moreau-split
------------------

Home: https://moreau.so

Package license: Apache-2.0

Summary: GPU-native, batched, differentiable conic optimization

Development: https://github.com/moreau-project/moreau

Documentation: https://moreau.so

Moreau solves quadratic cone programs with a Rust CPU backend and a
C++/CUDA GPU backend behind one Python API, with support for batching
and differentiation through the solution.


Current build status
====================


<table><tr>
    <td>GitHub Actions</td>
    <td>
      <a href="https://github.com/conda-forge/moreau-feedstock/actions/workflows/conda-build.yml">
        <img src="https://github.com/conda-forge/moreau-feedstock/actions/workflows/conda-build.yml/badge.svg?event=push&branch=main">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=30089&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/moreau-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=30089&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/moreau-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-moreau-green.svg)](https://anaconda.org/conda-forge/moreau) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/moreau.svg)](https://anaconda.org/conda-forge/moreau) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/moreau.svg)](https://anaconda.org/conda-forge/moreau) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/moreau.svg)](https://anaconda.org/conda-forge/moreau) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-moreau--cpu-green.svg)](https://anaconda.org/conda-forge/moreau-cpu) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/moreau-cpu.svg)](https://anaconda.org/conda-forge/moreau-cpu) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/moreau-cpu.svg)](https://anaconda.org/conda-forge/moreau-cpu) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/moreau-cpu.svg)](https://anaconda.org/conda-forge/moreau-cpu) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-moreau--gpu-green.svg)](https://anaconda.org/conda-forge/moreau-gpu) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/moreau-gpu.svg)](https://anaconda.org/conda-forge/moreau-gpu) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/moreau-gpu.svg)](https://anaconda.org/conda-forge/moreau-gpu) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/moreau-gpu.svg)](https://anaconda.org/conda-forge/moreau-gpu) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-moreau--runtime-green.svg)](https://anaconda.org/conda-forge/moreau-runtime) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/moreau-runtime.svg)](https://anaconda.org/conda-forge/moreau-runtime) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/moreau-runtime.svg)](https://anaconda.org/conda-forge/moreau-runtime) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/moreau-runtime.svg)](https://anaconda.org/conda-forge/moreau-runtime) |

Installing moreau
=================

Installing `moreau` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

How to use
----------

<details>
<summary>With conda</summary>

```
conda install moreau moreau-cpu moreau-gpu moreau-runtime
```

</details>

<details>
<summary>With mamba</summary>

```
mamba install moreau moreau-cpu moreau-gpu moreau-runtime
```

</details>

<details>
<summary>With pixi</summary>

```
# for adding to your local project
pixi add moreau moreau-cpu moreau-gpu moreau-runtime
# for installing globally
pixi global install moreau moreau-cpu moreau-gpu moreau-runtime
```

</details>

Search package versions
-----------------------

It is possible to list all of the versions of `moreau` available on your platform:

<details>
<summary>With conda</summary>

```
conda search moreau --channel conda-forge
```

</details>

<details>
<summary>With mamba</summary>

```
mamba search moreau --channel conda-forge
```

</details>

<details>
<summary>With pixi</summary>

```
pixi search moreau --channel conda-forge
```

</details>

<details>
<summary>With mamba repoquery, which may provide more information</summary>

```
# Search all versions available on your platform:
mamba repoquery search moreau --channel conda-forge

# List packages depending on `moreau`:
mamba repoquery whoneeds moreau --channel conda-forge

# List dependencies of `moreau`:
mamba repoquery depends moreau --channel conda-forge
```

</details>



About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/) and [GitHub](https://github.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance,
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information, please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating moreau-feedstock
=========================

If you would like to improve the moreau recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/moreau-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@timkpaine](https://github.com/timkpaine/)

