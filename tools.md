---
layout: page
title: Tools
permalink: /tools/
---

The U.S. Data Federation will be documenting existing tools and developing new ones to support federated data efforts. The first tool being prototyped is the Federated Data Ingest Tool. 

# The Federated Data Ingest Tool 

Easily upload, validate and standardize data across all levels of government.  Better data, with less hassle.

## Step one: Download and install the tool

To get started, visit the **[Github repository](https://github.com/18F/django-data-ingest)** to install the tool locally on your machine.  

Current features include:

- Flexible input format
- Validation with goodtables, JSON Schema, or a custom validation class
- Row-by-row feedback on validation results
- Manage and track status of data submissions
- Re-submit previous submissions
- Flexible ultimate destination for data

## Step two: Set up your own custom validator

Instructions on how to set up your own validation engine will guide you through the process of setting up the ingest tool for your own datasets.  The validator will be used to compare files submitted to a set of rules.  These can be rather simple checks, like making sure dates are present in date fields, or more complex, like comparing values between fields that fall within a certain range.

## Step three: Deploy and share your ingest tool with your users

Once the validator is created, the ingest tool can be set up as either a custom URL that you can share with your users to upload and process files, or as an API that will sit ontop of an existing system.  

If errors in submitted files, the errors will be shared with the user in real time.  Users can then make the necessary corrections and submit the cleaned file for processing.

## Other features

### Easily customizable

The **Federated Data Ingest Tool** is an open source prototype, easily customizable for a number of use cases.  This means data managers to create a data schema that users can then easily upload and validate data against, correcting any errors as they go.

### GUI and API support

The Ingest Tool can also be built into a GUI interface or operate behind the scenes via an API.  The tool will ingest a file, compare the file to a set of customizable validation rules, and return errors to the user to fix before submitting a final file for review.  The tool can also help agencies verify larger, aggregated datasets containing submissions from a number of external parties.

### Free and open source

The tool is available under an open source license, so you are free to use it without incurring licensing costs.

## Become a contributor

Help us make the tool even better by [becoming a contributor](https://github.com/18F/django-data-ingest)!
