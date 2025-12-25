# Kubernetes Manifest Tool

Generate production-ready Kubernetes manifests with best practices.

## Usage
/k8s-manifest [service name] [requirements]

## Example
/k8s-manifest user-service with autoscaling and health checks

## Manifest Types

1. **Deployment**
   - Container configuration
   - Replica sets
   - Rolling update strategy
   - Resource limits

2. **Service**
   - Service type (ClusterIP, LoadBalancer, NodePort)
   - Port configuration
   - Selector labels

3. **ConfigMap & Secrets**
   - Configuration management
   - Environment variables
   - Secret handling

4. **Horizontal Pod Autoscaler (HPA)**
   - CPU/Memory-based scaling
   - Custom metrics
   - Min/max replicas

5. **Ingress**
   - Routing rules
   - SSL/TLS configuration
   - Load balancing

6. **Network Policies**
   - Pod-to-pod communication
   - Security policies

## Output
- Deployment manifest
- Service manifest
- ConfigMap/Secrets
- HPA configuration
- Ingress configuration
- Network policies
- Documentation

## Variables
$ARGUMENTS - Service name and requirements

## Best Practices Applied
- Resource limits and requests
- Health checks (liveness, readiness)
- Security contexts
- Pod disruption budgets
- Affinity/anti-affinity rules
- Persistent volumes if needed

## Production Features
- Autoscaling
- Health checks
- Resource management
- Security policies
- Monitoring integration
- Logging configuration

