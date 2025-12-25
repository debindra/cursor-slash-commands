# Monitor Setup Tool

Set up comprehensive observability with metrics, logging, and alerting.

## Usage
/monitor-setup [service name] [monitoring type]

## Example
/monitor-setup user-service with Prometheus and Grafana

## Features

1. **Metrics Setup**
   - Prometheus configuration
   - Custom metrics definition
   - Metric collection endpoints
   - Exporters configuration

2. **Logging Setup**
   - Structured logging configuration
   - Log aggregation setup
   - Log levels configuration
   - Log rotation policies

3. **Tracing Setup**
   - Distributed tracing
   - Trace sampling
   - Trace export configuration
   - Service map generation

4. **Alerting Setup**
   - Alert rules definition
   - Alert routing
   - Notification channels
   - Alert thresholds

5. **Dashboards**
   - Grafana dashboard creation
   - Custom visualizations
   - Dashboard templates
   - Key metrics visualization

## Output
- Monitoring configuration files
- Dashboard definitions
- Alert rules
- Logging configuration
- Documentation

## Variables
$ARGUMENTS - Service name and monitoring type

## Supported Tools
- Metrics: Prometheus, Datadog, New Relic
- Logging: ELK Stack, Loki, CloudWatch
- Tracing: Jaeger, Zipkin, OpenTelemetry
- Dashboards: Grafana, Datadog, New Relic

## Monitoring Types
- Application metrics
- Infrastructure metrics
- Business metrics
- Error tracking
- Performance monitoring

