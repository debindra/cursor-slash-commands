# Dependencies Upgrade Tool

Safely upgrade project dependencies with compatibility checking.

## Usage
/deps-upgrade [package name or "all"]

## Example
/deps-upgrade react

## Features

1. **Dependency Analysis**
   - Check current versions
   - Find available updates
   - Identify security vulnerabilities
   - Check compatibility matrix

2. **Upgrade Strategy**
   - Major version upgrades (breaking changes)
   - Minor version upgrades (features)
   - Patch version upgrades (fixes)
   - Dependency resolution

3. **Compatibility Checking**
   - Check peer dependencies
   - Verify API compatibility
   - Test breaking changes
   - Update related packages

4. **Safety Measures**
   - Create backup
   - Generate migration guide
   - Test after upgrade
   - Rollback plan

## Output
- Updated package files
- Compatibility report
- Breaking changes documentation
- Migration guide
- Test results

## Variables
$ARGUMENTS - Package name or "all"

## Supported Package Managers
- npm/yarn/pnpm (Node.js)
- pip/poetry (Python)
- Maven/Gradle (Java)
- NuGet (C#)
- Cargo (Rust)
- Go modules

## Upgrade Types
- Patch: Bug fixes (1.0.0 → 1.0.1)
- Minor: New features (1.0.0 → 1.1.0)
- Major: Breaking changes (1.0.0 → 2.0.0)

