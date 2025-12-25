# Quick Reference Guide

## Workflow Commands

| Command | Usage | Example |
|---------|-------|---------|
| `feature-development` | End-to-end feature implementation | `/workflows:feature-development implement user authentication` |
| `smart-fix` | Intelligent problem resolution | `/workflows:smart-fix Fix memory leak in component` |
| `full-review` | Comprehensive code review | `/workflows:full-review src/components/UserProfile.tsx` |
| `tdd-cycle` | Test-driven development | `/workflows:tdd-cycle create email validator` |
| `legacy-modernize` | Modernize legacy code | `/workflows:legacy-modernize src/utils/oldHelpers.js` |
| `git-workflow` | Git automation | `/workflows:git-workflow feature "Add login page"` |
| `api-design` | Complete API design | `/workflows:api-design users CRUD operations` |
| `improve-agent` | Agent optimization | `/workflows:improve-agent Optimize code review agent` |
| `multi-platform` | Cross-platform dev | `/workflows:multi-platform user auth web, iOS, Android` |
| `workflow-automate` | CI/CD automation | `/workflows:workflow-automate CI/CD with testing` |
| `data-driven-feature` | ML/data features | `/workflows:data-driven-feature recommendation system` |

## Tool Commands

| Command | Usage | Example |
|---------|-------|---------|
| `api-scaffold` | Generate RESTful APIs | `/tools:api-scaffold products CRUD` |
| `security-scan` | Security vulnerability scan | `/tools:security-scan src/api/` |
| `test-generate` | Generate test suites | `/tools:test-generate src/utils/calculator.js` |
| `docker-optimize` | Optimize Dockerfiles | `/tools:docker-optimize Dockerfile` |
| `performance-analyze` | Performance analysis | `/tools:performance-analyze src/components/DataTable.tsx` |
| `doc-generate` | Generate documentation | `/tools:doc-generate src/api/` |
| `db-migrate` | Database migrations | `/tools:db-migrate add user preferences table` |
| `refactor-extract` | Extract reusable code | `/tools:refactor-extract function calculateTotal` |
| `k8s-manifest` | Kubernetes manifests | `/tools:k8s-manifest user-service with autoscaling` |
| `code-format` | Format code | `/tools:code-format src/utils/helpers.js` |
| `deps-upgrade` | Upgrade dependencies | `/tools:deps-upgrade react` |
| `env-setup` | Environment configuration | `/tools:env-setup production` |
| `ci-cd-setup` | CI/CD pipeline setup | `/tools:ci-cd-setup github-actions` |
| `component-generate` | Generate UI components | `/tools:component-generate UserCard functional` |
| `monitor-setup` | Observability setup | `/tools:monitor-setup user-service with Prometheus` |
| `cost-optimize` | Cloud cost optimization | `/tools:cost-optimize AWS infrastructure` |
| `data-pipeline` | Data processing | `/tools:data-pipeline ETL from S3 to Redshift` |
| `data-validation` | Data validation | `/tools:data-validation user registration data` |
| `tdd-red` | TDD Red phase | `/tools:tdd-red create shipping calculator` |
| `tdd-green` | TDD Green phase | `/tools:tdd-green implement to pass tests` |
| `tdd-refactor` | TDD Refactor phase | `/tools:tdd-refactor optimize code` |
| `context-save` | Save context | `/tools:context-save authentication-feature` |
| `context-restore` | Restore context | `/tools:context-restore authentication-feature` |
| `bundle-analyze` | Bundle analysis | `/tools:bundle-analyze dist/` |
| `lint-setup` | Linting config | `/tools:lint-setup TypeScript with strict rules` |

## Common Workflows

### New Feature Development
```
/workflows:feature-development implement [feature description]
/tools:test-generate [new files]
/tools:security-scan [new code]
/tools:doc-generate [new code]
```

### Code Quality Check
```
/workflows:full-review [file or directory]
/tools:performance-analyze [file]
/tools:code-format [file]
```

### Bug Fix
```
/workflows:smart-fix [problem description]
/tools:test-generate [fixed code]
```

### Modernization
```
/workflows:legacy-modernize [target]
/tools:deps-upgrade all
/tools:test-generate [updated code]
```

## Tips

1. **Be Specific**: Provide detailed requirements for better results
2. **Chain Commands**: Use workflows first, then refine with tools
3. **Review Output**: Always review generated code before committing
4. **Test First**: Run tests after using code generation commands
5. **Security First**: Run security-scan on new code

