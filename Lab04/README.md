# Lab04 - MÓDULO LOGÍSTICO
## Desarrollo

**1. Instalación de Módulo Inventarios**

   * Instalamos el módulo Gestión de inventarios
   
   ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/modulo_inventario.png)
   
**2. Configuración de Almacenes**

   * Vemos que podemos crear contactos como gerentes, asistentes, etc; direcciones de
facturación, de envío, etc. Esto nos servirá a futuro para contactos con múltiples sucursales o personas
a cargo.

  ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/crear_almacen.png)

**3. Tipos de operaciones**

   * Estas son las operaciones permitidas por el sistema. Uno puede restringir a un usuario a solamente
realizar ciertas operaciones o tener acceso a todas, dependiendo del almacén en el que trabajan

  ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/tipos_operaciones.png)

**4. Gestión de Productos**

   * Podemos crear nuevos productos que seran agregados al almacén
   
   ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/gestion_producto.png)

**5. Importación y exportación masiva de productos**

   - Excel exportado desde productos, con los campos elegidos.
   
   ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/exportar_informacion.png)

   - Podemos importar informacion desde un archivo .xlsx o un archivo .csv
   
   ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/importar_informacion.png)

**6. Ajustes de Inventario**

   * Al volver a la vista de productos, veremos reflejado el ajuste al ver los nuevos stocks.
   
   ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/ajuste_inventario.png)

**7. Transfrencias Internas**

   * Cuando hacemos click en Tablero, vemos justamente todas las operaciones en proceso. Esto es útil
para poder ver cuantas transferencias hay actualmente en camino a ser concretadas.

  ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/transferencia_realizada.png)

**8. Informes**

   * Odoo nos permite visualizar la valorización de neustro almacén, el stock y movimientos de los productos
   
   ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/informe.png)

**9. Tarea**

   * Los atributos permite que los prouctos tengan mas especificaciones y las unidades de medida establecen la cantidad en la que el producto debe ser vendido
   
     Atributos
     ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/atributos.png)
     
     Unidad de medida     
     ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/unidad_medida.png)
     
   * Las reglas de abastecimiento permiten poner límites en cuanto al stock se refiere, es decir si el stock baja del límite mínimo establecido entonces se nos notifica.

   ![](https://github.com/Ares-Fel/Lab-Integ.-de-Sis.-Empresariales-Avanzado/blob/master/Lab04/regla_abastecimiento.png)

## Conclusiones

* Los produtos al ser en una cantidad masiva generalmente deben poder registrarse rapidamente, Odoo brinda la opcion de importar los productos si se tienen en algun formato de excel o csv, facilitando el registro de estos. Por otro lado permite tambien exportar los productos ya registrados.
* Para poder cambiar la unidad de medidada de algun producto, tiene que estar desactivado o que no haya sido usado en un movimiento de mercancía validado
* Al establecer un nuevo producto se recmienda que se detalle todos los vaores posibles como atributos, unidades de medida, recio, etc. para evitar posibles retrasos por no haber especificado antes.
