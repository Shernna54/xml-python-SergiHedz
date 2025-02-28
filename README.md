# 📌 Python en 1º de ASIR
Python es un lenguaje de programación interpretado y de alto nivel que se usa mucho en administración de sistemas, automatización y análisis de datos.

## 1️⃣ Fundamentos de Python
* Sintaxis básica: variables, tipos de datos (int, float, str, bool).
* Estructuras de control: if-else, for, while.
* Listas, tuplas y diccionarios: estructuras de datos clave.
* Funciones: definición con def, argumentos y retorno de valores.
* Módulos y librerías: uso de import para funciones avanzadas (os, sys, json, etc.).

## 2️⃣ Aplicaciones en administración de sistemas
* Automatización de tareas: scripts para renombrar archivos, modificar permisos, leer logs.
* Gestión de archivos: leer/escribir archivos con open().
* Subprocesos: ejecutar comandos del sistema con subprocess.

![Imagen de python](https://alfabetizaciondigital.fundacionesplai.org/pluginfile.php/9523/course/section/1596/python-logo-master-v3-TM.png)


<br><br>

# 📌 XML en 1º de ASIR
XML (**Extensible Markup Language**) es un formato usado para almacenar y transportar datos en una estructura jerárquica. Se usa mucho en configuración de servidores, intercambio de datos y APIs.

## 1️⃣ Estructura de XML
* Se basa en etiquetas personalizadas (parecido a HTML).
* Ejemplo de XML básico:

```python
<usuario>
    <nombre>Sergi</nombre>
    <correo>sergi@example.com</correo>
</usuario>
```
* Reglas: debe tener un elemento raíz, etiquetas bien cerradas y atributos en formato clave-valor.

## 2️⃣ Uso de XML en administración de sistemas
* Archivos de configuración: muchos programas guardan configuraciones en XML (config.xml).

* Intercambio de datos: APIs y servicios web usan XML para enviar información.

* Procesamiento con Python: librerías como xml.etree.ElementTree permiten leer y modificar XML.

* Ejemplo en Python para leer XML:

```python
import xml.etree.ElementTree as ET

xml_data = "<usuario><nombre>Sergi</nombre></usuario>"
root = ET.fromstring(xml_data)

print(root.find("nombre").text)  # Salida: Sergi
```

![Imagen de python](https://www.skillreactor.io/blog/wp-content/uploads/2024/07/xml-full-form-980x519.jpg)
