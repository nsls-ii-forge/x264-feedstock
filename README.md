About x264
==========

Home: http://www.videolan.org/developers/x264.html

Package license: GPL-2.0

Feedstock license: BSD 3-Clause

Summary: A free software library for encoding video streams into the H.264/MPEG-4 AVC format.



Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=88&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/x264-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_target_platformlinux-64</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=88&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/x264-feedstock?branchName=master&jobName=linux&configuration=linux_target_platformlinux-64" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_target_platformosx-64</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=88&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/x264-feedstock?branchName=master&jobName=osx&configuration=osx_target_platformosx-64" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>
      <img src="https://img.shields.io/badge/Windows-disabled-lightgrey.svg" alt="Windows disabled">
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-x264-green.svg)](https://anaconda.org/nsls2forge/x264) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/x264.svg)](https://anaconda.org/nsls2forge/x264) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/x264.svg)](https://anaconda.org/nsls2forge/x264) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/x264.svg)](https://anaconda.org/nsls2forge/x264) |

Installing x264
===============

Installing `x264` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `x264` can be installed with:

```
conda install x264
```

It is possible to list all of the versions of `x264` available on your platform with:

```
conda search x264 --channel nsls2forge
```




Updating x264-feedstock
=======================

If you would like to improve the x264 recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/x264-feedstock are
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


