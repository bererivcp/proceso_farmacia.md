# Diagrama de Atención al Cliente en Farmacia
```mermaid
flowchart TD
    A[Inicio: Identificación del cliente]
    A --> B{¿Consulta o Compra?}
    B --> C[Consulta: Fin de la atención]
    B --> D[Compra: Registrar detalles de la transacción]
    D --> E[Validar disponibilidad del producto]
    E --> F{¿Producto disponible?}
    F --> G[No: Registrar pedido pendiente y marcar como seguimiento]
    G --> H[Fin de la atención]
    F --> I[Sí: Concretar la venta]
    I --> H

```
