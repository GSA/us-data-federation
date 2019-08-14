---
layout: page
title: Tools
permalink: /tools/
---

## The U.S. Data Federation is curating and creating reusable tools to support data validation, automated aggregation, and the development and documentation of data specifications.

### ReVAL - Reusable Validation & Aggregation Library

The first tool prototyped through this effort is a reusable Django App for validating and aggregating data via API and web interface.

For the web interface, it can manage data submitted as file uploads to a central gathering point, and it can perform data validation, basic change tracking and duplicate file handling. Each file generally contains multiple data rows, and each user may submit multiple files.

For the API, it can perform data validation, and view uploads that were done via the web interface.

Learn more about the tool and track its development on [GitHub](https://github.com/18F/ReVAL)

#### Features

- Flexible input format
- Validation with:
  - goodtables
  - JSON Logic
  - SQL
  - JSON Schema
  - a custom validation class
- Row-by-row feedback on validation results
- Manage and track status of data submissions
- Re-submit previous submissions
- Flexible ultimate destination for data
- API for validation

#### Requirements

- Python (3.5, 3.6)
- Django (1.11)
- Goodtables
- pyyaml
- djangorestframework
- psycopg2
- json_logic_qubit
- dj-database-url
- requests
