## Digital Forensics Artifact Repository

A free, community-sourced, machine-readable knowledge base of digital forensic
artifacts that the world can use both as an information source and within other
tools.

If you'd like to use the artifacts in your own tools, **all you need to be able
to do is read YAML**. That is it, no other dependencies. The Python code in
this project is just used to validate all the artifacts to make sure they
follow the specfication.

### Project status

[Travis-CI](https://travis-ci.org/) | [AppVeyor](https://ci.appveyor.com) | [Codecov](https://codecov.io/)
--- | --- | ---
[![Build Status](https://travis-ci.org/ForensicArtifacts/artifacts.svg?branch=master)](https://travis-ci.org/ForensicArtifacts/artifacts) | [![Build status](https://ci.appveyor.com/api/projects/status/7gv9fwr269527cj1?svg=true)](https://ci.appveyor.com/project/forensicartifacts/artifacts) | [![codecov](https://codecov.io/gh/ForensicArtifacts/artifacts/branch/master/graph/badge.svg)](https://codecov.io/gh/ForensicArtifacts/artifacts)

## Artifact Definitions

The artifact definitions can be found in the [data directory](https://github.com/ForensicArtifacts/artifacts/tree/master/data)
and the format is described in detail in the [Style Guide](https://github.com/ForensicArtifacts/artifacts/blob/master/docs/Artifacts%20definition%20format%20and%20style%20guide.asciidoc).

As of 2019-06-10 the repository contains:

| **File paths covered** | **1013** |
| :------------------ | ------: |
| **Registry keys covered** | **635** |
| **Total artifacts** | **525** |

**Artifacts by type**

| ARTIFACT_GROUP | COMMAND | DIRECTORY | FILE | PATH | REGISTRY_KEY | REGISTRY_VALUE | WMI |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 21 | 9 | 14 | 283 | 8 | 50 | 114 | 26 |

**Artifacts by OS**

| Darwin | Linux | Windows |
| :---: | :---: | :---: |
| 33 | 25 | 23 |

**Artifacts by label**

| Antivirus | Authentication | Browser | Cloud | Cloud Storage | Configuration Files | Docker | External Media | ExternalAccount | Hadoop | History Files | Logs | Mail | Network | Software | System | Users | iOS |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 6 | 18 | 21 | 2 | 4 | 41 | 2 | 2 | 3 | 1 | 3 | 46 | 15 | 15 | 43 | 104 | 68 | 5 |

## Background/History

The [ForensicArtifacts.com](http://forensicartifacts.com/) artifact repository
was forked from the [GRR project](https://github.com/google/grr) artifact
collection into a stand-alone repository that is not tool-specific. The GRR
developers have migrated to using this repository and make contributions here. In
addition the ForensicArtifact team will begin backfilling artifacts in the new
format from the [ForensicArtifacts.com](http://forensicartifacts.com/) website.

For some background on the artifacts system and how we expect it to be used see
[this blackhat presentation](https://www.blackhat.com/us-14/archives.html#grr-find-all-the-badness-collect-all-the-things)
and [youtube video](https://www.youtube.com/watch?v=ren6QSvwFvg) from the GRR team.

## Contributing

Please send us your contribution! See [the developers guide](https://github.com/ForensicArtifacts/artifacts/wiki/Developers-guide) for instructions.

## External links

* [GRR Artifacts](https://www.blackhat.com/docs/us-14/materials/us-14-Castle-GRR-Find-All-The-Badness-Collect-All-The-Things-WP.pdf), by Greg Castle, Blackhat 2014

## Contact

* [forensicartifacts@googlegroups.com](https://groups.google.com/forum/#!forum/forensicartifacts)
* Artifacts channel of [Open Source DFIR Slack](https://github.com/open-source-dfir/slack)

