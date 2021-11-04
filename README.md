# A set of Common Service Quality Assurance Baseline Criteria for Research Projects

[![HTML Manuscript](https://img.shields.io/badge/manuscript-HTML-blue.svg)](https://EOSC-synergy.github.io/service-qa-baseline/)
[![PDF Manuscript](https://img.shields.io/badge/manuscript-PDF-blue.svg)](https://EOSC-synergy.github.io/service-qa-baseline/manuscript.pdf)
[![GitHub Actions Status](https://github.com/EOSC-synergy/service-qa-baseline/workflows/Manubot/badge.svg)](https://github.com/EOSC-synergy/service-qa-baseline/actions)

## Motivation

Service development, provisioning, operation and integration into large
scale production infrastructures often suffers from a lack of
quality assurance realization. This might result from the fact that the
different actors involved are either not aware of the benefits that applying
quality practices bring along, or not keen to adhere to them as they might
increase the burden of service deployment, operation and management.
Thus, the main purpose of this
document is to _provide a lightweight and practical approach_ to educate and,
ultimately, achieve quality of those services, such as their stability or
functional suitability..

The Common Service Quality Assurance Baseline Criteria
_establishes the minimum viable set of quality requirements_ provides an initial
approach to Service Quality Assurance, meant to be applied in the integration
process of the services existing under the EOSC-Synergy project, which eventually
will be accessible as part of the EOSC offerings. In
order to discern among them, the [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt)
convention is used throughout the document, thus adding adequate information
about the criticality of each requirement.

_A citable version of this manuscript is available at https://digital.csic.es/handle/10261/214441_

## Open Collaboration

The current baseline has been elaborated based on the first-hand
experiences extracted from several European-funded research projects for
service provisioning, operation and integration into large scale production
infrastructures. We aim to consolidate the quality guidelines as a
reference point for current and future research infrastructures, setting a
path for sustainability and knowledge transfer. This goal can only be achieved
through a open and collaborative effort. Consequently, __any contribution
is welcomed and will be considered for inclusion.__

Please check our [contribution](CONTRIBUTING.md) guide.

## Copyright Notice

<<<<<<< HEAD
Copyright © Members of the EOSC-Synergy collaborations, 2019-2020.
=======
### Repository directories & files

The directories are as follows:

+ [`content`](content) contains the manuscript source, which includes markdown files as well as inputs for citations and references.
  See [`USAGE.md`](USAGE.md) for more information.
+ [`output`](output) contains the outputs (generated files) from Manubot including the resulting manuscripts.
  You should not edit these files manually, because they will get overwritten.
+ [`webpage`](webpage) is a directory meant to be rendered as a static webpage for viewing the HTML manuscript.
+ [`build`](build) contains commands and tools for building the manuscript.
+ [`ci`](ci) contains files necessary for deployment via continuous integration.

### Local execution

The easiest way to run Manubot is to use [continuous integration](#continuous-integration) to rebuild the manuscript when the content changes.
If you want to build a Manubot manuscript locally, install the [conda](https://conda.io) environment as described in [`build`](build).
Then, you can build the manuscript on POSIX systems by running the following commands from this root directory.

```sh
# Activate the manubot conda environment (assumes conda version >= 4.4)
conda activate manubot

# Build the manuscript, saving outputs to the output directory
bash build/build.sh

# At this point, the HTML & PDF outputs will have been created. The remaining
# commands are for serving the webpage to view the HTML manuscript locally.
# This is required to view local images in the HTML output.

# Configure the webpage directory
manubot webpage

# You can now open the manuscript webpage/index.html in a web browser.
# Alternatively, open a local webserver at http://localhost:8000/ with the
# following commands.
cd webpage
python -m http.server
```

Sometimes it's helpful to monitor the content directory and automatically rebuild the manuscript when a change is detected.
The following command, while running, will trigger both the `build.sh` script and `manubot webpage` command upon content changes:

```sh
bash build/autobuild.sh
```

### Continuous Integration

Whenever a pull request is opened, CI (continuous integration) will test whether the changes break the build process to generate a formatted manuscript.
The build process aims to detect common errors, such as invalid citations.
If your pull request build fails, see the CI logs for the cause of failure and revise your pull request accordingly.

When a commit to the `main` branch occurs (for example, when a pull request is merged), CI builds the manuscript and writes the results to the [`gh-pages`](https://github.com/manubot/rootstock/tree/gh-pages) and [`output`](https://github.com/manubot/rootstock/tree/output) branches.
The `gh-pages` branch uses [GitHub Pages](https://pages.github.com/) to host the following URLs:

+ **HTML manuscript** at https://manubot.github.io/rootstock/
+ **PDF manuscript** at https://manubot.github.io/rootstock/manuscript.pdf

For continuous integration configuration details, see [`.github/workflows/manubot.yaml`](.github/workflows/manubot.yaml) if using GitHub Actions or [`.travis.yml`](.travis.yml) if using Travis CI.
>>>>>>> 9a448fe6edb477fb98065d5b83d206b1ca489cee

## License

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

The Common Software Quality Assurance Baseline Criteria is licensed under a
CC-BY SA 4.0. See [`LICENSE.md`](LICENSE.md).

## Acknowledgment

The EOSC-Synergy project has received funding from the European Union’s Horizon
2020 research and innovation programme under grant agreement number 857647.

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT1WF4g5KH3PnQE_Ve10QFRS-gZ0NpCQ7Qr-_km1RqnOCEF1fQt">
</p>


###### _Manuscript generated with [Manubot](https://greenelab.github.io/manubot-rootstock/)_
