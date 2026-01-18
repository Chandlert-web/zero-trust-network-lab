# Network Security Zones

This directory defines the security zones used in the Zero Trust Network Segmentation Lab.

Each zone represents a distinct trust boundary with explicitly defined access rules.

---

## Defined Zones

### User Zone
- End-user devices
- Limited access to required services only
- No implicit access to management or infrastructure networks

### Server Zone
- Application and service infrastructure
- Access restricted to required ports and sources
- No direct access from user devices without explicit policy

### Management Zone
- Administrative systems and interfaces
- Highly restricted access
- Accessible only from approved sources

### Monitoring Zone
- Monitoring and observability systems
- Receives telemetry from other zones
- No inbound access from user networks
