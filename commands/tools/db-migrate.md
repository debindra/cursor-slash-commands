# Database Migrate Tool

Generate database migrations with best practices and rollback support.

## Usage
/db-migrate [migration description]

## Example
/db-migrate add user preferences table with foreign key to users

## Features

1. **Migration Generation**
   - Up migration (forward)
   - Down migration (rollback)
   - Version control
   - Timestamp-based naming

2. **Schema Changes**
   - Table creation/modification
   - Column additions/modifications
   - Index creation
   - Foreign key constraints
   - Data type changes

3. **Data Migrations**
   - Data transformation
   - Data seeding
   - Data backfill
   - Safe data migration patterns

4. **Best Practices**
   - Zero-downtime migrations
   - Backward compatibility
   - Rollback strategies
   - Migration testing

## Output
- Migration files (up and down)
- Schema changes
- Data migration scripts
- Rollback scripts
- Migration documentation

## Variables
$ARGUMENTS - Migration description

## Supported Databases
- PostgreSQL
- MySQL/MariaDB
- SQLite
- MongoDB
- SQL Server
- Oracle

## Migration Patterns
- Expand-contract pattern
- Blue-green deployment
- Feature flags
- Dual writes
- Backfill strategies

