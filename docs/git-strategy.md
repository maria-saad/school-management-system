# Git Branching Strategy & Commit Conventions

## Branches
- `main`: stable, production-ready
- `develop`: integration branch
- `feature/*`: feature branches per Jira ticket, e.g. `feature/EPIC-01-auth-login`

## Commit Messages (Conventional Commits + Jira key)
Format:
`type(SCHL-XX): short description`

Examples:
- `feat(SCHL-38): add /auth/login endpoint`
- `fix(SCHL-52): correct rate limiting config`
- `chore: bump dependencies`
