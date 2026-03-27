<p align="center">
  <img src="https://raw.githubusercontent.com/mokoconsulting-tech/MokoStandards/main/templates/images/primary/logo.png" alt="Moko Consulting" width="300">
</p>

# Moko Consulting

**Enterprise-grade software standards, automation, and governance for modern development teams.**

We build and maintain open-source tools that help organizations enforce coding standards, automate workflows, and manage repositories at scale.

## What We Do

- **MokoStandards** — Authoritative source of coding standards, workflow templates, and governance policies for all our repositories
- **Dolibarr Modules** — Custom CRM extensions for [Dolibarr ERP/CRM](https://www.dolibarr.org)
- **Joomla Extensions** — Web-as-a-Service (WaaS) components for [Joomla CMS](https://www.joomla.org)
- **Automation Tools** — PHP-based CLI tools for repository management, deployment, and compliance

## Our Standards

Every repository in this organization is governed by [MokoStandards](https://github.com/mokoconsulting-tech/MokoStandards):

- **6-tier enforcement system** for file synchronization
- **54 standard labels** across all repositories
- **Three-environment deploy pipeline** (dev → demo → RS) via SFTP
- **Auto-versioning** with patch bumps on every merge to main
- **Auto-release** with GitHub Releases and git tags
- **Bulk sync** to push standards updates across 45+ repositories

## Key Repositories

| Repository | Description |
|------------|-------------|
| [MokoStandards](https://github.com/mokoconsulting-tech/MokoStandards) | Standards, policies, and automation — the source of truth |
| [MokoCRM](https://github.com/mokoconsulting-tech/MokoCRM) | Dolibarr CRM module |
| [MokoCassiopeia](https://github.com/mokoconsulting-tech/MokoCassiopeia) | Joomla Cassiopeia template customization |
| [MokoJoomTOS](https://github.com/mokoconsulting-tech/MokoJoomTOS) | Joomla Terms of Service module |

## Tech Stack

- **PHP 8.1+** — All automation, validation, and deployment tools
- **GitHub Actions** — CI/CD, compliance checks, automated releases
- **SFTP via phpseclib3** — Secure deployment to dev/demo/RS servers
- **Terraform-style definitions** — Repository structure as code

## Contact

- **Email**: hello@mokoconsulting.tech
- **GitHub**: [@mokoconsulting-tech](https://github.com/mokoconsulting-tech)

---

*All repositories follow the [MokoStandards](https://github.com/mokoconsulting-tech/MokoStandards) governance framework.*
