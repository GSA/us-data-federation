---
layout: page
title: Tools
permalink: /tools/
---

## The U.S. Data Federation wants to curate and create reusable tools to support federated data efforts. The reusable tools are intended to include capabilities around data validation, automated aggregation, and the development and documentation of data specifications.

### **Django Data Ingest**

The first tool prototyped through this effort is a reusable Django project that manages data submitted as file uploads to a central gathering point. It performs data validation, basic change tracking, and duplicate file handling.

Learn more about the tool and track its development on [GitHub](https://github.com/18F/django-data-ingest/blob/master/README.md).

#### Features

- Flexible input format
- Validation with goodtables, JSON Schema, SQL, or a custom validation class
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
