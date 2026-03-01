# Lab M4.10 - Terraform Git Workflows

## Workflow
1. Create feature branch
2. Make infrastructure changes
3. Push and open PR
4. GitHub Actions runs format, validate, plan
5. Review plan output in PR comment
6. Merge to main

## CI/CD Pipeline
- **Format check** — ensures consistent code style
- **Validate** — catches syntax errors
- **Plan** — shows proposed changes on PRs

## Repository Structure
```
├── .github/workflows/terraform.yml
├── .github/pull_request_template.md
├── .gitignore
├── main.tf
├── variables.tf
└── outputs.tf
```
