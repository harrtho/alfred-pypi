# Alfred-PyPI

An Alfred workflow for looking up Python package versions on PyPI.

![PyPI Alfred Search](img/pypi-alfred-search.png)

![PyPI Alfred Result](img/pypi-alfred-result.png)

## Installation

To install, download and run the [`PyPI-*.alfredworkflow`][releases] file in GitHub.

## Development

PyPI-Alfred works with Python 3.7+ only! Since macOS 12.3 (Monterey) python is no longer part of OS,
therefore python 3 needs to be installed to used this workflow.

This workflow reads data from the PyPI project JSON API. [Click here][example] for an example of what that API returns.

## Contributors

Origin Grant McConnaughey [grantmcconnaughey][grantmcconnaughey]

## License

This workflow is released under the [MIT License][mit-license].

Alfred PyPI uses the following libraries:

- [Alfred-PyWorkflow][alfred-pyworkflow] ([MIT License][mit-license])

[alfred-pyworkflow]: https://github.com/harrtho/alfred-pyworkflow
[example]: http://pypi.python.org/pypi/requests/json
[grantmcconnaughey]: https://github.com/grantmcconnaughey
[mit-license]: https://opensource.org/licenses/MIT
[releases]: https://github.com/harrtho/alfred-pypi/releases
