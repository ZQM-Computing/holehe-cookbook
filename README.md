# Holehe Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Holehe cookbook** — email presence checks across public services. Second-tier OSINT tool in the wave-8 set. Patterns are planned from the design, not yet from fleet runs. Check only addresses you own or are authorized to check. It is intended for Practitioners who test whether an email is registered on public services. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Holehe patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Practitioners who test whether an email is registered on public services.

## Prerequisites

- Holehe in the fleet Python environment
- An email address you own or are authorized to check
- Python 3.11+

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-check` | A first presence check and its output |
| 02 | `02-services` | Service coverage and result interpretation |
| 03 | `03-output` | Exporting results for triage |

## Repository layout

```text
holehe-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [h8mail-cookbook](https://github.com/ZQM-Computing/h8mail-cookbook) — Email breach hunting from the command line
- [theharvester-cookbook](https://github.com/ZQM-Computing/theharvester-cookbook) — Passive reconnaissance: domains, emails, and hosts from public sources
- [maigret-cookbook](https://github.com/ZQM-Computing/maigret-cookbook) — Username search with extended site coverage and reporting
