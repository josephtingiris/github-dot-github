<!-- Markdown link definitions -->
[init-base]: https://github.com/josephtingiris/github-dot-github
[init-conduct]: github-dot-github.CODE_OF_CONDUCT.md
[init-contributing]: github-dot-github.CONTRIBUTING.md
[init-installation]: #Installation
[init-issue]: https://github.com/josephtingiris/github-dot-github/issues/new
[init-license]: github-dot-github.LICENSE.md
[init-support]: #Support
[init-usage]: #Usage
[init-wiki]: https://github.com/josephtingiris/github-dot-github/wiki

# Description

This is an initial structure for a composite project that contains code from multiple other open source projects with varying README, LICENSE, CONTRIBUTING, and CODE_OF_CONDUCT files.

## Table of Contents

* [Installation][init-installation]
* [Usage][init-usage]
* [Support][init-support]
* [License][init-license]
* [Code of Conduct][init-conduct]
* [Contributing][init-contributing]

## Installation

Download to the project directory, add, and commit.  i.e.:

```sh
export Project_Name=my-project
mkdir $Project_Name && cd $Project_Name
curl -LOk https://github.com/josephtingiris/github-dot-github/archive/master.zip && unzip -j master.zip github-dot-github-master/.github/* -d .github/ && rm -f master.zip
# (optionally) get github-dot-github from https://github.com/josephtingiris/github-bin
github-dot-github $Project_Name
```

## Usage

1. Create the following files for the project:

* *project*.README.md
* *project*.TYPE.LICENSE.md
* *project*.CODE_OF_CONDUCT.md
* *project*.CONTRIBUTING.md

2. Update the *project* files with links and/or content about the *project*. e.g.:

* Name
* Description
* Installation instructions
* Usage instructions
* Support instructions
* Contributing instructions

3. Update the following files with links and/or content to the *project* files.

* README.md
* LICENSE.md
* CODE_OF_CONDUCT.md
* CONTRIBUTING.md

## Support

Please see the [Wiki][init-wiki] or [open an issue][init-issue] for support.
