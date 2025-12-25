# Docker Optimize Tool

Optimize Dockerfiles for size, build time, and security.

## Usage
/docker-optimize [dockerfile path or "current"]

## Example
/docker-optimize Dockerfile

## Optimizations

1. **Multi-Stage Builds**
   - Separate build and runtime stages
   - Reduce final image size
   - Remove build dependencies

2. **Layer Caching**
   - Optimize layer order
   - Minimize cache invalidation
   - Use .dockerignore effectively

3. **Base Image Optimization**
   - Use minimal base images (Alpine, distroless)
   - Remove unnecessary packages
   - Use specific version tags

4. **Security Hardening**
   - Run as non-root user
   - Scan for vulnerabilities
   - Use minimal attack surface
   - Add security labels

5. **Build Performance**
   - Parallel operations
   - Cache mount optimization
   - Build argument optimization

## Output
- Optimized Dockerfile
- .dockerignore file
- Build optimization report
- Size reduction metrics
- Security improvements

## Variables
$ARGUMENTS - Dockerfile path or "current"

## Optimization Metrics
- Image size reduction (typically 50-90%)
- Build time improvement
- Security score
- Layer count reduction

## Best Practices Applied
- Multi-stage builds
- Minimal base images
- Non-root user
- Health checks
- Proper signal handling
- Resource limits

