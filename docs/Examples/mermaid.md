#  Mermaid Examples

## Topology

```mermaid
graph LR
    A[192.168.1.0/24] --> R1(R1)
    R1 -->|10.0.1.0/24| R2(R2)
    R2 --> B[192.168.2.0/24]
```
