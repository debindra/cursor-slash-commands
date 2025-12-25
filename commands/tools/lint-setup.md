# Lint Setup Tool

Configure comprehensive linting and code quality tools.

## Usage
/lint-setup [language/framework] [rules]

## Example
/lint-setup TypeScript with strict rules and Prettier

## Features

1. **Linter Configuration**
   - ESLint for JavaScript/TypeScript
   - Pylint for Python
   - RuboCop for Ruby
   - golangci-lint for Go
   - Clippy for Rust

2. **Code Formatting**
   - Prettier integration
   - EditorConfig
   - Format on save
   - Format on commit

3. **Rule Sets**
   - Framework-specific rules
   - Custom rule configuration
   - Rule severity levels
   - Disable rules where needed

4. **Integration**
   - Editor integration
   - Pre-commit hooks
   - CI/CD integration
   - IDE plugins

## Output
- Linter configuration files
- Formatter configuration
- Pre-commit hooks
- CI/CD integration
- Documentation

## Variables
$ARGUMENTS - Language/framework and rules

## Supported Linters
- JavaScript/TypeScript: ESLint, TSLint
- Python: Pylint, Flake8, Black
- Ruby: RuboCop
- Go: golangci-lint
- Rust: Clippy
- Java: Checkstyle, PMD

## Code Quality Tools
- Prettier (formatting)
- EditorConfig (editor settings)
- Husky (git hooks)
- lint-staged (staged file linting)

