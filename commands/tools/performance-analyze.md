# Performance Analyze Tool

Analyze and optimize code performance with profiling and recommendations.

## Usage
/performance-analyze [file path or "current file"]

## Example
/performance-analyze src/components/DataTable.tsx

## Analysis Types

1. **Code Complexity Analysis**
   - Time complexity (Big O)
   - Space complexity
   - Cyclomatic complexity
   - Algorithm efficiency

2. **Performance Bottlenecks**
   - Slow operations identification
   - Memory leak detection
   - Unnecessary re-renders (React)
   - Database query optimization
   - Network request optimization

3. **Bundle Analysis**
   - Bundle size analysis
   - Code splitting opportunities
   - Tree shaking potential
   - Dependency size analysis

4. **Runtime Profiling**
   - Function execution times
   - Memory usage patterns
   - CPU usage analysis
   - I/O operation analysis

## Output
- Performance analysis report
- Bottleneck identification
- Optimization suggestions
- Before/after metrics
- Code improvements

## Variables
$ARGUMENTS - File path or "current file"

## Optimization Strategies
- Algorithm optimization
- Caching strategies
- Lazy loading
- Code splitting
- Memoization
- Debouncing/throttling
- Database query optimization

## Metrics Provided
- Execution time
- Memory usage
- Bundle size
- Complexity scores
- Optimization potential

