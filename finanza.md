# Diagrama de Finanzas en Farmacia
```mermaid
flowchart TD
    A[Inicio] --> B[Registrar ingresos]
    B --> C[Registrar gastos]
    
    C --> D[Gestión de Proveedores]
    D --> D1[Pago a proveedores]
    D --> D2[Control de facturas]

    C --> E[Gestión de Recursos Humanos (RRHH)]
    E --> E1[Pago de sueldos]
    E --> E2[Registro de horas laborales]

    C --> F[Gestión de Recursos Materiales (RRMM)]
    F --> F1[Compra de insumos]
    F --> F2[Inventario de productos]

    F2 --> G[Calcular ingresos netos]

    G --> H{¿Ingresos netos positivos?}
    H -- Sí --> I[Evaluar oportunidades de inversión]
    H -- No --> J[Reducir gastos]

    I --> K[Implementar inversiones]
    J --> K

    K --> L[Fin]

```
