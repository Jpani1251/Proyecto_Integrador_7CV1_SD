# Sistema de Reservas de Hotel en la Nube

## 1. Descripción del Proyecto
Sistema distribuido en la nube diseñado para gestionar la disponibilidad y reservas de hoteles pequeños y casas de huéspedes. Resuelve problemas de sobreventa (doble reserva) y caídas del sistema en picos de demanda mediante un motor con control de concurrencia. El proyecto evolucionará hasta convertirse en una arquitectura de microservicios (autenticación, catálogo, reservas y notificaciones) orquestada sobre Kubernetes.

## 2. Integrantes del Equipo (Equipo 1)
* **Bernal Jardon Saul Andres**
* **Carlos Antonio Hernández Villeda**
* **Jorge Alberto Paniagua Escamilla**

## 3. Bitácora del Proyecto
El registro detallado de actividades, decisiones de arquitectura, problemas encontrados y avances por fase se documenta en el archivo [BITACORA.md](./BITACORA.md). Todos los integrantes registrarán commits significativos en este repositorio como evidencia de trabajo.

## 4. Fases de Desarrollo
El proyecto se divide en 7 fases alineadas al plan de estudios:
- [x] **Registro y propuesta:** Repositorio creado, problema definido (gestión hotelera) y alcance establecido.
- [ ] **Fase 1 y 2 (1er Parcial):** Modelo de servicio, arquitectura inicial, justificación del proveedor y definición de SLOs medibles.
- [ ] **Fase 3 y 4 (2do Parcial):** Partición/replicación de datos, servicio tras un balanceador con autoescalado y pruebas de carga.
- [ ] **Fase 5:** Seguridad aplicada (IAM de menor privilegio, segmentación de red, cifrado y gestión de secretos).
- [ ] **Fase 6:** API REST documentada con OpenAPI y desplegada en contenedor o serverless.
- [ ] **Fase 7 (Demo Final):** Sistema en microservicios sobre Kubernetes con observabilidad básica y demostración de resiliencia (failover en vivo).

## 5. Requisitos Técnicos y Presupuesto
* **Proveedor de Nube**
* **Gestión de Costos**
