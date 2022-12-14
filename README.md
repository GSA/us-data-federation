[![GitHub Actions](https://github.com/GSA/us-data-federation/actions/workflows/build.yml/badge.svg)](https://github.com/GSA/us-data-federation/actions/workflows/build.yml)
[![GitHub Actions](https://github.com/GSA/us-data-federation/actions/workflows/qa.yml/badge.svg)](https://github.com/GSA/us-data-federation/actions/workflows/qa.yml)

# us-data-federation

U.S. Data Federation website

## Usage

## Development

### Requirements

-   [Ruby](https://www.ruby-lang.org/en/) > 2.7
-   [Bundler](https://bundler.io/)

### Setup

After you've confirmed you have Ruby > 2.7 (`ruby --version`) and Bundler (`bundle --version`) installed, all lifecycle operations can be run with Make commands (ex `make install`).

| Make Command | Alias for                                    | Description                                                |
| ------------ | -------------------------------------------- | ---------------------------------------------------------- |
| install      | `bundle install`                             | Install dependencies (pinned in Gemfile.lock, if it exists |
| update       | `bundle update`                              | Update installed dependencies; Reacreate Gemfile.lock      |
| build        | `bundle exec jekyll build`                   | Build the site                                             |
| serve        | `bundle exec jekyll serve`                   | Serve a local build                                        |
| testlinks    | `bundle exec htmlproofer --check-html _site` | Check for broken links                                     |

## Contributing

See [CONTRIBUTING](CONTRIBUTING.md) for additional information.

This site is automatically published based on the branch.

| Branch    | Environment | URL                                                                 | Description                                                          |
| --------- | ----------- | ------------------------------------------------------------------- | -------------------------------------------------------------------- |
| `develop` | staging     | [federation-staging.data.gov](https://federation-staging.data.gov/) | Ad-hoc development and significant changes requiring partner review. |
| `main`    | production  | [federation.data.gov](https://federation.data.gov/)                 | Production instance.                                                 |

Federalist automatically builds previews for all branches. Changes to `main` are
automatically published to [federation.data.gov](https://federation.data.gov/).
Feature branches should be branched from `main`.

`develop` is used ad-hoc in order to preview significant changes with partners
and is not part of the development workflow.

## Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
