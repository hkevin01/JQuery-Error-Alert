# Workflow

## Branching Strategy
- Use `main` for stable releases
- Use `dev` for ongoing development
- Feature branches: `feature/<name>`
- Bugfix branches: `bugfix/<name>`
- Pull requests required for merging to `main`

## CI/CD Pipeline
- GitHub Actions for build, test, and deploy
- Lint and format checks on every push
- Automated deployment for tagged releases

## Code Review Process
- All changes via pull requests
- At least one approval required
- Automated checks must pass before merge
- Use issue templates for bug reports and feature requests

## Development Workflow
1. Fork and clone the repo
2. Create a feature branch
3. Make changes and commit
4. Push branch and open a pull request
5. Address review comments
6. Merge after approval

## Issue Tracking
- Use GitHub Issues for bugs and features
- Label issues for priority and type
