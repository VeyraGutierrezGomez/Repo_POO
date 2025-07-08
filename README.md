# Repo_POO

**Proyecto en Java (Java Swing) – Ingeniería en Tecnologías de la Información**

Este repositorio contiene el proyecto **Simulador De Registro De Viajes - Planificador Turistico**, desarrollado como parte de las prácticas académicas del curso **Programación Orientada a Objetos** (6° cuatrimestre) en la Universidad Politécnica de Victoria.

## Tecnologías utilizadas

* Lenguaje: Java 8+
* Entorno principal de desarrollo: IntelliJ IDEA Community Edition 2024.3.1.1
* Librería para PDF: OpenPDF 1.3.30 (`openpdf-1.3.30.jar`)
* GUI: Java Swing (javax.swing)
* JDK: Java Development Kit 17

## Proyecto incluido

### Simulador De Registro De Viajes - Planificador Turistico

Un planificador de viajes por México con interfaz gráfica que permite:

* Seleccionar destino, fechas, número de personas y tipo de hospedaje.
* Agregar actividades opcionales.
* Generar un resumen en formato HTML.
* Exportar el resumen a PDF usando OpenPDF.

## Instrucciones de ejecución

1. Asegúrate de tener instalado **JDK 17**.
2. Clona el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/Repo_POO.git
   ```
3. Abre **IntelliJ IDEA Community Edition 2024.3.1.1**.
4. Selecciona **File > Open** y elige la carpeta del proyecto.
5. Crea la carpeta `lib/` en la raíz y copia `openpdf-1.3.30.jar`.
6. Ve a **File > Project Structure > Modules > Dependencies**.
7. Añade `lib/openpdf-1.3.30.jar` como dependencia de tipo JAR.
8. Configura el SDK del proyecto a JDK 17 en **Project Settings**.
9. Ejecuta la clase principal:

   ```
   Run > Run 'PlanificadorTuristico.main()'
   ```

## Estructura del repositorio

```
Repo_POO
```
**Nota:** Este proyecto fue desarrollado con fines educativos para la materia de Programación Orientada a Objetos.
