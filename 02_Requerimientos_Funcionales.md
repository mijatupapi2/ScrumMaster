## 3.3. Listado de Requerimientos Funcionales (RF)

**Prioridad:** MoSCoW (Must = Debe tener, Should = Debería, Could = Podría, Won't = No tendrá)

| ID | Descripción del Requerimiento | Prioridad | Criterio de Aceptación |
|----|-------------------------------|-----------|------------------------|
| RF-01 | El sistema debe permitir el registro y autenticación de usuarios con roles diferenciados (admin, técnico, ciudadano). | Must | Acceso denegado tras 3 intentos fallidos; cada rol ve solo lo autorizado. |
| RF-02 | El sistema debe permitir registrar datos ambientales (calidad de aire, agua, residuos, ruido) con formularios estandarizados. | Must | Los datos se guardan con metadatos obligatorios: fecha, ubicación, unidad de medida. |
| RF-03 | El sistema debe permitir visualizar datos en mapas interactivos (GIS) con capas temáticas. | Must | El mapa carga en menos de 3 segundos y permite filtrar por fecha y tipo de indicador. |
| RF-04 | El sistema debe generar reportes automáticos en PDF/Excel para cumplimiento normativo. | Should | El reporte incluye logo municipal, fecha, firma digital y se descarga en <10 seg. |
| RF-05 | El sistema debe publicar un portal público con indicadores ambientales actualizados. | Should | Los ciudadanos acceden sin login; los datos tienen máximo 24h de desfase. |
| RF-06 | El sistema debe integrarse con el Sistema Nacional de Información Ambiental vía API. | Could | La sincronización se ejecuta cada 24h sin intervención manual. |
| RF-07 | El sistema debe permitir notificaciones automáticas ante superación de umbrales ambientales. | Could | Se envía alerta por correo/SMS al técnico responsable en menos de 5 minutos. |