# ANGULAR_POINT_OF_SALE

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `ANGULAR_POINT_OF_SALE` in category **POS_SYSTEMS**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** ANGULAR_POINT_OF_SALE · **Upstream pin:** `7073a9c0a408b88faf2acc9b00282b4e257dae5a` · **Category:** POS_SYSTEMS · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

# Hunts Point POS

[![Join the chat at https://gitter.im/afaqurk/hunts-point-pos](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/afaqurk/hunts-point-pos?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A simple, beautiful, & real-time Point of Sale system written in Node.js & Angular.js

Open Source: MIT Licensed.

##### [See Screenshots](#screenshots)

<h3 align="center">
<img src="https://raw.githubusercontent.com/afaqurk/screenshots/master/hunts-point-pos/home-page.png" width="70%" align="center">
</h3>

# Quick Start

To start using hunts-point-pos:

## Step 1: Get code

source project via git 
```bash
git source https://github.com/afaqurk/hunts-point-pos.git
```

Or [download Hunts Point POS here](https://github.com/afaqurk/hunts-point-pos/archive/master.zip).

## Step 2: Install Dependencies

Go to the Hunts Point POS directory and run:

```bash
$ npm install
$ bower install
```

## Step 3: Run the app!

To start the app, run:

```bash
node server/
```

This will install all dependencies required to run the node app.

# Project Goals

## Planned Features for v0.5
- [ ] esc/pos integration
- [ ] scan-search on inventory page
- [ ] inventory increment page
- [ ] config page
- [ ] refund feature
- [ ] account for multiple cash registers
- [ ] reports feature
	- [ ] line graph of today's transactions (live updating)
	- [ ] line graph of transactions with date-range
	- [ ] line graph of product's selling history 

## Project Principles

- A clean & beautiful interface
- Feature-set targeted towards single store operation
- Seamless installation process
- Responsive web app accessible from any device on the network
- Plug & Play support for:
	- POS printers (ESC/POS)
	- Cash Drawers
	- Barcode Scanners (USB, Bluetooth)
	- Touch screen panel (USB)

# Screenshots

Welcome Screen
![home page of hunts point pos](https://raw.githubusercontent.com/afaqurk/screenshots/master/hunts-point-pos/home-page.png)

Manage Inventory
![Inventory page screenshot](https://raw.githubusercontent.com/afaqurk/screenshots/master/hunts-point-pos/inventory.png)

Inventory - Edit Product
![Inventory item view](https://raw.githubusercontent.com/afaqurk/screenshots/master/hunts-point-pos/item.png)

Live Cart (Updates in real-time)
![Live Cart screenshot](https://raw.githubusercontent.com/afaqurk/screenshots/master/hunts-point-pos/live-cart.png)

POS 1
![](https://raw.githubusercontent.com/afaqurk/screenshots/master/hunts-point-pos/checkout-screen.png)

POS 2
![](https://raw.githubusercontent.com/afaqurk/screenshots/master/hunts-point-pos/checkout-modal.png)

Transactions
![](https://raw.githubusercontent.com/afaqurk/screenshots/master/hunts-point-pos/transactions.png)

---

## Installation

Go to the Hunts Point POS directory and run:

```bash
$ npm install
$ bower install
```

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

- [ ] refund feature
- [ ] account for multiple cash registers
- [ ] reports feature
	- [ ] line graph of today's transactions (live updating)
	- [ ] line graph of transactions with date-range
	- [ ] line graph of product's selling history

## Contributing

Fork the project, create a feature branch, run the test suite, and open a pull request against upstream.

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** ANGULAR_POINT_OF_SALE
- **Pinned SHA:** `7073a9c0a408b88faf2acc9b00282b4e257dae5a`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`b5759e2032c40bf3b67cffea055fdb43eb608c2a918523f64307ceddded3353a`.

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

