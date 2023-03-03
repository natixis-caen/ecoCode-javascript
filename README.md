![Logo](https://github.com/green-code-initiative/ecoCode/blob/main/docs/resources/logo-large.png?raw=true)
======================================

Websites are becoming increasingly heavy and complex over the years. They represent an important part
of the digital environmental footprint. The objective of this project is to detect smells in a website source code
that can have a negative ecological impact: overconsumption of energy, "fatware", shortening of the life span of
devices, etc. This project is part of [ecoCode](https://github.com/green-code-initiative/ecoCode).

Rules in this repository are mainly based from book
[115 Web Ecodesign Best Practices](https://github.com/cnumr/best-practices).
This reference is maintained by [CNumR](https://collectif.greenit.fr/), a french collective that works
for a responsible design of digital services. You can find all applicable rules in
the [main ecoCode repository](https://github.com/green-code-initiative/ecoCode/tree/main/docs/rules).

> ⚠️ These plugins are in a very early stage and need improvements. Any contribution will be appreciated.

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

📣 Why linters?
----------------

This repository contains multiple linters that each support a different set of programming languages. They are separated
from each other and are designed primarily to analyze static code that the SonarQube scanner cannot process. They can
however be used, modified and published independently of our ecoCode plugins.

The purpose of these linters is twofold: to allow code smells to be found as soon as it is written using standard
techonologies, and also to trace these reports back into SonarQube. This way we can make up for a SonarQube lack by
improving feedback to developers. It's a good deal! And the use is not more complex.

🌿 Use with our SonarQube plugin
--------------------------------

Not available right now. Coming soon!

🔧 Use as standalone linters
----------------------------

If you don't want to integrate rules into SonarQube, you are free to do so.\
Plugins are working nicely on their own! Follow instructions in the dedicated README files.

- [JavaScript/TypeScript linter using ESLint](https://github.com/green-code-initiative/ecoCode-linter/blob/main/eslint-plugin/README.md)
- More to come..

🛒 Distribution
---------------

Plugins are available as dedicated NPM packages.\
You can follow changelogs on [GitHub Releases page](https://github.com/green-code-initiative/ecoCode-linter/releases).

🤝 Contribution
---------------

You have an idea or you want to help us improving these linters? \
We are open to your suggestions and contributions! Open an issue or PR 🚀

Check out the [CONTRIBUTING.md](https://github.com/green-code-initiative/ecoCode-linter/blob/main/CONTRIBUTING.md) file
and follow the various guides to start contributing.
