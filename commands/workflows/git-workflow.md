# Git Workflow Automation

Automated version control process with branching strategies and commit standards.

## Usage
/git-workflow [action] [description]

## Example
/git-workflow feature "Add user authentication"

## Workflow Steps

1. **Branch Strategy Agent**
   - Create appropriate branch (feature, bugfix, hotfix, release)
   - Follow naming conventions
   - Check for existing branches
   - Set up branch protection if needed

2. **Commit Message Agent**
   - Generate conventional commit messages
   - Follow commit message standards
   - Include scope and description
   - Add breaking changes notes if needed
   - Format: type(scope): description

3. **Code Review Preparation Agent**
   - Generate PR description template
   - List changed files
   - Summarize changes
   - Add testing instructions
   - Include screenshots if UI changes

4. **Quality Checks Agent**
   - Run pre-commit hooks
   - Check for merge conflicts
   - Verify tests pass
   - Check code style
   - Validate commit message format

## Output
- Branch created with proper naming
- Formatted commit messages
- PR template with details
- Quality check report

## Variables
$ARGUMENTS - Action and description (e.g., "feature Add login page")

## Branch Types
- feature/: New features
- bugfix/: Bug fixes
- hotfix/: Critical production fixes
- release/: Release preparation
- chore/: Maintenance tasks

## Commit Types
- feat: New feature
- fix: Bug fix
- docs: Documentation
- style: Code style changes
- refactor: Code refactoring
- test: Test additions/changes
- chore: Build process or auxiliary tool changes

