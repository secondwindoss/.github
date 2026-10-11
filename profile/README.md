<p align="center">
  <img src="https://github.com/secondwindoss.png" width="96" alt="Second Wind OSS">
</p>

<h1 align="center">Second Wind OSS</h1>

<p align="center">Community-maintained forks of open-source libraries whose upstream went quiet.<br>Same API, same license, the fixes that never shipped.</p>

## What we do

Good libraries outlive their maintainers' time. When a widely used project stops releasing, its users are left with open security advisories, dependency pins that no longer resolve, and pull requests that were never merged. We fork such projects, publish them under a new distribution name, and keep them moving.

## How we work

- **Same API, same import.** Code written against the original keeps working. The distribution name changes, the import name does not.
- **Same license, full credit.** Every fork keeps the original license, copyright and author credit. Imported commits keep their authors.
- **Compatible with existing data.** Files, databases and formats written by the original remain readable, and the reverse, until a major version says otherwise.
- **Fixes with a changelog.** Security fixes first, then the pull requests upstream never merged, each recorded in a changelog and a GitHub Release.

## Projects

| Project | What it is | Forked from | Install |
|---|---|---|---|
| [diskcache-community](https://github.com/secondwindoss/diskcache-community) | Disk and file backed persistent cache for Python, built on SQLite, with a Django backend | python-diskcache | `pip install diskcache-community` |
| [streaming-community](https://github.com/secondwindoss/streaming-community) | Fast, accurate streaming of training data from cloud storage for PyTorch | MosaicML Streaming | `pip install streaming-community` |
| [sqlx](https://github.com/secondwindoss/sqlx) | General purpose extensions to Go's `database/sql` | jmoiron/sqlx | `go get github.com/secondwindoss/sqlx` |

<p>
  <a href="https://github.com/secondwindoss/diskcache-community/actions/workflows/ci.yml"><img alt="diskcache-community CI" src="https://github.com/secondwindoss/diskcache-community/actions/workflows/ci.yml/badge.svg"></a>
  <a href="https://pypi.org/project/diskcache-community/"><img alt="diskcache-community on PyPI" src="https://img.shields.io/pypi/v/diskcache-community?label=diskcache-community"></a>
  <a href="https://pypi.org/project/streaming-community/"><img alt="streaming-community on PyPI" src="https://img.shields.io/pypi/v/streaming-community?label=streaming-community"></a>
  <a href="https://pkg.go.dev/github.com/secondwindoss/sqlx"><img alt="sqlx on pkg.go.dev" src="https://pkg.go.dev/badge/github.com/secondwindoss/sqlx.svg"></a>
</p>

Each repository's README explains why that fork exists, what changed, and how to switch from the original.

## Get involved

- **Report a bug or ask a question** in the issue tracker of the project concerned.
- **Report a vulnerability** privately through the Security tab of that repository. See [SECURITY.md](https://github.com/secondwindoss/.github/blob/main/SECURITY.md).
- **Send a pull request.** Small, tested changes with a changelog entry are easiest to merge. See [CONTRIBUTING.md](https://github.com/secondwindoss/.github/blob/main/CONTRIBUTING.md) and the project's own guide.
- **Suggest a project** that needs a second wind by opening an issue in this repository.
