##  Financiamiento

Este proyecto se financia combinando dos fuentes: una beca de la red Stellar y un mecanismo de pagos continuos para código abierto.

| Fuente | Tipo | Red | Estado |
|---|---|---|---|
| [Stellar Community Fund](https://stellar.gitbook.io/scf-handbook/scf-awards/build-award) | Beca por hitos | Stellar/Soroban | En postulación |
| [Drips Protocol](https://docs.drips.network/) | Streaming continuo | Ethereum/EVM | Pendiente de reclamo |

### Stellar Community Fund (SCF)

Beca oficial de la Stellar Development Foundation para proyectos construidos sobre Stellar/Soroban. Versión vigente: **SCF 7.0**.

- **Monto:** hasta 150,000 USD, pagados en XLM
- **Modalidad:** 4 tramos ligados a hitos (~4-6 meses hasta Mainnet)
- **Categorías:** Open · Integration · RFP
- **Requisito clave:** el uso de Stellar/Soroban debe ser genuino, no forzado
- **Restricción:** no aplica si el proyecto ya recibe fondos activos de programas con objetivos similares (Matching Fund, Enterprise Fund, etc.)




### Drips Protocol

Protocolo de financiamiento continuo para proyectos open source, conectado a GitHub. Corre sobre Ethereum, Optimism, Metis y Filecoin — **no sobre Stellar**.

**Para reclamar este repositorio y recibir fondos:**

1. Agregar `FUNDING.json` en la rama principal con la dirección Ethereum a verificar on-chain.
2. Tener una wallet con ETH para el gas del reclamo.
3. Definir el porcentaje de reparto entre mantenedores y dependencias.

>  **Nota:** el streaming continuo de Drips no opera nativamente en Stellar/Soroban. La única integración confirmada es **Drips Wave** (recompensas semanales por resolver issues, pagadas en Stellar) — distinta del streaming por dependencias.

### Roadmap de financiamiento por fase

| Fase | Entregable | Fuente |
|---|---|---|
| 1. Fundación | MVP en testnet | SCF Build (tramo 1) |
| 2. Comunidad | Issues abiertos a colaboradores | Drips Wave |
| 3. Mainnet | Despliegue final | SCF Build (tramos 3-4) |
| 4. Sostenibilidad | Mantenimiento continuo | Drip List (Ethereum/EVM) |

### Pendiente por confirmar

Aún no se ha verificado si existe una vía de streaming de Drips compatible de forma nativa con Soroban. Mientras se confirma con el equipo de Drips, la alternativa es combinar Drips Wave con una tesorería separada en Ethereum/EVM.

---
 Fuentes: [SCF Handbook](https://stellar.gitbook.io/scf-handbook/scf-awards/build-award) · [Drips Docs](https://docs.drips.network/)