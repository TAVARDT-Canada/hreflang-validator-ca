# Hreflang and International SEO Validator

[![Hreflang Validator](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/ca/hreflang-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audits alternate return tags, regional language targeting, bilingual English and French Canadian routing, and global x-default fallback architecture.

Developed and maintained by the international search architecture and web standards division at **TAVARDT**.

***

## Risk Vectors and Operational Impact in International SEO

Inconsistent hreflang directives create acute crawl budget waste and indexing conflicts for Canadian multi-regional architectures. When language tags fail reciprocity checks, search crawlers ignore regional targeting between English and French Canadian assets.

This fault causes content cannibalisation and presents domestic visitors with incorrect language versions in organic results. Rigorous automated verification ensures Canadian digital platforms maintain spotless international search signals.

***

## Core Technical Audit Capabilities

* **Self-Referencing Tag Validation**: Ensures current page URLs are self-declared within alternate link structures to preserve search engine crawl integrity.
* **Global x-default Fallback Inspection**: Confirms correct fallback routing for international visitors outside targeted geographical zones.
* **ISO 639-1 and ISO 3166-1 Syntax Verification**: Validates language and territorial codes to eliminate malformed regional targeting.
* **Canonical Tag Alignment**: Identifies discrepancies where canonical tags diverge from declared alternate language targets.
* **Dual-Source Parsing**: Extracts alternate annotations seamlessly from both HTML head tags and HTTP Link headers.
* **International Health Score**: Computes an objective 0 to 100 compliance metric with granular technical alerts.

***

## Installation and Execution

Requires Python 3.8 or higher with zero external packages.

```bash
git clone https://github.com/TAVARDT-Canada/hreflang-validator-ca.git
cd hreflang-validator-ca
python hreflang_validator.py https://company.ca
```

To output structured JSON for automated pipelines and quality audits:

```bash
python hreflang_validator.py https://company.ca -j
```

***

## Technical Frequently Asked Questions

### 1. What causes search engines to silently ignore hreflang annotations?
Missing reciprocal return tags and omitted self-referencing links cause crawlers to discard entire alternate tag clusters. This utility inspects tag symmetry and identifies syntax omissions before indexation degradation occurs.

### 2. Why is the x-default annotation essential for multi-regional websites?
The x-default tag provides an authoritative fallback destination for visitors arriving from unassigned geographical territories. Omitting this declaration forces search engines to guess appropriate routing, decreasing international conversion rates.

### 3. How does the validator detect conflicts between canonical and hreflang directives?
The script extracts both canonical declarations and alternate links to verify absolute target alignment. Any discrepancy triggers a critical alert and penalises the overall compliance score by 20 points.

### 4. Does the tool support HTTP Link response headers in addition to HTML tags?
The parser extracts annotations from both HTML head elements and raw HTTP Link headers. This dual capability allows auditing non-HTML assets such as PDF documents and dynamic API endpoints.

### 5. Which international standards govern the validation of language and region codes?
The validator enforces ISO 639-1 for two-letter language identifiers and ISO 3166-1 alpha-2 for regional country codes. Invalid or reversed combinations generate automated warnings and score deductions.

***

## Online Diagnostic Suite

For comprehensive web testing and visual verification of international tags:

* [Hreflang Validator](https://tools.tavardt.com/ca/hreflang-checker/)
* [Corporate Portal](https://ag.tavardt.com/ca/)

***

## International SEO and Multi-Region Architecture Advisory

For bilingual deployment strategies and technical alignment with W3C Internationalisation Standards, consult **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/ca/
* **Diagnostic Suite:** https://tools.tavardt.com/ca/
* **Technical Contact:** https://ag.tavardt.com/ca/contact/

***

### License
Distributed under the MIT License. See the LICENSE file for complete terms.

***

© 2026 TAVARDT. All rights reserved.
