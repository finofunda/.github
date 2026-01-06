<div align = "center">

# Contributing to `FinoFunda INC`
[![FinoFunda INC](https://img.shields.io/badge/🌐-finofunda-blue)](https://github.com/finofunda)
[![Primary Language](https://img.shields.io/badge/🔣-English_Language-858794)]()

</div>

<div align = "justify">

First and foremost, 🙏 thank you for considering to contribute to **[`finofunda`](https://github.com/finofunda)**. We are currently setting up the organization,
stay tuned for more information! Actively looking for contributors!

## Issues

If you spot a problem with any of the funtionalities/documentations then first
[search if an issue already exists](https://docs.github.com/en/github/searching-for-information-on-github/searching-on-github/searching-issues-and-pull-requests#search-by-the-title-body-or-comments).
If a related issue doesn't exist, you can open a new issue using a relevant [issue form](https://github.com/github/docs/issues/new/choose).

### Issue Types

An issue type is available to categorize issues across the organization for better control and management. The types are `P0`, `P1`, ..., `P6` which are the priority of the
issue in question, where `P0` has the highest priority (that needs to be adressed immediately) and `P6` has the lowest/unresolved priority. For more information about issue types
check [documentation](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/managing-issue-types-in-an-organization).

By default, when an issue is created it is assigned a `P6` priority and is reviewed and updated by the admin to respective one. If you feel that the priority needs to be changed,
comment so that it can be re-evaluated by the administrator.

## Pull Request Process

The product/project (repository) for the organization may have additional contributing guidelines. Please refer to respective repository readme file or contact administrator
and/or group administrator for more informations. The general process are as below:

1. Ensure any install or build dependencies are removed before the end of the layer when doing a  build.
2. Update the README.md with details of changes to the interface, this includes new environment  variables,
  exposed ports, useful file locations and container parameters.
3. Increase the version numbers in any examples files and the README.md to the new version that this
  Pull Request would represent. The versioning scheme we use either [SemVer](http://semver.org/) or [PEP 440](https://peps.python.org/pep-0440/).
4. You may merge the Pull Request in once you have the sign-off of two other developers, or if you 
  do not have permission to do that, you may request the second reviewer to merge it for you.

### Version Styling Guide

All the project versioning follows [`SemVer`](http://semver.org/) unless it is an explicit Python project which follows [`PEP 440`](https://peps.python.org/pep-0440/) styling guide.
All the notable changes for a repository also follows any one of the styling guide, check changelog header for convention for each repository.

<details>
<summary>Click to open <code>PEP 440</code> Styilng Guide</summary>

Packaging for `PyPI` follows the standard PEP0440 styling guide and is implemented by the **`packaging.version.Version`** class. The other
popular versioning scheme is [`semver`](https://semver.org/), but each build has different parts/mapping.
The following table gives a mapping between these two versioning schemes:

<div align = "center">

| `PyPI` Version | `semver` Version |
| :---: | :---: |
| `epoch` | n/a |
| `major` | `major` |
| `minor` | `minor` |
| `micro` | `patch` |
| `pre` | `prerelease` |
| `dev` | `build` |
| `post` | n/a |

</div>

One can use the **`packaging`** version to convert between PyPI to semver and vice-versa. For more information, check
this [link](https://python-semver.readthedocs.io/en/latest/advanced/convert-pypi-to-semver.html).

</details>

## Activity & Development

It is expected that an issue/PR needs a definite amount of time to resolve. To ensure, we follow the `stale` and `mothballed` convention when it is not resolved within a specified period.
For issues, the default is 85 days, and for PR it is 30 days of inactivity after which an issue/PR is marked as
[`stale`]([./workflows/stale.yml](https://github.com/digitphilia/.github/blob/master/.github/workflows/stale.yml)). The label allows administrators to review and take necessary actions.

</div>
