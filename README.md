# OPENFRAMEWORKS

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-artist_tools-lightgrey)

> Anticloud-hardened packaging of the upstream project `OPENFRAMEWORKS` in category **ARTIST TOOLS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** ARTIST TOOLS · **Upstream:** https://github.com/openframeworks/openframeworks · **Upstream pin:** `5052e08a015a324df7adceb2a3c4278fafb3c5a2` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

[openFrameworks](http://openframeworks.cc/)
================

openFrameworks is a C++ toolkit for creative coding.  If you are new to OF, welcome!

- [Grab the Nightly Release (to avoid submodule cloning)](https://github.com/openframeworks/openFrameworks/releases)
- [Setup guides for different Platforms](https://openframeworks.cc/download/)
- [Join Our Slack](https://join.slack.com/t/openframeworks/shared_invite/zt-1r2brqms0-dZMMFZgZhFTgomjJ0vlCjA)
- [Discuss on the Forum](https://forum.openframeworks.cc) 
- [Follow OF on Mastodon](https://fosstodon.org/@openframeworks)

## Build status

* The **master** branch contains the newest, most recently updated code. This code is packaged and available for download in the "Nightly Builds" section of [openframeworks.cc/download](https://openframeworks.cc/download/).
* The **stable** branch contains the code corresponding to the last stable openFrameworks release. This stable code is packaged and available for download at [openframeworks.cc/download](https://openframeworks.cc/download/).

Platform                     | Master branch  | Stable branch
-----------------------------|:---------|:---------
Windows MSYS2        | [![Build status](https://github.com/openframeworks/openFrameworks/workflows/build-msys2/badge.svg)](https://github.com/openframeworks/openFrameworks/actions) | [![Build status](https://github.com/openframeworks/openFrameworks/workflows/build-msys2/badge.svg?branch=stable)](https://github.com/openframeworks/openFrameworks/actions)
Windows Visual Studio  | [![Build status](https://github.com/openframeworks/openFrameworks/workflows/build-vs/badge.svg)](https://github.com/openframeworks/openFrameworks/actions) | [![Build status](https://github.com/openframeworks/openFrameworks/workflows/build-vs/badge.svg?branch=stable)](https://github.com/openframeworks/openFrameworks/actions)
Linux 64 & Arm                    | [![Linux Build Status](https://github.com/openframeworks/openFrameworks/workflows/build-linux64-and-arm/badge.svg)](https://github.com/openframeworks/openFrameworks/actions) | [![Linux Build Status](https://github.com/openframeworks/openFrameworks/workflows/build-linux64-and-arm/badge.svg?branch=stable)](https://github.com/openframeworks/openFrameworks/actions)
Emscripten                   | [![Emscripten Build Status](https://github.com/openframeworks/openFrameworks/workflows/build-emscripten/badge.svg)](https://github.com/openframeworks/openFrameworks/actions) | [![Emscripten Build Status](https://github.com/openframeworks/openFrameworks/workflows/build-emscripten/badge.svg?branch=stable)](https://github.com/openframeworks/openFrameworks/actions) 
macos                        | [![macos Build Status](https://github.com/openframeworks/openFrameworks/workflows/build-macos/badge.svg)](https://github.com/openframeworks/openFrameworks/actions) | [![macos Build Status](https://github.com/openframeworks/openFrameworks/workflows/build-macos/badge.svg?branch=stable)](https://github.com/openframeworks/openFrameworks/actions)
iOS & tvOS                         | [![iOS tvOS Build Status](https://github.com/openframeworks/openFrameworks/workflows/build-ios-tvos/badge.svg)](https://github.com/openframeworks/openFrameworks/actions) | [![iOS tvOS Build Status](https://github.com/openframeworks/openFrameworks/workflows/build-ios-tvos/badge.svg?branch=stable)](https://github.com/openframeworks/openFrameworks/actions)

<!-- Android Arm7                 | [![Android Build Status](https://github.com/openframeworks/openFrameworks/workflows/build-android/badge.svg)](https://github.com/openframeworks/openFrameworks/actions) | [![Android Build Status](https://github.com/openframeworks/openFrameworks/workflows/build-android/badge.svg?branch=stable)](https://github.com/openframeworks/openFrameworks/actions) -->

## folder structure

This release of OF comes with several folders:

* addons
* apps
* docs
* examples
* export (on some systems)
* libs
* other
* scripts
* projectGenerator

`docs` has some documentation around OF usage, per platform things to consider, etc. You should definitely take a look in there; for example, if you are on OSX, read the osx.md.   `apps` and `examples` are where projects go -- `examples` contains a variety of projects that show you how to use OF, and `apps` is where your own projects will go.  `libs` contains the libraries that OF uses, including the openframeworks core itself.  `addons` are for additional functionality that's not part of the core.  `export` is for DLLs and dylibs that need to be put in each compiled project.  The `scripts` folder has the templates and small scripts for automating OF per platform. `project generator` is a GUI based tool for making new projects - this folder is only there in packaged releases.  

One idea that's important is that OF releases are designed to be self-contained.  You can put them anywhere on your hard drive, but it's not possible to mix different releases of OF together, so please keep each release (0.8.0, 0.8.1) separate.  Projects may generally work from release to release, but this is not guaranteed.  Because OF is self-contained, there's extensive use of local file paths (ie, ../../../) throughout OF.  It's important to be aware of how directories are structured.  A common error is to take a project and move it so that it's a level below or above where it used to be compared to the root of OF.  This means that links such as ../../../libs will break.  

## Get involved

The openframeworks forum:

[http://forum.openframeworks.cc/](http://forum.openframeworks.cc/)

is a warm and friendly place.  Please ask or answer a question.  The most important part of this project is that it's a community, more than just a tool, so please join us!  Also, this is free software, and we learn so much about what is hard, what doesn't make sense, what is useful, etc. The most basic questions are acceptable here!  Don't worry, just join the conversation.  Learning in OF is social, it's

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `addons/`, `apps/`, `examples/`, `libs/`, `scripts/`, `tests/`
- Upstream commit pinned for this packaging: `5052e08a015a324df7adceb2a3c4278fafb3c5a2`

---

## Installation

- [Join Our Slack](https://join.slack.com/t/openframeworks/shared_invite/zt-1r2brqms0-dZMMFZgZhFTgomjJ0vlCjA)
- [Discuss on the Forum](https://forum.openframeworks.cc) 
- [Follow OF on Mastodon](https://fosstodon.org/@openframeworks)

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

* export (on some systems)
* libs
* other
* scripts
* projectGenerator

`docs` has some documentation around OF usage, per platform things to consider, etc. You should definitely take a look in there; for example, if you are on OSX, read the osx.md.   `apps` and `examples` are where projects go -- `examples` contains a variety of projects that show you how to use OF, and `apps` is where your own projects will go.  `libs` contains the libraries that OF uses, including the openframeworks core itself.  `addons` are for additional functionality that's not part of the core.  `export` is for DLLs and dylibs that need to be put in each compiled project.  The `scripts` folder has the templates and small scripts for automating OF per platform. `project generator` is a GUI based tool for making new projects - this folder is only there in packaged releases.  

One idea that's important is that OF releases are designed to be self-contained.  You can put them anywhere on your hard drive, but it's not possible to mix different releases of OF together, so please keep each release (0.8.0, 0.8.1) separate.  Projects may generally work from release to release, but this is not guaranteed.  Because OF is self-contained, there's extensive use of local file paths (ie, ../../../) throughout OF.  It's important to be aware of how directories are structured.  A common error is to take a project and move it so that it's a level below or above where it used to be compared to the root of OF.  This means that links such as ../../../libs will break.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

One idea that's important is that OF releases are designed to be self-contained.  You can put them anywhere on your hard drive, but it's not possible to mix different releases of OF together, so please keep each release (0.8.0, 0.8.1) separate.  Projects may generally work from release to release, but this is not guaranteed.  Because OF is self-contained, there's extensive use of local file paths (ie, ../../../) throughout OF.  It's important to be aware of how directories are structured.  A common error is to take a project and move it so that it's a level below or above where it used to be compared to the root of OF.  This means that links such as ../../../libs will break.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | not captured in this benchmark snapshot |
| Lines of code | not captured in this benchmark snapshot |
| Dependency references | not captured in this benchmark snapshot |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

To set up the project generator submodule within the OF project, use the command `git submodule init` then `git submodule update` whilst inside the openFrameworks project.

For more info on working with the Project Generator, for per-platform readmes, and more information, see the [documentation](docs/table_of_contents.md).

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contribute to openFrameworks

Thank you for contributing! openFrameworks is a community-built, maintained and operated project that welcomes contributions from all members of the openFrameworks community in its broadest sense. 

This document outlines the procedures and what to expect when contributing a bug report, a feature request, or new code via a pull request.
If you want to contribute documentation have a look at the [ofSite git project](https://github.com/openframeworks/ofSite). 

**Please read** and **follow these guidelines** before submitting a bug report, feature request or pull request.
It really helps us efficiently process your contribution!

Jump to: [report a bug](#bug-reports), [request a feature](#feature-requests), [contribute code](#contributing-code).

## <a id='bug-reports'></a>Report a bug

We love hearing about bugs! It's how we get them fixed. 

- If you notice something odd happening, try to make it happen again (reproduce it). 
- If you can reproduce it, try to figure out if it's caused by your code or by openFrameworks. 
- If it's caused by openFrameworks, make sure it **still occurs in the current development version** (where we continually fix problems) by checking out with git or [downloading](https://github.com/openframeworks/openFrameworks/archive/master.zip) the current `master` branch of OF.
- If it looks like it's caused by openFrameworks (or if you're not sure) and still occurs on the current `master` branch, submit a bug report to the [issue tracker](https://github.com/openframeworks/openFrameworks/issues).
  - **Search the issue tracker** to make sure your problem has not been reported yet. If you find a relevant bug, comment there, even if it's an old or closed one! 
  - Only if you don't find a relevant issue, open a new issue. A new issue does not generate more exposure/visibility than commenting on an existing one.
  - Make sure you give it a good title! 
  A good title explains the core of the problem in about 5-10 words. (It's sometimes easier to write the title after you've written the description.)
    - Examples of bad titles: _problem with ofRectangle_ or _can't set color_
    - Examples of good titles: _ofRectangle crashes if the width is 0_ or _ofSetColor doesn't work with ofPath objects_.
  - In the description, include the following details:
    0. **relevant system information** such as which openFrameworks version, operating system, and IDE you are using,
    1. what you were doing when you notic

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE.md` in the upstream snapshot).

License file excerpt:

```text
**openFrameworks** is distributed under the [MIT License](https://en.wikipedia.org/wiki/MIT_License). This gives everyone the freedoms to use openFrameworks in any context: commercial or non-commercial, public or private, open or closed source.

---

Copyright (c) 2025 - openFrameworks Community

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

openFrameworks also ships with a mix of the following [libraries](docs/libraries.md), depending on your platform, which may have different licenses.

* [OpenGL](http://www.opengl.org/), [GLEW](http://glew.sourceforge.net/), [GLUT](http://www.opengl.org/resources/libraries/glut/), [libtess2](https://code.google.com/p/libtess2/) and [cairo](http://cairographics.org/) for graphics
* [rtAudio](http://www.music.mcgill.ca/~gary/rtaudio/), [PortAudio](http://www.portaudio.com/) or [FMOD](http://www.fmod.org/)  and [Kiss FFT](http://kissfft.sourceforge.net/) for audio input, output and analysis
* [FreeType](http://freetype.sourceforge.net/index2.html) for fonts
* [FreeImage](http://freeimage.sourceforge.net/) for image saving and loading
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `OPENFRAMEWORKS` (category: ARTIST TOOLS)
- **Upstream URL:** https://github.com/openframeworks/openframeworks
- **Pinned commit (SHA):** `5052e08a015a324df7adceb2a3c4278fafb3c5a2`
- **Branch:** master
- **Pin provenance:** GitHub API commits/<branch> (response quoted in report). The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`11b52373ff44becc6c8507398b868b1fc1d0a65e79a53a29d82f4512ce805a5f`.

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
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

