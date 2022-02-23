#### Jean Marco Rojas U. - Alonso Obando - 

# Objetivo General
* Implementar un analizador de espectros simple para audio.
# Objetivos Específicos
* Profundizar los conceptos de señales y ondas mediante el uso de módulos de software que implementan la transformada de Fourier.
* Graficar señales de audio en el dominio del tiempo y dominio de frecuencia.
* Extraer armónicos específicos para generar tonos de audio.
# Datos Generales
* El valor del proyecto: 7%
* La tarea debe ser implementada por grupos de 3 personas.
* La fecha de entrega es 11/03/2022 antes de las 3:30 pm.
* Cualquier indicio de copia será calificado con una nota de 0 y será procesado de acuerdo al reglamento. La copia incluye código que se puede encontrar en Internet y que sea utilizado parcial o totalmente sin el debido reconocimiento al autor.
* La revisión es realizada por él profesor asignado al curso, él mismo se reserva el derecho de solicitar una revisión virtual con los miembros del grupo para evacuar cualquier duda sobre la implementación.
* Se espera que todos y todas las integrantes del grupo entiendan la implementación suministrada.
* Se deben seguir buenas prácticas de programación. Por ejemplo documentación interna y externa, estándares de código, diagramas de arquitectura, diagramas de flujo, pruebas unitarias son algunas de las buenas prácticas que se esperan de un estudiante de Ingeniería en Computación en sus cursos finales.
* El lenguaje de implementación queda a criterio de cada grupo, se recomienda Python.
* Toda documentación debe ser implementada en Markdown.
* El email de entrega debe contener una copia del proyecto en formato tar.gz y un link al repositorio dónde se encuentra almacenado, debe seguir los lineamientos en el programa de curso.
# Descripción
Cada grupo deberá implementar una pequeña aplicación llamada Autrum, la misma tiene dos
modos de operación:
**Analizador:** toma señales de audio streaming (captura de micrófono) o batch (archivos WAV) y
deberá:
* Almacenar el audio en caso de ser streaming (el usuario debe poder indicar cuándo iniciar,
cuando parar, cuando continuar y cuando terminar).
* Graficar la señal en el dominio del tiempo.
* Calcular su transformada de Fourier utilizando algún módulo de software disponible, por ejemplo scipy.fft.
* Graficar en tiempo real los componentes de frecuencia obtenidos mediante la transformada de Fourier y poder ver tanto el gráfico en el tiempo así como en frecuencia al mismo tiempo.
* Generar un archivo .atm (Autrum File) que contendrá el audio original, junto con los datos usados para generar los gráficos en dominio de frecuencia.
**Reproductor:** Toma archivos con extensión .atm y puede reproducir el audio al mismo tiempo
que los gráficos en dominio del tiempo y dominio de frecuencia, el usuario podrá detener, cancelar y
resumir la reproducción en cualquier momento y realizar una exploración de los gráficos (zoom in /
zoom out).