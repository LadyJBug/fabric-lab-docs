# fabric-lab-docs

Dummy enterprise-style data and files for testing Microsoft Fabric features.

## Purpose

This repository provides realistic, non-sensitive sample content that can be used to test common Microsoft Fabric scenarios, including:

- Lakehouse file ingestion (CSV, JSON Lines, TXT)
- Data Warehouse modeling across related business domains
- Dataflow / notebook transformations
- Security and governance testing with mixed structured and unstructured data

## Sample dataset

Path: `sample-data/enterprise-core/`

- `sales/customers.csv` - customer master data
- `sales/orders.csv` - sales transactions
- `finance/invoices.csv` - invoice and payment status data
- `hr/employees.csv` - workforce dimension data
- `it/security_events.jsonl` - semi-structured security event records
- `documents/vendor-contract-summary.txt` - unstructured enterprise document

## Data principles

- All content is synthetic dummy data.
- No secrets, credentials, or personal sensitive data are included.
- IDs are intentionally cross-linked to support joins and lineage testing.
