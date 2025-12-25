# Code Format Tool

Format code according to project standards and best practices.

## Usage
/code-format [file path or "current file"]

## Example
/code-format src/utils/helpers.js

## Formatting Features

1. **Code Style**
   - Indentation (tabs/spaces)
   - Line length
   - Trailing whitespace
   - Blank lines

2. **Import Organization**
   - Import sorting
   - Import grouping
   - Unused import removal

3. **Code Structure**
   - Function ordering
   - Class member ordering
   - Consistent spacing

4. **Language-Specific**
   - JavaScript/TypeScript: ESLint, Prettier
   - Python: Black, autopep8
   - Java: Google Java Format
   - C#: dotnet format

## Output
- Formatted code
- Formatting report
- Configuration file updates
- Style guide recommendations

## Variables
$ARGUMENTS - File path or "current file"

## Supported Formatters
- JavaScript/TypeScript: Prettier, ESLint
- Python: Black, autopep8, isort
- Java: Google Java Format
- C#: dotnet format
- Go: gofmt, goimports
- Rust: rustfmt

## Configuration
- Detects existing formatter config
- Creates config if missing
- Respects project standards
- Customizable rules

