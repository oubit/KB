---
order: 100
---

# Kappa arquitecture
- One single infraestructure
- Todo es o será real-time
- Los procesos batch se convierten en real-time:
    - Producer, vía storage.
    - Consumer, leyendo directamente de Kafka
- Kafka se convierte en SPOT. Lo usa como bus de comunicación entre todos los brokers.