# PVLIB

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-solar-lightgrey)

> Anticloud-hardened packaging of the upstream project `PVLIB` in category **SOLAR**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SOLAR · **Upstream:** https://github.com/pvlib/pvlib-python · **Upstream pin:** `88fb562455a43da38329dfc3fe6d5039659a5225` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<img src="docs/sphinx/source/_images/pvlib_logo_horiz.png" width="600">

<table>
<tr>
  <td>Latest Release</td>
  <td>
    <a href="https://pypi.org/project/pvlib/">
    <img src="https://img.shields.io/pypi/v/pvlib.svg" alt="latest release" />
    </a>
    <a href="https://anaconda.org/conda-forge/pvlib">
    <img src="https://anaconda.org/conda-forge/pvlib/badges/version.svg" />
    </a>
    <a href="https://anaconda.org/conda-forge/pvlib">
    <img src="https://anaconda.org/conda-forge/pvlib/badges/latest_release_date.svg" />
    </a>
</tr>
<tr>
  <td>License</td>
  <td>
    <a href="https://github.com/pvlib/pvlib-python/blob/main/LICENSE">
    <img src="https://img.shields.io/pypi/l/pvlib.svg" alt="license" />
    </a>
</td>
</tr>
<tr>
  <td>Build Status</td>
  <td>
    <a href="http://pvlib-python.readthedocs.org/en/stable/">
    <img src="https://readthedocs.org/projects/pvlib-python/badge/?version=stable" alt="documentation build status" />
    </a>
    <a href="https://github.com/pvlib/pvlib-python/actions/workflows/pytest.yml?query=branch%3Amain">
      <img src="https://github.com/pvlib/pvlib-python/actions/workflows/pytest.yml/badge.svg?branch=main" alt="GitHub Actions Testing Status" />
    </a>
    <a href="https://codecov.io/gh/pvlib/pvlib-python">
    <img src="https://codecov.io/gh/pvlib/pvlib-python/branch/main/graph/badge.svg" alt="codecov coverage" />
    </a>
  </td>
</tr>
<tr>
  <td>Benchmarks</td>
  <td>
    <a href="https://pvlib.github.io/pvlib-benchmarks/">
    <img src="https://img.shields.io/badge/benchmarks-asv-lightgrey" />
    </a>
  </td>
</tr>
<tr>
  <td>Publications</td>
  <td>
    <a href="https://doi.org/10.5281/zenodo.593284">
    <img src="https://zenodo.org/badge/DOI/10.5281/zenodo.593284.svg" alt="zenodo reference">
    </a>
    <a style="border-width:0" href="https://doi.org/10.21105/joss.05994">
    <img src="https://joss.theoj.org/papers/10.21105/joss.05994/status.svg" alt="DOI badge" >
    </a>
  </td>
</tr>
</table>

pvlib python is a community developed toolbox that provides a set of
functions and classes for simulating the performance of photovoltaic
energy systems and accomplishing related tasks.  The core mission of pvlib python is to provide open,
reliable, interoperable, and benchmark implementations of PV system models.

Documentation
=============

Full documentation can be found at [readthedocs](http://pvlib-python.readthedocs.io/en/stable/),
including an [FAQ](https://pvlib-python.readthedocs.io/en/stable/user_guide/extras/faq.html) page.

Installation
============

pvlib-python releases may be installed using the ``pip`` and ``conda`` tools.
```bash
pip install pvlib
conda install -c conda-forge pvlib
```
Please see the [Installation page](https://pvlib-python.readthedocs.io/en/stable/user_guide/getting_started/installation.html) of the documentation for complete instructions.

Contributing
============

We need your help to make pvlib-python a great tool!
Please see the [Contributing page](https://pvlib-python.readthedocs.io/en/stable/contributing/index.html) for more on how you can contribute.
The long-term success of pvlib-python requires substantial community support.

Citing
======

Many of the contributors to pvlib python work in institutions where
citation metrics are used in performance or career evaluations. If you
use pvlib python in a published work, please cite:

**Recommended citation for the pvlib python project**

  Anderson, K., Hansen, C., Holmgren, W., Jensen, A., Mikofski, M., and Driesse, A.
  "pvlib python: 2023 project update."
  Journal of Open Source Software, 8(92), 5994, (2023).
  https://doi.org/10.21105/joss.05994

**Recommended citation for pvlib iotools**

  Jensen, A., Anderson, K., Holmgren, W., Mikofski, M., Hansen, C., Boeman, L., Loonen, R.
  "pvlib iotools —- Open-source Python functions for seamless access to solar irradiance data."
  Solar Energy, 266, 112092, (2023).
  https://doi.org/10.1016/j.solener.2023.112092

**Historical citation for pvlib python**

  Holmgren, W., Hansen, C., and Mikofski, M.
  "pvlib python: a python package for modeling solar energy systems."
  Journal of Open Source Software, 3(29), 884, (2018).
  https://doi.org/10.21105/joss.00884

If you use pvlib-python in a commercial or publicly-available application, please
consider displaying one of the "powered by pvlib" logos:

<img src="docs/sphinx/source/_images/pvlib_powered_logo_vert.png" width="300"><img src="docs/sphinx/source/_images/pvlib_powered_logo_horiz.png" width="300">

Getting support
===============

pvlib usage questions can be asked on
[Stack Overflow](http://stackoverflow.com) and tagged with
the [pvlib](http://stackoverflow.com/questions/tagged/pvlib) tag.

The [pvlib-python google group](https://groups.google.com/forum/#!forum/pvlib-python)
is used for discussing various topics of interest to the pvlib-python
community. We also make new version announcements on the google group.

If you suspect that you may have discovered a bug or if you'd like to
change something about pvlib, then please make an issue on our
[GitHub issues page](https://github.com/pvlib/pvlib-python/issues).

License
=======

BSD 3-clause.

History and acknowledgement
===========================

pvlib python began in 2013 as a Python translation of the [PVLIB for Matlab](https://github.com/sandialabs/MATLAB_PV_LIB)
toolbox developed by Sandia National Laboratories. pvlib python has grown substantially since then.
Today it contains code contributions from over a hundred individuals worldwide
and is maintained by a core group of PV modelers from a variety of institutions.

pvlib has been supported directly and indirectly by DOE, NumFOCUS, and
Google Summer of Code funding, university research projects,
companies that allow their employees to contribute, and from personal time.

NumFOCUS
========

pvlib python is a [NumFOCUS Affiliated Project](https://numfocus.org/sponsored-projects/affiliated-projects)

[![NumFocus Affliated P

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python** (manifests: pyproject.toml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `benchmarks/`, `ci/`, `paper/`, `pvlib/`, `tests/`
- Snapshot size: **452 files**, **66359 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (187), `.rst` (113), `.csv` (46), `.txt` (20), `.png` (16), `.ipynb` (8)
- Upstream commit pinned for this packaging: `88fb562455a43da38329dfc3fe6d5039659a5225`

---

## Installation

<td>
    <a href="http://pvlib-python.readthedocs.org/en/stable/">
    <img src="https://readthedocs.org/projects/pvlib-python/badge/?version=stable" alt="documentation build status" />
    </a>
    <a href="https://github.com/pvlib/pvlib-python/actions/workflows/pytest.yml?query=branch%3Amain">
      <img src="https://github.com/pvlib/pvlib-python/actions/workflows/pytest.yml/badge.svg?branch=main" alt="GitHub Actions Testing Status" />
    </a>
    <a href="https://codecov.io/gh/pvlib/pvlib-python">
    <img src="https://codecov.io/gh/pvlib/pvlib-python/branch/main/graph/badge.svg" alt="codecov coverage" />
    </a>
  </td>
</tr>
<tr>
  <td>Benchmarks</td>
  <td>
    <a href="https://pvlib.github.io/pvlib-benchmarks/">
    <img src="https://img.shields.io/badge/benchmarks-asv-lightgrey" />
    </a>
  </td>
</tr>
<tr>
  <td>Publications</td>
  <td>
    <a href="https://doi.org/10.5281/zenodo.593284">
    <img src="https://zenodo.org/badge/DOI/10.5281/zenodo.593284.svg" alt="zenodo reference">
    </a>
    <a style="border-width:0" href="https://doi.org/10.21105/joss.05994">
    <img src="https://joss.theoj.org/papers/10.21105/joss.05994/status.svg" alt="DOI badge" >
    </a>
  </td>
</tr>
</table>

pvlib python is a community developed toolbox that provides a set of
functions and classes for simulating the performance of photovoltaic
energy systems and accomplishing related tasks.  The core mission of pvlib python is to provide open,
reliable, interoperable, and benchmark implementations of PV system models.

Documentation
=============

Full documentation can be found at [readthedocs](http://pvlib-python.readthedocs.io/en/stable/),
including an [FAQ](https://pvlib-python.readthedocs.io/en/stable/user_guide/extras/faq.html) page.

Installation
============

pvlib-python releases may be installed using the ``pip`` and ``conda`` tools.
```bash
pip install pvlib
conda install -c conda-forge pvlib
```
Please see the [Installation page](https://pvlib-python.readthedocs.io/en/stable/user_guide/getting_started/installation.html) of the documentation for complete instructions.

Contributing
============

We need your help to make pvlib-python a great tool!
Please see the [Contributing page](https://pvlib-python.readthedocs.io/en/stable/contributing/index.html) for more on how you can contribute.
The long-term success of pvlib-python requires substantial community support.

Citing
======

Many of the contributors to pvlib python work in institutions where
citation metrics are used in performance or career evaluations. If you
use pvlib python in a published work, please cite:

**Recommended citation for the pvlib python project**

  Anderson, K., Hansen, C., Holmgren, W., Jensen, A., Mikofski, M., and Driesse, A.
  "pvlib python: 2023 project update."
  Journal of Open Source Software, 8(92), 5994, (2023).
  https://doi.org/10.21105/joss.05994

**Recommended citation for pvlib iotools**

  Jensen, A., Anderson, K., Holmgren, W., Mikofski, M., Hansen, C., Boeman, L., Loonen, R.
  "pvlib iotools —- Open-source Python functions for seamless access to solar irradiance data."
  Solar Energy, 266, 112092, (2023).
  https://doi.org/10.1016/j.solener.2023.112092

**Historical citation for pvlib python**

  Holmgren, W., Hansen, C., and Mikofski, M.
  "pvlib python: a python package for modeling solar energy systems."
  Journal of Open Source Software, 3(29), 884, (2018).
  https://doi.org/10.21105/joss.00884

If you use pvlib-python in a commercial or publicly-available application, please
consider displaying one of the "powered by pvlib" logos:

<img src="docs/sphinx/source/_images/pvlib_powered_logo_vert.png" width="300"><img src="docs/sphinx/source/_images/pvlib_powered_logo_horiz.png" width="300">

Getting support
===============

pvlib usage questions can be asked on
[Stack Overflow](http://stackoverflow.com) and tagged with
the [pvlib](http://stackoverflow.com/questions/tagged/pvlib) tag.

The [pvlib-python google group](https://groups.google.com/forum/#!forum/pvlib-python)
is used for discussing various topics of interest to the pvlib-python
community. We also make new version announcements on the google group.

If you suspect that you may have discovered a bug or if you'd like to
change something about pvlib, then please make an issue on our
[GitHub issues page](https://github.com/pvlib/pvlib-python/issues).

License
=======

BSD 3-clause.

History and acknowledgement
===========================

pvlib python began in 2013 as a Python translation of the [PVLIB for Matlab](https://github.com/sandialabs/MATLAB_PV_LIB)
toolbox developed by Sandia National Laboratories. pvlib python has grown substantially since then.
Today it contains code contributions from over a hundred individuals worldwide
and is maintained by a core group of PV modelers from a variety of institutions.

pvlib has been supported directly and indirectly by DOE, NumFOCUS, and
Google Summer of Code funding, university research projects,
companies that allow their employees to contribute, and from personal time.

NumFOCUS
========

pvlib python is a [NumFOCUS Affiliated Project](https://numfocus.org/sponsored-projects/affiliated-projects)

[![NumFocus Affliated Projects](https://i0.wp.com/numfocus.org/wp-content/uploads/2019/06/AffiliatedProject.png)](https://numfocus.org/sponsored-projects/affiliated-projects)

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

**Recommended citation for the pvlib python project**

  Anderson, K., Hansen, C., Holmgren, W., Jensen, A., Mikofski, M., and Driesse, A.
  "pvlib python: 2023 project update."
  Journal of Open Source Software, 8(92), 5994, (2023).
  https://doi.org/10.21105/joss.05994

**Recommended citation for pvlib iotools**

  Jensen, A., Anderson, K., Holmgren, W., Mikofski, M., Hansen, C., Boeman, L., Loonen, R.
  "pvlib iotools —- Open-source Python functions for seamless access to solar irradiance data."
  Solar Energy, 266, 112092, (2023).
  https://doi.org/10.1016/j.solener.2023.112092

**Historical citation for pvlib python**

  Holmgren, W., Hansen, C., and Mikofski, M.
  "pvlib python: a python package for modeling solar energy systems."
  Journal of Open Source Software, 3(29), 884, (2018).
  https://doi.org/10.21105/joss.00884

If you use pvlib-python in a commercial or publicly-available application, please
consider displaying one of the "powered by pvlib" logos:

<img src="docs/sphinx/source/_images/pvlib_powered_logo_vert.png" width="300"><img src="docs/sphinx/source/_images/pvlib_powered_logo_horiz.png" width="300">

Getting support
===============

pvlib usage questions can be asked on
[Stack Overflow](http://stackoverflow.com) and tagged with
the [pvlib](http://stackoverflow.com/questions/tagged/pvlib) tag.

The [pvlib-python google group](https://groups.google.com/forum/#!forum/pvlib-python)
is used for discussing various topics of interest to the pvlib-python
community. We also make new version announcements on the google group.

If you suspect that you may have discovered a bug or if you'd like to
change something about pvlib, then please make an issue on our
[GitHub issues page](https://github.com/pvlib/pvlib-python/issues).

License
=======

BSD 3-clause.

History and acknowledgement
===========================

pvlib python began in 2013 as a Python translation of the [PVLIB for Matlab](https://github.com/sandialabs/MATLAB_PV_LIB)
toolbox developed by Sandia National Laboratories. pvlib python has grown substantially since then.
Today it contains code contributions from over a hundred individuals worldwide
and is maintained by a core group of PV modelers from a variety of institutions.

pvlib has been supported directly and indirectly by DOE, NumFOCUS, and
Google Summer of Code funding, university research projects,
companies that allow their employees to contribute, and from personal time.

NumFOCUS
========

pvlib python is a [NumFOCUS Affiliated Project](https://numfocus.org/sponsored-projects/affiliated-projects)

[![NumFocus Affliated Projects](https://i0.wp.com/numfocus.org/wp-content/uploads/2019/06/AffiliatedProject.png)](https://numfocus.org/sponsored-projects/affiliated-projects)

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

</a>
    <a href="https://github.com/pvlib/pvlib-python/actions/workflows/pytest.yml?query=branch%3Amain">
      <img src="https://github.com/pvlib/pvlib-python/actions/workflows/pytest.yml/badge.svg?branch=main" alt="GitHub Actions Testing Status" />
    </a>
    <a href="https://codecov.io/gh/pvlib/pvlib-python">
    <img src="https://codecov.io/gh/pvlib/pvlib-python/branch/main/graph/badge.svg" alt="codecov coverage" />
    </a>
  </td>
</tr>
<tr>
  <td>Benchmarks</td>
  <td>
    <a href="https://pvlib.github.io/pvlib-benchmarks/">
    <img src="https://img.shields.io/badge/benchmarks-asv-lightgrey" />
    </a>
  </td>
</tr>
<tr>
  <td>Publications</td>
  <td>
    <a href="https://doi.org/10.5281/zenodo.593284">
    <img src="https://zenodo.org/badge/DOI/10.5281/zenodo.593284.svg" alt="zenodo reference">
    </a>
    <a style="border-width:0" href="https://doi.org/10.21105/joss.05994">
    <img src="https://joss.theoj.org/papers/10.21105/joss.05994/status.svg" alt="DOI badge" >
    </a>
  </td>
</tr>
</table>

pvlib python is a community developed toolbox that provides a set of
functions and classes for simulating the performance of photovoltaic
energy systems and accomplishing related tasks.  The core mission of pvlib python is to provide open,
reliable, interoperable, and benchmark implementations of PV system models.

Documentation
=============

Full documentation can be found at [readthedocs](http://pvlib-python.readthedocs.io/en/stable/),
including an [FAQ](https://pvlib-python.readthedocs.io/en/stable/user_guide/extras/faq.html) page.

Installation
============

pvlib-python releases may be installed using the ``pip`` and ``conda`` tools.
```bash
pip install pvlib
conda install -c conda-forge pvlib
```
Please see the [Installation page](https://pvlib-python.readthedocs.io/en/stable/user_guide/getting_started/installation.html) of the documentation for complete instructions.

Contributing
============

We need your help to make pvlib-python a great tool!
Please see the [Contributing page](https://pvlib-python.readthedocs.io/en/stable/contributing/index.html) for more on how you can contribute.
The long-term success of pvlib-python requires substantial community support.

Citing
======

Many of the contributors to pvlib python work in institutions where
citation metrics are used in performance or career evaluations. If you
use pvlib python in a published work, please cite:

**Recommended citation for the pvlib python project**

  Anderson, K., Hansen, C., Holmgren, W., Jensen, A., Mikofski, M., and Driesse, A.
  "pvlib python: 2023 project update."
  Journal of Open Source Software, 8(92), 5994, (2023).
  https://doi.org/10.21105/joss.05994

**Recommended citation for pvlib iotools**

  Jensen, A., Anderson, K., Holmgren, W., Mikofski, M., Hansen, C., Boeman, L., Loonen, R.
  "pvlib iotools —- Open-source Python functions for seamless access to solar irradiance data."
  Solar Energy, 266, 112092, (2023).
  https://doi.org/10.1016/j.solener.2023.112092

**Historical citation for pvlib python**

  Holmgren, W., Hansen, C., and Mikofski, M.
  "pvlib python: a python package for modeling solar energy systems."
  Journal of Open Source Software, 3(29), 884, (2018).
  https://doi.org/10.21105/joss.00884

If you use pvlib-python in a commercial or publicly-available application, please
consider displaying one of the "powered by pvlib" logos:

<img src="docs/sphinx/source/_images/pvlib_powered_logo_vert.png" width="300"><img src="docs/sphinx/source/_images/pvlib_powered_logo_horiz.png" width="300">

Getting support
===============

pvlib usage questions can be asked on
[Stack Overflow](http://stackoverflow.com) and tagged with
the [pvlib](http://stackoverflow.com/questions/tagged/pvlib) tag.

The [pvlib-python google group](https://groups.google.com/forum/#!forum/pvlib-python)
is used for discussing various topics of interest to the pvlib-python
community. We also make new version announcements on the google group.

If you suspect that you may have discovered a bug or if you'd like to
change something about pvlib, then please make an issue on our
[GitHub issues page](https://github.com/pvlib/pvlib-python/issues).

License
=======

BSD 3-clause.

History and acknowledgement
===========================

pvlib python began in 2013 as a Python translation of the [PVLIB for Matlab](https://github.com/sandialabs/MATLAB_PV_LIB)
toolbox developed by Sandia National Laboratories. pvlib python has grown substantially since then.
Today it contains code contributions from over a hundred individuals worldwide
and is maintained by a core group of PV modelers from a variety of institutions.

pvlib has been supported directly and indirectly by DOE, NumFOCUS, and
Google Summer of Code funding, university research projects,
companies that allow their employees to contribute, and from personal time.

NumFOCUS
========

pvlib python is a [NumFOCUS Affiliated Project](https://numfocus.org/sponsored-projects/affiliated-projects)

[![NumFocus Affliated Projects](https://i0.wp.com/numfocus.org/wp-content/uploads/2019/06/AffiliatedProject.png)](https://numfocus.org/sponsored-projects/affiliated-projects)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python |
| Manifests detected | pyproject.toml |
| Files in snapshot | 452 |
| Lines of code | 66359 |
| Dependency references | 7 |
| Dependencies by ecosystem | pypi: 7 |
| Upstream license | BSD-3-Clause |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| pypi | numpy | >= | pyproject.toml |
| pypi | pandas | >= | pyproject.toml |
| pypi | pytz | - | pyproject.toml |
| pypi | requests | - | pyproject.toml |
| pypi | scipy | >= | pyproject.toml |
| pypi | h5py | - | pyproject.toml |
| pypi | tzdata | - | pyproject.toml |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `pyproject.toml`
- `setup.cfg`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `.github/CONTRIBUTING.md`:*

Contributing
============

We welcome your contributions! Please see the [contributing](https://pvlib-python.readthedocs.io/en/stable/contributing/index.html) page for information about how to contribute.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: BSD-3-Clause** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
BSD 3-Clause License

Copyright (c) 2023 pvlib python Contributors
Copyright (c) 2014 PVLIB python Development Team
Copyright (c) 2013 Sandia National Laboratories

All rights reserved.

Redistribution and use in source and binary forms, with or without modification,
are permitted provided that the following conditions are met:

  Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

  Redistributions in binary form must reproduce the above copyright notice, this
  list of conditions and the following disclaimer in the documentation and/or
  other materials provided with the distribution.

  Neither the name of the copyright holder nor the names of its
  contributors may be used to endorse or promote products derived from
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original BSD-3-Clause terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `BSD-3-Clause` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `PVLIB` (category: SOLAR)
- **Upstream URL:** https://github.com/pvlib/pvlib-python
- **Pinned commit (SHA):** `88fb562455a43da38329dfc3fe6d5039659a5225`
- **Branch:** main
- **Pin provenance:** GitHub API commits/main. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`3c2a384e978ea7cf22efc313693cbfbe670eac962439754767acc2d484b83300`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

