## Configuración de la máquina virtual

### Software utilizado  
**Aplicación:** Oracle VM VirtualBox  
**Versión:** 7.2.6 

---

### Configuración aplicada  

**CPU:** 2 núcleos (equivalente al equipo real: Intel Core 2 Duo de 2 núcleos)  

**RAM:** 4096 MB (4 GB) para simulación completa  

**Disco virtual:** 160 GB (dinámico, SATA)  

**Controlador de almacenamiento:** SATA (AHCI)  

**Red:** Adaptador no conectado(para simular entorno offline)  

**Audio / vídeo / otros ajustes relevantes:**  
- Gráficos: 128 MB de memoria de vídeo  
- Controlador gráfico: VMSVGA    
- Firmware: BIOS (modo legacy)  

---

### Relación con el equipo real  

La máquina virtual intenta reproducir las características principales del HP Compaq dc7800, especialmente en CPU (2 núcleos), memoria RAM (4 GB) y almacenamiento (160 GB SATA).

Sin embargo, no es posible replicar completamente el hardware real, como el chipset Intel Q35, la tarjeta gráfica integrada Intel GMA 3100 o el comportamiento real del disco duro mecánico (latencias físicas y velocidad real de lectura/escritura). Tampoco se puede simular con total fidelidad la compatibilidad de dispositivos físicos como el adaptador WiFi Belkin.

Por ello, la VM se utiliza como entorno de pruebas previo, pero los resultados deben validarse posteriormente en el equipo físico.
