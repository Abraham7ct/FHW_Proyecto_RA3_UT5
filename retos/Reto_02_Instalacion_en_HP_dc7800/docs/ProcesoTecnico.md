# Informe de Prácticas: Instalación de Linux en Equipo Real

**Alumno:** Abraham Aparicio Moreno  
**Grupo:** 1º ASIR  
**Equipo:** HP Compaq dc7800 SFF  
**Fecha de entrega:** 11/04/2026  

---

## EJERCICIO 1. Preparación del Medio de Instalación (Ventoy)

### 1.1. Configuración del USB
- **Herramienta:** Ventoy (versión más reciente) para soporte multiso.  
- **Método:** Instalación de Ventoy en el pendrive y copia de archivos mediante arrastrar y soltar.  
- **Arquitectura:** Se han seleccionado ISOs de 64 bits para aprovechar el procesador Intel Core 2 Duo E6750.  

### 1.2. ISOs incluidas (Validadas en Reto 01)
Se han incluido las tres opciones analizadas para garantizar el éxito de la instalación:

- **Lubuntu 22.04 LTS:** Opción principal por su equilibrio y entorno LXQt.  
- **Puppy Linux (Fossapup64 9.5):** Alternativa ligera para ejecución en RAM.  
- **Bodhi Linux 7.0.0:** Respaldo basado en Ubuntu con escritorio Moksha.  

**Captura de pantalla requerida:**  
Mostrar el contenido del USB con los tres archivos `.iso` visibles.

---

## EJERCICIO 2. Proceso de Arranque y Selección

### 2.1. Configuración de la BIOS (Legacy)
Dado que el equipo no posee UEFI, se han seguido estos pasos:

1. Inserción del USB preparado.  
2. Encendido y pulsación de la tecla de menú de arranque (habitualmente F9 en HP).  
3. Selección del dispositivo USB en el listado de arranque.  

### 2.2. Interfaz de Ventoy en el HP Compaq dc7800
- Se inicia el menú de Ventoy mostrando las tres opciones.  
- **Elección inicial:** Lubuntu 22.04 LTS.  

---

## EJERCICIO 3. Documentación de la Instalación Final

### 3.1. Distribución instalada
`[Escribir nombre de la ISO instalada]`

### 3.2. Particionado aplicado
- **Disco duro:** SATA de 160 GB (HDD mecánico).  
- **Esquema de particiones:**  
  - `[Ejemplo: Particionado automático usando todo el disco]`  
  - `[Ejemplo: Partición / (raíz), /home y área de intercambio (SWAP) de 4GB]`

### 3.3. Pasos principales de la instalación
- **Idioma y Teclado:** Configurado en español.  
- **Conexión:** Instalación realizada sin conexión a internet.  
- **Creación de usuario:** Nombre de usuario "Abraham" con privilegios de administrador.  
- **Copia de archivos:** Proceso de transferencia al HDD de 160 GB.  

### 3.4. Incidencias y soluciones encontradas

| Incidencia detectada | Solución aplicada |
|----------------------|------------------|
| [Ej: El instalador no reconoce el disco] | [Ej: Cambio de modo SATA en BIOS a AHCI/IDE] |
| [Ej: Lentitud extrema en la carga] | [Ej: Se optó por Puppy Linux en lugar de Lubuntu por el HDD] |
| [Ej: Fallo en resolución de pantalla] | [Ej: Uso de drivers genéricos Intel GMA 3100] |

### 3.5. Resultado final
- **¿El sistema arranca desde el disco duro?:** `[Sí/No]`  
- **Rendimiento observado:** `[Fluido / Aceptable / Lento]`  

**Captura de pantalla final:**  
Foto del equipo real con el escritorio cargado y una terminal abierta mostrando el comando `neofetch` o las propiedades del sistema.
