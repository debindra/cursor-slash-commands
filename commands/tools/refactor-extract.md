# Refactor Extract Tool

Extract code into reusable components, functions, or modules.

## Usage
/refactor-extract [extraction type] [target code]

## Example
/refactor-extract function calculateTotal from checkout logic

## Extraction Types

1. **Extract Function**
   - Extract method/function
   - Identify parameters
   - Handle return values
   - Update call sites

2. **Extract Component**
   - Extract React/Vue component
   - Identify props
   - Handle state
   - Update imports

3. **Extract Class**
   - Extract class/module
   - Identify responsibilities
   - Define interfaces
   - Update dependencies

4. **Extract Service**
   - Extract service layer
   - Define service interface
   - Handle dependencies
   - Update consumers

## Output
- Extracted code in new file
- Updated original file
- Updated imports/exports
- Documentation
- Test updates

## Variables
$ARGUMENTS - Extraction type and target code

## Refactoring Principles
- Single Responsibility Principle
- DRY (Don't Repeat Yourself)
- Separation of Concerns
- Dependency Inversion

## Safety Measures
- Preserve functionality
- Update all references
- Maintain test coverage
- Add documentation

