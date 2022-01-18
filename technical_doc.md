# advertools Technical Documentation

**Last updated:** 2022-01-18\
_Document generation aided by **Documatic**_

<ENTER SHORT PROJECT DESCRIPTION>

* [Introduction](#introduction)
* [Code Overview](#code-overview)

## Introduction

This is a technical document detailing
        at a high-level
        what advertools does, how it operates,
        and how it is built.

The outline of this document was generated
        by **Documatic**.
<!---Documatic-section-group: arch-start--->


## Project Architecture


<!---Documatic-section-group: arch-end--->

<!---Documatic-section-group: helloworld-start--->


## Code Overview

The codebase has a 2-deep folder structure, with 43 in total.
<!---Documatic-section-helloworld: setup-start--->
The codebase is compatible with Python 3.6 and above, because of f-string 3.6 in /home/eli/Documents/programming/Forks/advertools/advertools/stopwords.py.

Run `pip install -e .` in top-level directory to install
package in local directory.




<!---Documatic-section-helloworld: setup-end--->
`advertools.tests.test_kw_generate`` has a `__main__` entrypoint.


<!---Documatic-section-helloworld: entrypoints-start--->


## Entrypoints

There are 0 source code entrypoints in top-level `__main__`/`__init__` files.


<!---Documatic-section-helloworld: entrypoints-end--->

<!---Documatic-section-group: concept-start--->
## Concepts
<!---Documatic-section-group: concept-end--->

<!---Documatic-section-group: helloworld-end--->

<!---Documatic-section-group: dev-start--->


## Developers
<!---Documatic-section-dev: setup-start--->
* Tests are present in `tests/` (using pytest, unittest)




<!---Documatic-section-dev: setup-end--->

<!---Documatic-section-dev: ci-start--->
The project uses Travis for CI/CD.


