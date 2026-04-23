README – Lenguajes de marcas (Proyecto Intermodular)

Qué datos representa el XML?

El archivo XML representa la estructura de datos de la aplicación web TECHNOVA una empresa de servicios y productos tecnológicos.

Incluye:

* Catálogo de productos (nombre, categoría, precio, stock)
* Clientes (nombre y email)
* Pedidos realizados por los clientes
* Líneas de pedido, donde se relacionan productos y cantidades

Estos datos simulan el funcionamiento real de una tienda tecnológica, permitiendo gestionar información de forma estructurada.

---

¿Cómo se valida?

El XML se valida mediante un archivo XSD (XML Schema) que define:

* La estructura del documento (elementos y jerarquía)
* Tipos de datos (string, decimal, date, etc.)
* Restricciones (precio ≥ 0, cantidad ≥ 1)
* Relaciones entre datos mediante claves (`xs:key`) y referencias (`xs:keyref`)

La validación se ha realizado usando Visual Studio Code con la extensión XML Tools, comprobando que el XML cumple correctamente todas las reglas definidas en el XSD.

---

¿Cómo encaja dentro del proyecto?

Este XML forma parte del proyecto como una **representación estructurada de los datos principales de la aplicación.

Se puede utilizar como:

* Sistema de exportación/importación de datos
* Base para futuras integraciones con bases de datos
* Documento de apoyo para entender la estructura de la información

De esta forma, el XML está directamente relacionado con la lógica del proyecto web, simulando un entorno real de desarrollo.

---
