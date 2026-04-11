# Prueba ISO 02

## 1. Datos generales
- **Nombre de la ISO probada:PuppyLinux**  
- **Fecha:11/04/2026**  
- **Software de virtualización:Vbox**  

## 2. Configuración de la VM
**CPU:** 2 núcleos (equivalente al equipo real: Intel Core 2 Duo de 2 núcleos)  

**RAM:** 4096 MB (4 GB) para simulación completa  

**Disco virtual:** 160 GB (dinámico, SATA)  
- **Tipo de arranque configurado:**BIOS
- **Otras opciones relevantes:**
- **Gráficos:** 128 MB de memoria de vídeo  
- **Controlador gráfico:** VMSVGA 

## 3. Resultado del arranque
Sistema de arranque GRUB con diversas opciones, seleccionaré la primera "fossapup64 9.5". El sistema arranca directamente y se ejecuta en vivo, ya que se carga en la RAM del sistema, para instalarlo debemos hacerlo manualmente.

## 4. Resultado del instalador
Para instalar el sistema, hay que abrir el menu, luego setup, puppyInstaller, frugalpup, puppy y seleccionar this, despues crear la particion sda1 (formato ext4) en la que instalaremos el sistema y el arrancador GRUB

## 5. Resultado final
Tras esto, el sistema estará instalado, pero se comporta exactamente igual que el sistema live, me he pegado 2h51m para que funcione exactamente igual que si estuviese live :) 

## 6. Capturas relacionadas
![Arranque](../assets/img/21-vm_iso_02/ArranquePuppy.png)
![Inicio](../assets/img/21-vm_iso_02/InicioPuppy.png)
![Instalador](../assets/img/21-vm_iso_02/InstaladorPuppy.png)

## 7. Valoración
Opinion sumamente honesta: mierdón enorme de sistema, super poco intiutivo, en ingles completamente, sin posibilidad de cambiarlo a español ya que la maquina no está conectada a internet y necesita descargar un pack de lenguajes para ello, +2h de configuraciones, salir y entrar, tocar ajustes de almacenamiento de virtualbox...Para poder instalarlo y tras todo eso la unica diferencia con la version live es que no se ve "Puppy live cd" arriba de la pantalla.Me ha dado una barbaridad de problemas.
