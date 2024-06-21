# Pull Request Check List

This checklist serves as a guide for contributors and maintainers to assess
whether a contribution can be merged into the main branch and thus serves
to guarantee the quality of the package. Please read the
[contribution guideline](https://github.com/tempoCollaboration/OQuPy/blob/main/CONTRIBUTING.md).

Before you submit a pull request, please go through this checklist once
more, as it will decrease the number of unnecessary review cycles.
However, this list is there to *help* all contributors to produce high
quality code, not to deter you from contributing. If you can't tick some of the
boxes, feel free to submit the pull request anyway and report about it in the
pull request message. Also, some of the boxes might not apply to the specific
type of your contribution.

* [ ] The contribution has been discussed and agreed on in the [Issue section](https://github.com/tempoCollaboration/OQuPy/issues).
* [ ] Code contributions do its best to follow [the zen of python](https://www.python.org/dev/peps/pep-0020/).
* [ ] The automated test are all positive:
  - [ ] `tox -e py36` (to run `pytest`) the code tests.
  - [ ] `tox -e style` (to run `pylint`) the [code style](https://www.python.org/dev/peps/pep-0008/) tests.
* [ ] Added test for changed/added code.
* [ ] The documentation has been updated:
  - [ ] docstring for all new functions/methods/classes/modules.
  - [ ] consistent style of all docstrings.
  - [ ] for new modules: `/docs/pages/modules.rst` has been updated.
  - [ ] for new functionality: `/docs/pages/api.rst` has been updated.
  - [ ] for new functionality: tutorials and examples have been updated.
