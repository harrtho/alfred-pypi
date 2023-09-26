# PyPI Alfred Workflow

[![GitHub Version][shield-version]][gh-releases]
[![GitHub All Releases][shield-downloads]][gh-releases]
[![GitHub][shield-license]][license-mit]

Look up for Python packages on [PyPI][pypi] in [Alfred][alfred].

![][preview]

## Download & Installation

Download the [latest workflow release][gh-latest-release] from GitHub. Open the workflow file to
install in Alfred.

## Usage

- `pypi [<query>]` — Show a list of releases of the Python package.
  - `↩` — Open the PyPI package release in your browser

This workflow reads data from the PyPI project JSON API. [Click here][example] for an example of
what that API returns.

## Bug Reports and Feature Requests

Please use [GitHub issues][gh-issues] to report bugs or request features.

## Contributors

This Alfred Workflow comes from the [abandoned Workflow][abandoned-workflow] of
[Grant McConnaughey][grantmcconnaughey]

## License

PyPI Alfred Workflow is licensed under the [MIT License][license-mit]

The workflow uses the following libraries:

- [Alfred-PyWorkflow][alfred-pyworkflow] ([MIT License][license-mit])

[abandoned-workflow]: https://github.com/grantmcconnaughey/pypi-alfred
[alfred-pyworkflow]: https://github.com/harrtho/alfred-pyworkflow
[alfred]: https://www.alfredapp.com
[example]: https://pypi.org/pypi/alfred-pyworkflow/json
[gh-issues]: https://github.com/harrtho/alfred-pypi/issues
[gh-latest-release]: https://github.com/harrtho/alfred-pypi/releases/latest
[gh-releases]: https://github.com/harrtho/alfred-pypi/releases
[grantmcconnaughey]: https://github.com/grantmcconnaughey
[license-mit]: https://opensource.org/licenses/MIT
[preview]: img/preview.png
[pypi]:https://pypi.org
[shield-downloads]: https://img.shields.io/github/downloads/harrtho/alfred-pypi/total.svg
[shield-license]: https://img.shields.io/github/license/harrtho/alfred-pypi.svg
[shield-version]: https://img.shields.io/github/release/harrtho/alfred-pypi.svg
