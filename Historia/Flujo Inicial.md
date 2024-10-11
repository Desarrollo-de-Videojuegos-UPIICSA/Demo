# Flujo Inical
Este es el flujo inicial del videojuego de Adpocalypse.

## Nuevo Juego
```mermaid
stateDiagram
    [*] --> CI
    CI --> CN
    CN --> LG
    LG --> MN
    MN --> OpSTRT
    OpSTRT --> [*]
```

### Explicacion
- CI: Creditos Iniciales.
- CN: Cinemetica.
- MN: Menu.
- OpSTRT: El judaor selecciona Iniciar Nueva Partida

---
