# Accounting Standards (accounting-standards)
Accounting Standards are the formal rules and guidelines that govern how financial transactions and statements are recorded, reported, and disclosed. They ensure consistency, transparency, and comparability across financial reports, and include frameworks like GAAP and IFRS. Digital reporting standards like XBRL enable structured, machine-readable financial filings.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Accounting Standards, Finance, GAAP, IFRS, XBRL, Financial Reporting, SEC, FASB

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### US GAAP Financial Reporting Taxonomy 2026
The 2026 GAAP Financial Reporting Taxonomy (GRT) is the official XBRL taxonomy maintained by FASB for SEC financial filings. It incorporates updates for FASB accounting standards published through December 1, 2025. The taxonomy provides structured element definitions for US Generally Accepted Accounting Principles (GAAP) financial statement reporting, available in XSD format with namespace http://fasb.org/us-gaap/2026.

**Human URL:** [https://xbrl.us/xbrl-taxonomy/2026-us-gaap/](https://xbrl.us/xbrl-taxonomy/2026-us-gaap/)

#### Tags:

 - GAAP, XBRL, FASB, SEC, Financial Reporting

#### Properties

- [Documentation](https://xbrl.us/xbrl-taxonomy/2026-us-gaap/)
- [Specification](https://fasb.org/standards)
- [FASB Accounting Standards Codification](https://asc.fasb.org/)
- [GAAP Accounting Standard Schema](json-schema/gaap-accounting-standard-schema.json)
- [GAAP Accounting Standard Structure](json-structure/gaap-accounting-standard-structure.json)
- [GAAP Accounting Standard Example](examples/gaap-accounting-standard-example.json)

### SEC EDGAR XBRL API
The SEC EDGAR XBRL APIs provide free, real-time access to structured financial data from public company filings. APIs include company submissions, company facts (all XBRL disclosures), company concepts (individual taxonomy tags per company), and aggregated XBRL frames across all filers. Data is returned in JSON and covers US-GAAP, IFRS, DEI, and SRT taxonomies. Rate limit is 10 requests/second with required User-Agent header.

**Human URL:** [https://www.sec.gov/about/developer-resources](https://www.sec.gov/about/developer-resources)

#### Tags:

 - SEC, EDGAR, XBRL, Financial Data, Open Data, REST API

#### Properties

- [Documentation](https://www.sec.gov/about/developer-resources)
- [APIReference](https://www.sec.gov/search-filings/edgar-application-programming-interfaces)
- [Rate Limits](https://www.sec.gov/about/developer-resources)
- [XBRL Financial Fact Schema](json-schema/xbrl-financial-fact-schema.json)
- [Edgar Company Submission Schema](json-schema/edgar-company-submission-schema.json)
- [XBRL Financial Fact Structure](json-structure/xbrl-financial-fact-structure.json)
- [Edgar Company Submission Structure](json-structure/edgar-company-submission-structure.json)
- [XBRL Financial Fact Example](examples/xbrl-financial-fact-example.json)
- [Edgar Company Submission Example](examples/edgar-company-submission-example.json)

### IFRS Accounting Standards
International Financial Reporting Standards (IFRS) are global accounting standards issued by the International Accounting Standards Board (IASB). IFRS standards govern the financial reporting of companies in over 140 jurisdictions. The IFRS Foundation publishes the IFRS Taxonomy for structured XBRL tagging of IFRS financial statements, referenced by the SEC for foreign private issuers.

**Human URL:** [https://www.ifrs.org/issued-standards/list-of-standards/](https://www.ifrs.org/issued-standards/list-of-standards/)

#### Tags:

 - IFRS, IASB, International, Financial Reporting, XBRL

#### Properties

- [Documentation](https://www.ifrs.org/issued-standards/list-of-standards/)
- [IFRS Taxonomy via SEC](https://www.sec.gov/data-research/standard-taxonomies/ifrs-taxonomy)

### FASB Accounting Standards Codification
The FASB Accounting Standards Codification (ASC) is the single source of authoritative nongovernmental U.S. GAAP. Organized into Topics, Subtopics, Sections, and Paragraphs, the ASC provides the complete set of accounting guidance for US GAAP.

**Human URL:** [https://asc.fasb.org/](https://asc.fasb.org/)

#### Tags:

 - GAAP, FASB, Codification, US Accounting

#### Properties

- [Documentation](https://asc.fasb.org/)
- [Accounting Standards Updates](https://www.fasb.org/standards/accounting-standard-updates)

### XBRL International Specification
eXtensible Business Reporting Language (XBRL) is an open international standard for digital business reporting maintained by XBRL International. It enables the exchange of business information in a structured, machine-readable format. XBRL is required by the SEC for financial filings and adopted by regulators worldwide.

**Human URL:** [https://www.xbrl.org/](https://www.xbrl.org/)

#### Tags:

 - XBRL, Digital Reporting, Financial Data, Open Standard

#### Properties

- [Documentation](https://www.xbrl.org/)
- [XBRL 2.1 Specification](https://www.xbrl.org/specification/gnl/rec-2003-12-31/gnl-2003-12-31.htm)

## Common Properties

- [Financial Accounting Standards Board](https://www.fasb.org/)
- [IFRS Foundation](https://www.ifrs.org/)
- [XBRL US](https://xbrl.us/)
- [XBRL GitHub Organization](https://github.com/xbrl)
- [SEC EDGAR Data Portal](https://data.sec.gov/)
- [Accounting Standards JSON-LD Context](json-ld/accounting-standards-context.jsonld)
- [Accounting Standards Vocabulary](vocabulary/accounting-standards-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Structured Financial Reporting | XBRL taxonomies enable machine-readable financial statement reporting that regulators, investors, and analysts can process programmatically. |
| US GAAP Codification | The FASB ASC provides the single authoritative source of US GAAP organized by topic for consistent application across entities. |
| International Standards Harmonization | IFRS provides globally harmonized accounting standards enabling cross-border financial comparability in over 140 jurisdictions. |
| Real-Time Financial Data Access | SEC EDGAR XBRL APIs provide real-time access to structured financial data from all public company filings as JSON. |
| Data Quality Rules | The Data Quality Committee Rules Taxonomy (DQCRT) provides machine-enforceable rules for validating XBRL-tagged financial data. |
| Taxonomy Versioning | Annual FASB taxonomy releases incorporate new accounting standards and ensure accurate representation of current GAAP requirements. |

## Use Cases

| Name | Description |
|------|-------------|
| Public Company Financial Reporting | Companies use XBRL taxonomies when filing 10-K, 10-Q, and 8-K reports with the SEC, ensuring structured, machine-readable disclosure. |
| Financial Data Analysis | Investors and analysts use SEC EDGAR XBRL APIs to retrieve structured financial statements for quantitative analysis and screening. |
| Accounting Research | CPAs and finance professionals use the FASB ASC to research applicable US GAAP guidance for specific transaction types and disclosures. |
| Regulatory Compliance | Finance teams implement GAAP or IFRS accounting standards to meet regulatory requirements and auditor expectations. |
| FinTech Integration | FinTech platforms integrate with SEC EDGAR APIs to ingest standardized financial data for valuation models, credit analysis, and benchmarking. |

## Integrations

| Name | Description |
|------|-------------|
| SEC EDGAR | The SEC's public filing database mandating XBRL for financial disclosures, providing free API access to all structured filing data. |
| XBRL US | Industry consortium supporting XBRL adoption in the US, providing taxonomy resources, training, and data quality rule development. |
| iXBRL (Inline XBRL) | Human-readable HTML combining with machine-readable XBRL tags, now required by the SEC for financial statement filings. |
| ESMA / European Reporting | European Securities and Markets Authority mandating IFRS XBRL reporting under the European Single Electronic Format (ESEF). |
| Deloitte DART | Deloitte's Accounting Research Tool providing access to FASB ASC and IFRS standards with interpretive guidance and examples. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [XBRL Financial Fact Schema](json-schema/xbrl-financial-fact-schema.json)
- [Edgar Company Submission Schema](json-schema/edgar-company-submission-schema.json)
- [GAAP Accounting Standard Schema](json-schema/gaap-accounting-standard-schema.json)

### JSON Structure

- [XBRL Financial Fact Structure](json-structure/xbrl-financial-fact-structure.json)
- [Edgar Company Submission Structure](json-structure/edgar-company-submission-structure.json)
- [GAAP Accounting Standard Structure](json-structure/gaap-accounting-standard-structure.json)

### JSON-LD

- [Accounting Standards Context](json-ld/accounting-standards-context.jsonld)

### Examples

- [XBRL Financial Fact Example](examples/xbrl-financial-fact-example.json)
- [Edgar Company Submission Example](examples/edgar-company-submission-example.json)
- [GAAP Accounting Standard Example](examples/gaap-accounting-standard-example.json)

## Vocabulary

- [Accounting Standards Vocabulary](vocabulary/accounting-standards-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 5 actions, 4 workflows, and 5 personas across the accounting standards landscape

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
