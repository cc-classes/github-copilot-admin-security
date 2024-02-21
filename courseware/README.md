# GitHub Copilot for Business Administration and Security Courseware

Welcome to the GitHub Copilit for Business Administration and Security training! The following content is the courseware for this course. The content mixes official GitHub content (slide deck) and instructor-created materials. All materials are for registered course attendees only.

First, here is the official GitHub Copilot for Business Developers slide deck. The slide deck will drive the class, and we will occasionally reference the materials in this document.

- [Official GitHub Slides](./GithubCopilotForBusinessAdministrationAndSecuritySlides.pdf)

## GitHub Administration Links

- [GitHub Enterprise Copilot Settings](https://github.com/enterprises/atmosera-partner-demo/settings/copilot)
  - Access Management
  - Policies
- [GitHub Organization Settings](https://github.com/organizations/Atmosera-CoPilot-Dev/settings/profile)
  - [Access Management](https://github.com/organizations/Atmosera-CoPilot-Dev/settings/copilot/seat_management)
  - [Policies and features](https://github.com/organizations/Atmosera-CoPilot-Dev/settings/copilot/policies)
  - [Content exclusion](https://github.com/organizations/Atmosera-CoPilot-Dev/settings/copilot/content_exclusion)
  - [Sample Seat Usage Report](./Example-seat-usage-1708511191.csv)

## GitHub Copilot Local Environment Configuration

- Copilot Extension in VSCode
- [In Your Environment](https://docs.github.com/en/copilot/configuring-github-copilot/configuring-github-copilot-in-your-environment)
- [GitHub Copilot FAQ](https://github.com/features/copilot/#faq)
- [Using GitHub Copilot in the CLI](https://docs.github.com/en/copilot/github-copilot-in-the-cli/using-github-copilot-in-the-cli)

## Telemetry

- [Telemetry API](https://docs.github.com/en/enterprise-cloud@latest/rest/copilot/copilot-business?apiVersion=2022-11-28)
- [Personal Access Tokens](https://github.com/settings/tokens)
- [New Personal Access Token](https://github.com/settings/tokens/new)
- [REST API Telemetry Examples](./TelemetryExamples.rest)
- [GitHub CLI Telemetry Examples](./TelemetryExamples.md)
- [Troubleshooting in Editors](https://docs.github.com/en/copilot/troubleshooting-github-copilot/viewing-logs-for-github-copilot-in-your-environment)
- See Audit Examples below for more information

## Data Privacy

- [GitHub Copilot Business Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-copilot-business-privacy-statement)
- [What data does GitHub use to create a Contextual Prompt?](https://github.com/features/copilot#faq)
- [Prompt Process Flow](https://learn.microsoft.com/en-us/training/modules/introduction-prompt-engineering-with-github-copilot/3-github-copilot-user-prompt-process-flow)
- [Copilot Business vs. Individual](https://learn.microsoft.com/en-us/training/modules/introduction-to-github-copilot-for-business/2-about-github-copilot-business)
- [Copilot for Azure Data Studio](https://techcommunity.microsoft.com/t5/azure-sql-blog/introducing-github-copilot-for-azure-data-studio/ba-p/3829511)
- [Microsoft Docs: GitHub Copilot for Azure Data Studio](https://learn.microsoft.com/en-us/azure-data-studio/extensions/github-copilot-extension-overview)
- [GitHub Copilot for Your Codebase](https://githubnext.com/projects/copilot-view/)
- [How GitHub Copilot is getting better at understanding your code](https://github.blog/2023-05-17-how-github-copilot-is-getting-better-at-understanding-your-code/)

## Integrations

- [GitHub Organization Audit Logs](https://github.com/organizations/Atmosera-CoPilot-Dev/settings/audit-log)
  - Example 1: `action:copilot.cfb_seat_added`
  - Example 2: `action:copilot.cfb_org_settings_changed`
- [GitHub Enterprise Audit Logs](https://github.com/enterprises/atmosera-partner-demo/settings/audit-log)
  - Example 1: `action:copilot.cfb_seat_added`
  - Example 2: `action:copilot.cfb_org_settings_changed`

## FAQ

1. **When using GitHub Copilot in Azure Data Studio is the database data or schema sent to GitHub to generate the suggestions?**
      - When using GitHub Copilot in Azure Data Studio, the database data or schema is not sent to GitHub to generate the suggestions. GitHub Copilot operates locally within your development environment, analyzing the code you write and providing context-aware suggestions based on patterns, comments, and existing code in your project.
2. **When a user is assigned GitHub Copilot seat in multiple organizations, how is the seat usage calculated?**
      - The seat usage is calculated based on the number of unique users who have been assigned a seat in the organization. If a user is assigned a seat in multiple organizations, they will only be counted once.
