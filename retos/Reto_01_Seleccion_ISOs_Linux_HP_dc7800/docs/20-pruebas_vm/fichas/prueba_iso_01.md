# Prueba ISO 01

## 1. Datos generales
- **Nombre de la ISO probada:Lubuntu 22.04.4LTS**  
- **Fecha:11/04/2026**  
- **Software de virtualización:VirtualBox**  

## 2. Configuración de la VM
**CPU:** 2 núcleos (equivalente al equipo real: Intel Core 2 Duo de 2 núcleos)  

**RAM:** 4096 MB (4 GB) para simulación completa  

**Disco virtual:** 160 GB (dinámico, SATA)  
- **Tipo de arranque configurado:**BIOS
- **Otras opciones relevantes:**
- **Gráficos:** 128 MB de memoria de vídeo  
- **Controlador gráfico:** VMSVGA 

## 3. Resultado del arranque
Aparece el menú de arranque(GRUB) con diferentes opciones, seleccionaré la primera (try or install Lubuntu).

## 4. Resultado del instalador
Aparece la pantalla de inicio del instalador, selecciono mi idioma y procedo con "instalar Lubuntu". Seleccionaré el modo "minimal installation" ya que al no estar conectada a internet la maquina no me permitiría descargar ningun software más allá del que incluye el SO.

## 5. Resultado final
Tras una instalación sin problemas, el equipo arranca e inicia perfectamente, como dije en otra parte del trabajo, esto no asegura al 100% que vaya a funcional en el equipo real del taller, ya que hay aspectos que no se pueden simular en la maquina virtual, como el chipset Intel Q35, la tarjeta gráfica integrada Intel GMA 3100 o el comportamiento real del disco duro mecánico (latencias físicas y velocidad real de lectura/escritura).

## 6. Capturas relacionadas
![Arranque](../assets/img/20-vm_iso_01/ArranqueLubuntu.png)
![Instalador](../assets/img/20-vm_iso_01/InstaladorLubuntu.png)
- `assets/img/20-vm_iso_01/iso-01-resultado.png`

## 7. Valoración
Indica si esta ISO parece adecuada para el HP real.
