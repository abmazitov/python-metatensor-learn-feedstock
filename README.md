About python-metatensor-learn-feedstock
=======================================

Feedstock license: [BSD-3-Clause](https://github.com/abmazitov/python-metatensor-learn-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/metatensor/metatensor

Package license: BSD-3-Clause

Summary: Building blocks for the atomistic machine learning models based on PyTorch and NumPy

Documentation: https://docs.metatensor.org

Current build status
====================


<table><tr>
    <td>All platforms:</td>
    <td>
      <img src="https://img.shields.io/badge/noarch-disabled-lightgrey.svg" alt="noarch disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-python--metatensor--learn-green.svg)](https://anaconda.org/metatensor/python-metatensor-learn) | [![Conda Downloads](https://img.shields.io/conda/dn/metatensor/python-metatensor-learn.svg)](https://anaconda.org/metatensor/python-metatensor-learn) | [![Conda Version](https://img.shields.io/conda/vn/metatensor/python-metatensor-learn.svg)](https://anaconda.org/metatensor/python-metatensor-learn) | [![Conda Platforms](https://img.shields.io/conda/pn/metatensor/python-metatensor-learn.svg)](https://anaconda.org/metatensor/python-metatensor-learn) |

Installing python-metatensor-learn
==================================

Installing `python-metatensor-learn` from the `metatensor` channel can be achieved by adding `metatensor` to your channels with:

```
conda config --add channels metatensor
conda config --set channel_priority strict
```

Once the `metatensor` channel has been enabled, `python-metatensor-learn` can be installed with `conda`:

```
conda install python-metatensor-learn
```

or with `mamba`:

```
mamba install python-metatensor-learn
```

It is possible to list all of the versions of `python-metatensor-learn` available on your platform with `conda`:

```
conda search python-metatensor-learn --channel metatensor
```

or with `mamba`:

```
mamba search python-metatensor-learn --channel metatensor
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search python-metatensor-learn --channel metatensor

# List packages depending on `python-metatensor-learn`:
mamba repoquery whoneeds python-metatensor-learn --channel metatensor

# List dependencies of `python-metatensor-learn`:
mamba repoquery depends python-metatensor-learn --channel metatensor
```




Updating python-metatensor-learn-feedstock
==========================================

If you would like to improve the python-metatensor-learn recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`metatensor` channel, whereupon the built conda packages will be available for
everybody to install and use from the `metatensor` channel.
Note that all branches in the abmazitov/python-metatensor-learn-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@Luthaf](https://github.com/Luthaf/)
* [@PicoCentauri](https://github.com/PicoCentauri/)

