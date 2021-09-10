
# Contributing

This repository describes best-practices that should be followed when
contributing to repositories owned by PRIO.

## Branching

The main branching strategy followed is the 
[Atlassian Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow).
In PRIO repositories, all new features _should_ be written in separate branches
named "feature/{feature-name}" where feature-name is the (descriptive) name of
your new feature.

## Versioning

The versioning strategy followed by all versioned PRIO software and
applications is [semver](https://semver.org/). Version numbers should be in the
format `MAJOR.MINOR.PATCH`, and should be incremented following these ground
rules:

1. MAJOR version when you make incompatible API changes,
2. MINOR version when you add functionality in a backwards compatible manner, and
3. PATCH version when you make backwards compatible bug fixes.
