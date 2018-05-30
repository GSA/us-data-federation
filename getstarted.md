---
layout: page
title: Get started
permalink: /getstarted/
---

# Installation

To get started, visit the **[Github repository](https://github.com/18F/django-data-ingest)** to install the tool locally on your machine.  

Current features include:

- Flexible input format
- Validation with goodtables, JSON Schema, or a custom validation class
- Row-by-row feedback on validation results
- Manage and track status of data submissions
- Re-submit previous submissions
- Flexible ultimate destination for data

Instructions on how to set up your own validation engine will guide you through the process of setting up the ingest tool for your own datasets.  

# Easily customizable

The **Federated Data Ingest Tool** is an open source prototype, easily customizable for a number of use cases.  This means data managers to create a data schema that users can then easily upload and validate data against, correcting any errors as they go.

# GUI and API support

The Ingest Tool can also be built into a GUI interface or operate behind the scenes via an API.  The tool will ingest a file, compare the file to a set of customizable validation rules, and return errors to the user to fix before submitting a final file for review.  The tool can also help agencies verify larger, aggregated datasets containing submissions from a number of external parties.

# Free and open source

The tool is available under an open source license, so you are free to use it without incurring licensing costs.

# Become a contributor

Help us make the tool even better by [becoming a contributor](https://github.com/18F/django-data-ingest)!
