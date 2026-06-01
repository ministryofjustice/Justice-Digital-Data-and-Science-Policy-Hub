# Justice Digital Data and Science Policy Hub

[![Ministry of Justice Repository Compliance Badge](https://github-community.service.justice.gov.uk/repository-standards/api/template-documentation-site/badge)](https://github-community.service.justice.gov.uk/repository-standards/template-documentation-site)

This repository contains the policies and guidance for the Ministry of Justice Digital, Data and Science division. The documentation site is built using the Government Digital Service's [Technical Documentation Template](https://github.com/alphagov/tech-docs-template), which uses the [tech-docs-gem](https://github.com/alphagov/tech-docs-gem).

---

# Adding a Policy

To contribute a new policy to this hub, follow our [Adding a New Policy guide](source/policies/adding-a-policy.html.md.erb) for step-by-step instructions on using the MoJ Policy Template.

---

# Developing

## Requirements

- Docker

## Previewing locally

Running the following command will run your technical documentation site locally using [ministryofjustice/tech-docs-github-pages-publisher](https://github.com/ministryofjustice/tech-docs-github-pages-publisher), allowing you to access it by visiting <http://127.0.0.1:4567> in your browser

```bash
make preview
```

## Checking links locally

This repository includes a GitHub Actions workflow that uses [Lychee](https://github.com/lycheeverse/lychee) for checking links.

To perform this locally, you will either need to use the dev container or install Lychee, and then run:

```bash
make link-check
```

# Publishing

This template includes a GitHub Actions workflow ([`.github/workflows/publish.yml`](.github/workflows/publish.yml)) for publishing to GitHub Pages when merging to `main`.

# Administration

This repository is managed by the [JDDS Policy Hub Admin team](https://github.com/orgs/ministryofjustice/teams/jdds-policy-hub-admins).

For questions about policies, documentation, or repository maintenance, please contact:

- **Email**: DigitalStandards@justice.gov.uk
- **Slack**: #standards-team
