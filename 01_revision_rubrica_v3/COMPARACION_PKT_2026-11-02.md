# Comparación de las dos versiones de Cisco de Theri

**Fecha de revisión:** 2 de noviembre de 2026. **Método:** lectura estática de las configuraciones y estructura guardadas en dos archivos Packet Tracer; no se ejecutaron pings ni pruebas en el simulador.

| Archivo | SHA-256 | Dispositivos | Enlaces |
|---|---|---:|---:|
| `TRABAJO REDES-backup.pkt` (versión del repositorio de Nico) | `18a404cadd2dbc8e4e0a38c9d44903ecf0512b60391ad5a59cbfd0b0a644460d` | 51 | 60 |
| `TRABAJO REDES-backup(1).pkt` (versión compartida por Christopher el 2/11) | `47cf5afdcd30d743b864f29fd963d6f3e7a7a06a8c2fef1bdf2e50933e5f5ea6` | 51 | 60 |

## Diferencias comprobadas

- No hay dispositivos añadidos ni retirados.
- Los **60 enlaces** conservan los mismos extremos y puertos de conexión.
- Todas las líneas guardadas de `RUNNINGCONFIG` y `STARTUPCONFIG` coinciden entre versiones. Se observan movimientos de iconos en el plano y cambios internos de metadatos de Packet Tracer.
- **No se identificaron correcciones funcionales persistidas** en IP, NAT, servicios ni nuevas WLAN. Esto no permite descartar trabajo en curso que aún no haya sido guardado en el archivo.

## Hallazgos que permanecen en la nueva versión

1. En `R-HQ`, la regla de publicación web apunta a `10.10.1.146`, pero `Server HTTP` conserva `10.10.1.147/24`; la DMZ es `10.10.1.144/28` con gateway `10.10.1.145`.
2. `Server1` a `Server6` siguen sin IPv4 fija guardada en sus interfaces.
3. DNS y AAA/ACS aparecen deshabilitados en el estado guardado de los siete servidores.
4. No hay puntos de acceso inalámbrico para los SSID exigidos en ambas sedes.
5. `Termostato` y `Termostato2` siguen registrados como dispositivos tipo PC.
6. `SW-DMZ` mantiene un único uplink a `CORE-HQ1`.

## Acciones para la rúbrica

Primero concluir la configuración de servicios, direccionamiento, WLAN e IoT **en una copia de trabajo**. Luego registrar pruebas de `show ip ospf neighbor`, `show standby brief`, `show crypto isakmp sa`, `show crypto ipsec sa`, `show ip nat translations`, ping, HTTP, DHCP, telefonía, restricciones de ACL y recuperación. Comprobar el PDF, presupuesto con **tope de $35 millones IVA incluido informado como autorizado por el profesor**, cotizaciones y defensa de 15 minutos.

**Autoría:** la implementación Cisco pertenece a Theri. La comparación y lista de pendientes son material nuevo de apoyo; no se modifica ni divulga el `.pkt` completo en este archivo.
