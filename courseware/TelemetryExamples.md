# Telemetry Examples with the GitHub CLI

## Update token to have property Copilot permissions

```bash
gh auth refresh -h github.com -s copilot
```

## Get Copilot Business seat information and settings for an organization

```bash
gh api -H "Accept: application/vnd.github+json" -H "X-GitHub-Api-Version: 2022-11-28" /orgs/Atmosera-CoPilot-Dev/copilot/billing
```

## List all Copilot Business seat assignments for an organization

```bash
gh api -H "Accept: application/vnd.github+json" -H "X-GitHub-Api-Version: 2022-11-28" /orgs/Atmosera-CoPilot-Dev/copilot/billing/seats
```

## Get Copilot Business seat assignment details for a user

```bash
gh api -H "Accept: application/vnd.github+json" -H "X-GitHub-Api-Version: 2022-11-28" /orgs/Atmosera-CoPilot-Dev/members/mickknutson/copilot
```