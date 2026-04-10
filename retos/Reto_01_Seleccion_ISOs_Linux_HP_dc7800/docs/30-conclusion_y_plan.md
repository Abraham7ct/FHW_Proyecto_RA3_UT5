# Conclusión final y plan de instalación

---

## 1. Resumen del análisis

Tras el análisis y prueba de las tres distribuciones Linux seleccionadas, se ha comprobado que todas son compatibles con el hardware del HP Compaq dc7800, aunque con diferentes niveles de rendimiento y facilidad de uso.

Se ha observado que Lubuntu ofrece la experiencia más completa y equilibrada, Puppy Linux destaca por su extrema ligereza y rapidez, y Bodhi Linux se sitúa como una solución intermedia que combina bajo consumo de recursos con una interfaz funcional. En conjunto, las tres opciones permiten cubrir distintos escenarios de uso según las limitaciones del equipo.

---

## 2. Decisión final

**ISO elegida como opción principal:**  
Lubuntu 22.04 LTS  

**ISO elegida como alternativa:**  
Puppy Linux (Fossapup64 9.5)  

**ISO elegida como respaldo:**  
Bodhi Linux 7.0.0  

---

## 3. Justificación de la decisión

El orden seleccionado se basa en un criterio de equilibrio entre rendimiento, compatibilidad y facilidad de uso.

Lubuntu se elige como opción principal por ser la más estable, fácil de usar y compatible con hardware antiguo, manteniendo un entorno moderno. 

Puppy Linux se selecciona como alternativa debido a su capacidad para funcionar con muy pocos recursos, lo que la convierte en una opción viable si el rendimiento de Lubuntu no es suficiente. 

Finalmente, Bodhi Linux se utiliza como respaldo por su ligereza y estabilidad, ofreciendo una solución intermedia en caso de fallo de las otras dos opciones.

Este orden tiene sentido para el HP Compaq dc7800, ya que adapta las distribuciones a sus limitaciones de hardware (HDD lento, 4 GB de RAM DDR2 y CPU antigua) sin comprometer la funcionalidad básica del sistema.

---

## 4. Plan para el aula taller

El orden de instalación en el equipo real sería el siguiente:

1. Primero se intentaría la instalación de Lubuntu 22.04 LTS como sistema principal.  
2. Si Lubuntu no funcionara correctamente o presentara problemas de rendimiento, se procedería a instalar Puppy Linux como alternativa ligera.  
3. En caso de que ninguna de las dos opciones anteriores fuese funcional, se instalaría Bodhi Linux como sistema de respaldo.

Si durante la instalación se detectaran errores de arranque, incompatibilidades de hardware o problemas de rendimiento, se reiniciaría el proceso utilizando la siguiente ISO en el orden establecido.

---

## 5. Aprendizaje obtenido

Analizar las características de un equipo antiguo y a seleccionar sistemas operativos adecuados en función de sus recursos hardware. 

También se ha comprendido la importancia de comparar distribuciones Linux según su consumo de recursos, compatibilidad y facilidad de instalación.

Además, se ha reforzado el uso de máquinas virtuales como herramienta de pruebas antes de la instalación en hardware real, así como la utilidad de planificar distintas opciones (principal, alternativa y respaldo) para asegurar el éxito del despliegue del sistema operativo.
