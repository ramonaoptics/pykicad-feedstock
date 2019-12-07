About pykicad
=============

Home: https://github.com/dvc94ch/pykicad

Package license: ISC

Feedstock license: BSD 3-Clause

Summary: Routines for generating and parsing KiCAD files



Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=8&branchName=master">
        <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/pykicad-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pykicad-green.svg)](https://anaconda.org/ramonaoptics/pykicad) | [![Conda Downloads](https://img.shields.io/conda/dn/ramonaoptics/pykicad.svg)](https://anaconda.org/ramonaoptics/pykicad) | [![Conda Version](https://img.shields.io/conda/vn/ramonaoptics/pykicad.svg)](https://anaconda.org/ramonaoptics/pykicad) | [![Conda Platforms](https://img.shields.io/conda/pn/ramonaoptics/pykicad.svg)](https://anaconda.org/ramonaoptics/pykicad) |

Installing pykicad
==================

Installing `pykicad` from the `ramonaoptics` channel can be achieved by adding `ramonaoptics` to your channels with:

```
conda config --add channels ramonaoptics
```

Once the `ramonaoptics` channel has been enabled, `pykicad` can be installed with:

```
conda install pykicad
```

It is possible to list all of the versions of `pykicad` available on your platform with:

```
conda search pykicad --channel ramonaoptics
```




Updating pykicad-feedstock
==========================

If you would like to improve the pykicad recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ramonaoptics` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ramonaoptics` channel.
Note that all branches in the ramonaoptics/pykicad-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@hmaarrfk](https://github.com/hmaarrfk/)

