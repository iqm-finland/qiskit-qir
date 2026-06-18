# Changelog

## Version 0.9.1
- Add Python 3.14 support
- Update package metadata

## Version 0.9.0
- Update package to support `qiskit~=2.0`.
- Remove support for conditionally controlled gates as they are not part of the [QIR Base profile](https://github.com/qir-alliance/qir-spec/blob/main/specification/profiles/Base_Profile.md).
- Drop Python 3.8 and 3.9 support
- Add Python 3.13 support

## Version 0.8.0
- Fixing documentation workflow in `publish.yml`

## Version 0.7.0

- Including `sphinx` as a requirement in `setup.cfg` to build docs.
- Updating the version requirement for `iqm-pyqir`

# Version 0.6.0

- First version forked from the `qiskit-qir` repository. Includes support for the RGate that is part of IQM's native gateset.
- Add CI workflow for publishing package on PyPI
- Add CI workflow for publishing documentation on GitHub Pages
