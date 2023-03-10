# CoderBackend

## Desafio entregable n° 18 - MEJORAR LA ARQUITECTURA DE NUESTRA API
- **Formato:** link a un repositorio en Github con el proyecto cargado.

- **Sugerencia:** no incluir los node_modules
  
- **Consigna:**
Retomemos nuestro trabajo para implementar los patrones de diseño Factory, DAO y DTO.

➔ Modificar la capa de persistencia incorporando los conceptos de Factory, DAO, y DTO.

➔ Los DAOs deben presentar la misma interfaz hacia la lógica de negocio de nuestro servidor.

➔ El DAO seleccionado (por un parámetro en línea de comandos como lo hicimos anteriormente) será
devuelto por una Factory para que la capa de negocio opere con el.

➔ Cada uno de estos casos de persistencia, deberán ser implementados usando el patrón singleton que
impida crear nuevas instancias de estos mecanismos de acceso a los datos.

➔ Comprobar que si llamo a la factory dos veces, con una misma opción elegida, devuelva la misma
instancia.

➔ Implementar el patrón Repository para la persistencia de productos y mensajes.