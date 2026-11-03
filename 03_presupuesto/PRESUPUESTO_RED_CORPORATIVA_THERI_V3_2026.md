# Presupuesto técnico de implementación de red corporativa (versión 3)

**Fecha de consulta:** 2026-11-02 · **Moneda:** pesos chilenos (CLP) · **IVA:** 19 % · **Máximo autorizado por el docente:** $35.000.000 IVA incluido.

**Fuente de cantidades:** inspección del archivo de Cisco Packet Tracer elaborado por Theri; la documentación de Nico sólo se usa para contrastar. **No es una orden de compra ni un conjunto de cotizaciones firmadas**: son precios web observados y partidas estimadas identificadas.

## Total de inversión

| Concepto | CLP, IVA incluido |
|---|---:|
| Red cableada | $7.955.520 |
| WAN / VPN | $614.932 |
| Servidores | $3.488.480 |
| Puestos | $12.189.204 |
| VoIP | $266.000 |
| WiFi rúbrica | $386.720 |
| IoT rúbrica | $164.940 |
| Infraestructura | $1.173.519 |
| Cableado + MO | $3.758.256 |
| Mano de obra TI | $2.686.782 |
| Servicios ISP | $300.000 |
| Logística | $350.000 |
| Reserva | $350.000 |
| Licencias | $831.960 |
| **TOTAL** | **$34.516.313** |
| **LÍMITE AUTORIZADO** | **$35.000.000** |
| **MARGEN SIN ASIGNAR** | **$483.687** |

**Mano de obra TI explícita:** $2.686.782. **Cableado Cat6 instalado y certificado (materiales + mano de obra juntos):** $3.758.256. La porción estricta de trabajo humano dentro del precio instalado de Cat6 no está separada por el proveedor y **no debe sumarse por segunda vez**.

## Detalle de equipamiento, servicios y mano de obra

Los valores son **unitarios y totales con IVA incluido**. En servicios con tarifa publicada sin IVA se calculó `precio neto × 1,19` y se redondeó al peso. El valor de la columna B es solo comparativo y puede corresponder a un distribuidor sin stock o una oferta no equivalente, indicado en el estado.

| N.º | Categoría | Equipo o servicio | Cantidad | Unitario IVA incl. | Total IVA incl. | Precio A y enlace | Precio B y enlace | Condición |
|---:|---|---|---:|---:|---:|---|---|---|
| 01 | Red cableada | Switch core L3 Cisco Catalyst C9200L-24T-4G-E | 4 | $1.532.105 | **$6.128.420** | [EliteCenter](https://store.elitecenter.cl/shop/redes/hubs-switches/cisco-catalyst-9200l-network-essentials-conmutador-l3-24-x-10-100-1000-4-x-gigabit-sfp-enlace-ascendente-montaje-en-rack/) | [IPeXpress](https://www.ipexpress.cl/pyme/product_info.php/switch-cisco-c9200l-24t-4g-p-4185): $1.632.934 | Web, disponibilidad parcial |
| 02 | Red cableada | Switch acceso PoE+ TP-Link Omada TL-SG2428P | 5 | $299.966 | **$1.499.830** | [EliteCenter](https://store.elitecenter.cl/shop/redes/hubs-switches/tp-link-omada-tl-sg2428p-gestionado-l2-l2-gigabit-ethernet-10-100-1000-energia-sobre-ethernet-poe-1u-negro/) | [ComparaFácil / NotebookStore](https://www.comparafacil.cl/producto/tp-link-tl-sg2428p-tl-sg2428p): $285.926 | Web |
| 03 | Red cableada | Switch DMZ MikroTik CRS326-24G-2S+RM | 1 | $327.270 | **$327.270** | [SP Digital](https://www.spdigital.cl/mikrotik-cloud-router-switch-crs326-24g-2srm-conmutador-l3-gestionado-24-x-101001000/) | [RedCetus](https://www.redcetus.cl/): precio sin verificar | Web; 2da cotización pendiente |
| 04 | WAN / VPN | Router empresarial MikroTik RB5009UG+S+IN | 2 | $307.466 | **$614.932** | [RedCetus](https://www.redcetus.cl/shop/mikrotik-rb5009ug-s-in-router-home-lab-4962) | [SP Digital](https://www.spdigital.cl/mikrotik-homelab-7-1000-1-2500-1-sfp10g-usb-l5-poein-dc-jack-dc-2pin/): $409.990 | Web |
| 05 | Servidores | Servidor Dell PowerEdge T150 Xeon E-2324G/16GB/1TB | 2 | $1.544.240 | **$3.088.480** | [SP Digital](https://www.spdigital.cl/t150-1-tb-4u-xeon-e-e2324g-3-1-ghz-16-gb/) | [EliteCenter](https://store.elitecenter.cl/shop/computadores/servidores/servidor-dell-poweredge-t150-servidor-1-tb-bastidor-4u-intel-xeon-e-e-2324g-31-ghz-16-gb-ddr4-sdram/): $1.632.846 | Web |
| 06 | Servidores | Reserva SSD/expansión RAM certificada Dell | 2 | $200.000 | **$400.000** | [Estimación técnica](https://www.dell.com/es-cl/shop/) | [Referencias memoria Dell](https://www.comparafacil.cl/categoria/rams/dell): precio sin verificar | ESTIMADO sin precio de SKU |
| 07 | Puestos | PC Ryzen 5 7600, 16GB DDR5, 1TB NVMe, Win11 Pro | 12 | $738.430 | **$8.861.160** | [Lotendras](https://www.lotendras.cl/pc-de-oficina-amd-ryzen-5-7600-16gb-ddr5-1tb-nvme) | [PCSolid](https://www.pcsolid.cl/productos/pc-slim-esgaming-amd-r5-7600-16gb-ddr5-1tb-nvme-wifi-win-11-pro/): $806.047 | Web |
| 08 | Puestos | Monitor LG 24MR400 IPS 24 pulgadas FHD | 12 | $87.390 | **$1.048.680** | [Lifemax](https://lifemaxdistribuidora.cl/products/monitor-lg-24mr400-24in-full-hd-ips-100hz-5ms-hdmi-vga-amd-freesync-flicker-safe-montaje-vesa) | [SP Digital](https://www.spdigital.cl/24mr400-24in-fhd-100hz-ips-monitor-3y/): precio sin verificar | Web; precio B pendiente |
| 09 | Puestos | Notebook Lenovo ThinkPad E14 Gen7, 16GB/512GB/Win11 Pro | 1 | $1.449.956 | **$1.449.956** | [NotebookStore](https://notebookstore.cl/lenovo-thinkpad-e14-notebook-14-lcd-intel-core-ultra-5-225u-16-gb-512-gb-ssd-win11-pro) | [TIShop](https://tishop.cl/products/notebook-lenovo-thinkpad-e14-gen-7-14-intel-core-ultra-5-225u-16-gb-ram-512-gb-ssd-windows-11-pro): $1.560.100 | Web |
| 10 | Puestos | Impresora láser red Brother HL-L2360DW | 4 | $207.352 | **$829.408** | [Insutech](https://www.insutech.cl/) | [Telenet](https://telenetchile.com/categoria/impresoras-laser): $221.883 | Web; enlace A categoría |
| 11 | VoIP | Teléfono IP Grandstream GRP2601P PoE | 5 | $53.200 | **$266.000** | [Smarthold](https://smarthold.cl/products/telefono-ip-grandstream-grp2601p-poe-sin-fuente) | [Netvoiss](https://www.tiendanetvoiss.cl/grandstream-grp2601p-telefono-ip): $53.756 | Web; stock a consultar |
| 12 | WiFi rúbrica | Access Point Wi-Fi 6 TP-Link Omada EAP610 | 4 | $96.680 | **$386.720** | [SP Digital](https://www.spdigital.cl/tp-link-punto-de-acceso-inalambrico-80211abgnacax-24-ghz-5-ghz-gestionado-a-traves-d/) | [Soluciones TCP](https://solucionestcp.cl/product/punto-de-acceso-wifi-6-tp-link-omada-eap610-ax1800-indoor-outdoor/): $129.990 | Web |
| 13 | IoT rúbrica | Cámara de red IP PoE TP-Link VIGI C440 4MP | 2 | $53.990 | **$107.980** | [Techcenter](https://www.techcenter.cl/collection/seguridad-y-video-vigilancia) | [Tecnobits](https://tecnobits.cl/product/camara-de-red-a-todo-color-dia-y-noche-vigi-de-4-mp-tplink/): precio sin verificar | Web; enlace A categoría |
| 14 | IoT rúbrica | Controlador Sonoff TH Elite THR320D | 2 | $21.990 | **$43.980** | [MCI Electronics](https://mcielectronics.cl/shop/product/interruptor-wifi-sonoff-th-elite-de-monitoreo-de-temperatura-y-humedad/) | [Sonoff Chile](https://sonoff.cl/products/interruptor-wifi-sonoff-th-elite-20a-monitoreo-de-temperatura-y-humedad): $21.990 | Web |
| 15 | IoT rúbrica | Sensor Sonoff THS01 temperatura/humedad | 2 | $6.490 | **$12.980** | [MCI Electronics](https://mcielectronics.cl/shop/product/sonoff-ths01-temp-and-humi-sensor/) | [Sonoff Chile](https://sonoff.cl/products/sensor-de-temperatura-y-humedad-sonoff-ths01-para-sonoff-th): $6.490 | Web |
| 16 | Infraestructura | Rack mural 12U 19 pulgadas, 60cm | 2 | $179.450 | **$358.900** | [SP Digital](https://www.spdigital.cl/rack-12u-ciego-fondo-60cm-ancho-19p-mural-pared-alto-64cm/) | [Telesystems](https://tienda.telesystems.cl/products/gabinete-mural-12u): $186.990 | Web |
| 17 | Infraestructura | UPS 2000VA rack/tower Ablerex SR 2000 | 2 | $229.990 | **$459.980** | [SP Digital](https://www.spdigital.cl/ups-ablerex-interactivo-2u-rack-torre-lcd-smart-sr-series-2000va-1200w/) | [Referencia cat. UPS](https://www.telesystems.cl/collections/racks-y-complementos): precio sin verificar | Web; precio B pendiente |
| 18 | Infraestructura | Regleta PDU rack 8 tomas | 3 | $19.987 | **$59.961** | [Rhona](https://rhona.cl/producto/11224/regleta-pdu-para-rack.html) | [TIShop](https://tishop.cl/categories/pdu-y-proteccion-electrica): $27.330 | Web |
| 19 | Infraestructura | Patch panel Cat6 24 puertos | 3 | $18.226 | **$54.678** | [Metacom](https://www.metacom.cl/patch-panel-cat-6-24-puertos) | [EECol](https://eecol.cl/cableado-estructurado/8731-patch-panel-24-puertos-cat6-1u-ex55993.html): $134.590 | Web |
| 20 | Infraestructura | Transceptor SFP 1G TP-Link TL-SM311LS o equivalente compatible | 8 | $30.000 | **$240.000** | [Tope de estimación](https://www.spdigital.cl/categories/conectividad-y-redes-conectividad-modulos-de-expansion/) | [Insutech](https://www.insutech.cl/categoria-producto/conectividad-y-redes/fibra-optica-y-transceptores/): $18.890 | ESTIMADO de 30.000; SKU Cisco pendiente |
| 21 | Cableado + MO | Punto Cat6 instalado y certificado (materiales + mano de obra) | 48 | $78.297 | **$3.758.256** | [Alicom](https://alicom.cl/servicios/redes-empresas/precio-punto-de-red/) | [Zentranet](https://www.zentranet.cl/precios): $71.400 | Web neto 65.796 + IVA; cantidad estimada |
| 22 | Mano de obra TI | Implementación lógica base de red | 2 | $178.500 | **$357.000** | [XHost](https://www.xhost.cl/administracion-de-redes/) | [PC-Help](https://www.pc-help.cl/servicios/configuracion-redes/): precio sin verificar | Tarifa de servicio publicada |
| 23 | Mano de obra TI | Configuración VLAN (hasta 10 por sede) | 2 | $59.500 | **$119.000** | [XHost](https://www.xhost.cl/administracion-de-redes/) | [PC-Help](https://www.pc-help.cl/servicios/configuracion-redes/): precio sin verificar | Tarifa de servicio publicada |
| 24 | Mano de obra TI | Enrutamiento inicial + DHCP/DNS | 2 | $23.800 | **$47.600** | [XHost](https://www.xhost.cl/administracion-de-redes/) | [PC-Help](https://www.pc-help.cl/servicios/configuracion-redes/): precio sin verificar | Tarifa de servicio publicada |
| 25 | Mano de obra TI | NAT/PAT perimetral | 2 | $29.750 | **$59.500** | [XHost](https://www.xhost.cl/administracion-de-redes/) | [PC-Help](https://www.pc-help.cl/servicios/configuracion-redes/): precio sin verificar | Tarifa de servicio publicada |
| 26 | Mano de obra TI | Túnel VPN IPsec sitio a sitio | 2 | $119.000 | **$238.000** | [XHost](https://www.xhost.cl/administracion-de-redes/) | [PC-Help](https://www.pc-help.cl/servicios/configuracion-redes/): precio sin verificar | Tarifa de servicio publicada |
| 27 | Mano de obra TI | Configuración lógica AP WiFi + SSID | 4 | $29.750 | **$119.000** | [XHost](https://www.xhost.cl/administracion-de-redes/) | [Fixday](https://fixday.cl/servicios/wifi-redes): $35.000 | Tarifa de servicio publicada |
| 28 | Mano de obra TI | Soporte especializado remoto, bloque hasta 2 horas | 18 | $53.431 | **$961.758** | [Logicnet](https://logicnet.cl/soporte.php) | [PC-Help](https://www.pc-help.cl/servicios/configuracion-redes/): precio sin verificar | Tarifa de servicio publicada |
| 29 | Mano de obra TI | Soporte instalación/verificación presencial, 2 horas | 4 | $83.181 | **$332.724** | [Logicnet](https://logicnet.cl/soporte.php) | [Fixday](https://fixday.cl/servicios/wifi-redes): precio sin verificar | Tarifa de servicio publicada |
| 30 | Mano de obra TI | Levantamiento/diagnóstico documentado de sitios | 2 | $226.100 | **$452.200** | [Zentranet](https://www.zentranet.cl/telecomunicaciones) | [PC-Help](https://www.pc-help.cl/servicios/configuracion-redes/): precio sin verificar | REFERENCIA por sitio |
| 31 | Servicios ISP | Bolsa de alta/enlaces ISP | 2 | $150.000 | **$300.000** | [ESTIMACIÓN no cotizada](https://www.entel.cl/empresas/) | [Alternativa proveedor](https://www.movistar.cl/empresas/): precio sin verificar | ESTIMACIÓN |
| 32 | Logística | Bolsa traslado/despacho/instalación no tarifada | 1 | $350.000 | **$350.000** | [ESTIMACIÓN no cotizada](https://www.chilexpress.cl/) | [Cotización de traslado](https://www.starken.cl/): precio sin verificar | ESTIMACIÓN |
| 33 | Reserva | Reserva por precio/stock y variación | 1 | $350.000 | **$350.000** | [RESERVA](https://www.cisco.com/c/en/us/products/collateral/switches/catalyst-9200-series-switches/nb-06-cat9200-swit-ser-cte-en.html) | [Referencia licencias](https://store.webredes.cl/brand/17-cisco): precio sin verificar | ESTIMACIÓN |
| 34 | Licencias | Cisco DNA Essentials 24 puertos 3 años (C9200L-DNA-E-24-3Y) | 4 | $207.990 | **$831.960** | [WebRedes Store](https://store.webredes.cl/brand/17-cisco) | [Guía oficial Cisco](https://www.cisco.com/c/en/us/products/collateral/switches/catalyst-9200-series-switches/nb-06-cat9200-swit-ser-cte-en.html): precio sin verificar | Web, a pedido |

## Alcance exacto que se tomó del Cisco de Theri

- **Se costean** 2 routers de borde de la empresa (R-HQ/R-SUC), 4 core multilayer, 5 switches de acceso y 1 switch para la DMZ. Los routers ISP1/ISP2 son **simulación de la red del operador** y no se compran.
- **Los siete servidores de Packet Tracer son siete funciones lógicas**: HTTP, DNS, NTP, correo, Syslog, AAA e IoT. Para este presupuesto se proponen dos hosts Dell T150 y virtualización de servicios Linux; la compatibilidad, memoria de 16 GB por host, almacenamiento y disponibilidad deben dimensionarse antes de compra.
- **Se costean 12 PCs de oficina y monitores**, excluyendo el PC externo usado para probar desde Internet. Se añaden 1 laptop, 4 impresoras y 5 teléfonos IP conforme al inventario. Los dos dispositivos etiquetados «Termostato» son PC renombrados en el archivo, no sensores reales.
- **La rúbrica exige WLAN por departamento e IoT**: se contemplan 4 AP Wi-Fi 6, 2 cámaras IP, 2 controladores termostato y 2 sensores. Estos equipos deben añadirse y configurarse en Cisco Packet Tracer si el grupo quiere evidenciar los requisitos.
- **El archivo guarda 60 enlaces simulados**, incluidas troncales y conexiones a dispositivos. Como cantidad inicial de presupuesto se fijaron **48 tomas Cat6 de planta** (24 por sede), no 60 tomas. Esta cifra es provisional, pues faltan medidas y plano de puntos reales. Incluye instalación, certificación y materiales según alcance publicado por Alicom; el resto de interconexiones se representa en elementos de rack/enlaces presupuestados.

## Condiciones de licencia y compatibilidad

1. La configuración guardada por Theri usa **HSRP v2**. El Cisco C9200L-24T-4G-**E** de este presupuesto incluye **Network Essentials**, que soporta enrutamiento OSPF de acceso y **VRRP**. **VRRP ofrece redundancia equivalente de gateway, pero no es la misma configuración HSRP del archivo Cisco.** Para mantener HSRP exactamente se debe recotizar C9200L-24T-4G-**A** (Network Advantage); el precio de esa variante no cabe automáticamente bajo el tope sin reordenar partidas. [Matriz de funciones Cisco](https://www.cisco.com/c/dam/m/en_us/products/software/dna-subscription-switching/en-sw-sub-matrix-switching/pdf/Cisco_catalyst_software_subscription_matrix_for_switching.pdf) · [Guía de pedido Cisco](https://www.cisco.com/c/en/us/products/collateral/switches/catalyst-9200-series-switches/nb-06-cat9200-swit-ser-cte-en.html).
2. Se presupuestan **4 licencias Cisco DNA Essentials por 3 años**. Cisco indica que al comprar Catalyst 9200 se debe incluir una suscripción de nivel correspondiente. Antes de pagar, validar con distribuidor si ya la incluyó en los precios de los cuatro switches, para evitar duplicación. [Licencia con precio publicado](https://store.webredes.cl/brand/17-cisco).
3. Las ofertas de Cisco verificadas presentan **stock insuficiente** para adquirir 4 unidades de forma inmediata; no asumir disponibilidad de la cantidad requerida. Las garantías/SMARTnet se deben cotejar con cada proveedor. La reserva de $350.000 no garantiza contratar un soporte Cisco adicional.
4. La **mensualidad de fibra/Internet y su SLA no está incluida** en esta inversión inicial; el ítem ISP es sólo una provisión de activación. Sin direcciones comerciales ni ancho de banda contratado no existe una cotización comparable que se pueda atribuir honestamente.

## Lo que requiere confirmación antes de una compra real

- **03 — Switch DMZ MikroTik CRS326-24G-2S+RM:** En PKT hay un solo uplink a core; conectar segundo físicamente sólo tras validar topología final.
- **06 — Reserva SSD/expansión RAM certificada Dell:** Monto asignado para actualización compatible con T150; exige cotización formal de RAM ECC + SSD soportado.
- **08 — Monitor LG 24MR400 IPS 24 pulgadas FHD:** La cotización de segunda tienda debe confirmarse para el mismo modelo.
- **17 — UPS 2000VA rack/tower Ablerex SR 2000:** Autonomía real depende de carga de switches PoE y UPS.
- **20 — Transceptor SFP 1G TP-Link TL-SM311LS o equivalente compatible:** No asumir que SFP TP-Link funciona en Cisco; validar transceptor aprobado y cable óptico, si hay fibra.
- **30 — Levantamiento/diagnóstico documentado de sitios:** Zentranet informa cobertura solo Santiago; valor sucursal Valparaíso es estimación de referencia.
- **31 — Bolsa de alta/enlaces ISP:** La mensualidad y SLA de Internet no se incluyen en CAPEX inicial: necesitan direcciones/velocidad y oferta comercial.
- **32 — Bolsa traslado/despacho/instalación no tarifada:** Fletes y viáticos son provisiones, no precio publicado del courier por esta carga.
- **33 — Reserva por precio/stock y variación:** La reserva no sustituye cotización formal. HSRP requiere Network Advantage y cambia significativamente la factura.

La pauta pide **dos cotizaciones chilenas por partida relevante**, idealmente PDFs emitidos por proveedores, no sólo enlaces de catálogo. En la tabla se aportan las dos referencias cuando existen; donde no existe precio comparable se dejó claramente como pendiente. Los precios publicados pueden variar por stock, medio de pago, despacho e impuestos.

## Evidencias de puesta en marcha que faltan en Cisco Packet Tracer

La compra presupuestada **no significa que el archivo Packet Tracer esté terminado**. Se necesitan pings entre VLANs y sedes, tabla OSPF, estado de failover/VRRP o HSRP según equipamiento real, negociación y contadores IPsec, NAT/PAT, publicación HTTP/DMZ, DNS/AAA, registros VoIP, SSID/WPA2-WPA3, IoT, ACL y capturas con fecha. La auditoría actual señaló una IP web incongruente (.146 contra .147), seis servidores sin IPv4 fija guardada y DNS/AAA deshabilitados.

**Control:** total calculado como suma de cantidades × precio unitario, cada precio unitario con IVA; no se suma un segundo 19 % sobre el total.
