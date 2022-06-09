# Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables
Creación de una cuenta de almacenamiento de Azure con los servicios de Blob, Azure files, Queue y Tables

![Logo de Almacenamiento](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/almacenamiento.jpg)

## Requisitos

- Cuenta de [Azure](https://portal.azure.com/) con suscripción activa
- Computadora con Windows, Linux o MacOs

---------------------------------------------------------

## Pasos

- Se inicia sesión en la página de [Azure](https://portal.azure.com/)

![Inicio Azure](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/inicio%20Azure.PNG)

- Se busca "Cuentas de almacenamiento" y se presiona enter

![P10-1](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-1.PNG)

- Se da click en el botón de "crear"

![P10-2](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-2.PNG)

- En el apartado "grupo de recursos" se selecciona "crear nuevo", se le da un nombre y se presiona "aceptar"

![P10-3](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-3.PNG)

- Más abajo se le coloca un nombre a la cuenta de almacenamiento, se seleccion la región y se selecciona "revisar y crear".

![P10-4](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-4.PNG)

- Se espera que se realice la validación y se active el botón de "crear", una vez activado se presiona.

![P10-5](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-5.PNG)

- Se mostrará una ventana indicando que está en proceso de creación:

![P10-6](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-6.PNG)

- Una vez creado se mostrará una ventana como la siguiente, se presiona "ir a recurso"

![P10-7](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-7.PNG)


#### Creación de almacenamiento Blob


- En el menú lateral izquierdo se busca y selecciona "contenedores"

![P10-8](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-8.PNG)

- Se selecciona "+ contenedor"

![P10-9](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-9.PNG)

- Se le coloca un nombre y el nivel de acceso público se pone "conetenedor con acceso anónimo de lectura" y da click en el notón "crear"

![P10-10](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-10.PNG)

- Se mostrará el contenedor que acabamos de crear como en la siguiente imagen, se da click en él.

![P10-11](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-11.PNG)

- Abrirá otra ventana, seleccionamos "cargar"

![P10-12](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-12.PNG)

- Hacemos click en el ícono de la carpeta en el nuevo submenú, seleccionamos los archivos a subir y luego se da click en el botón "cargar"

![P10-13](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-13.PNG)

- En este caso se subió un archivo comprimido .zip y un archivo html de una página web estática

- Los archivos subidos se mostrarán de la siguiente forma

![P10-14](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-14.PNG)

- Si se desea compartir el link de donde esta alojado el archivo, se da click en el archivo requerido y se copia el link que se muestra en pantalla:

![P10-15](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-15.PNG)

- En el caso del archivo html, se comparte de la misma forma, pero al abrirlo por medio de su respectivo link se abre como si fuera una página web estática:

![P10-17](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-17.PNG)

- Otra foorma de montar un sitio web estático es la siguiente:

- Se regresa al menú inicial de la cuenta de almacenamiento

![P10-18](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-18.PNG)

- En el menú lateral izquierdo se selecciona "sitio web estático"

![P10-19](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-19.PNG)

- Seleccionamos l opción "habilitado"

![P10-20](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-20.PNG)

- Se le coloca un nombre y se le da en "guardar"

![P10-21](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-21.PNG)

- Después en esa misma pestaña se mostrará el link de acceso a la página web estática

![P10-22](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-22.PNG)


#### Creación de almacenamiento compartido (Azure File Storage)


- Se selecciona en la menú lateral izquierdo de la cuenta de almacenamiento "Recursos compartidos de archivos"

![P10-23](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-23.PNG)

- Se selecciona "+ recurso compartido de archivos"

![P10-24](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-24.PNG)

- En la pestaña que se abre, se coloca el nombre y se da click en el botón "crear"

![P10-25](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-25.PNG)

- Se mostrará el recurso compartido creado, se da click en él

![P10-26](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-26.PNG)

- Se da click en "cargar"

![P10-27](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-27.PNG)

- Se selecciona el archivo a cargar por medio del ícono de carpeta y se da click en "cargar"

![P10-28](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-28.PNG)

- Se procede a dar click en "conectar"

![P10-29](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-29.PNG)

- Aparecerá un submenú a la derecha, seleccionamos "windows"

![P10-30](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-30.PNG)

- En método de autenticación se selecciona "clave de la cuenta de almacenamiento" y se copia el código mostrado en la ventana por medio del botón copiar indicado en part inferior derecha de la siguiente imagen:

![P10-31](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-31.PNG)

- Se abre una terminal de powershell en windows, se pega el código copiado y se da enter

![P10-32](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-32.PNG)

- Comenzará un proceso de ejecución, al finalizar mostrará un anuncio como el siguiente:

![P10-33](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-33.PNG)

- Ahora si nos dirigimos al explorador de archivos de windows se mostrará la nueva unidad de alamcenamiento de Azure files que acabamos de crear

![P10-34](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-34.PNG)

- Se vuelve al menú del recurso de la cuenta de almacenamiento:

![P10-35](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-35.PNG)


#### Creación de Queue


- En el menú lateral izquierdo de la cuenta de almacenamiento se busca "colas" y se da click

![P10-36](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-36.PNG)

- Se da click en "+ cola"

![P10-37](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-37.PNG)

- Se le coloca un nombre y se da click en "aceptar"

![P10-38](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-38.PNG)

- Ahora se mostrará la cola creada, se da click en ella

![P10-39](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-39.PNG)

- Ahora se da click en "agregar mensaje"

![P10-40](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-40.PNG)

- Se le coloca un texto, se marca la casilla de "no expira nunca" y se da click en "aceptar"

![P10-41](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-41.PNG)

- Ahora se mostrará el mensaje dentro de la cola

![P10-42](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-42.PNG)

- Si se desea se pueden crear más mensajes, en este caso se creó uno más y se añadió a la cola, quedando así:

![P10-43](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-43.PNG)

- Se regresa al menú de la cuenta de almacenamiento

![P10-44](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-44.PNG)


#### Creación de tables


- En el menú lateral izquierdo de la cuenta de almacenamiento se da click en "Tablas"

![P10-45](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-45.PNG)

- Se da click en "+ tabla"

![P10-46](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-46.PNG)

- Se le coloca un nombre y se da click en "aceptar"

![P10-47](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-47.PNG)

- Para modificar la tabla, en el menú lateral izquierdo se selecciona "Explorador de almacenamiento (versión preliminar)"

![P10-48](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-48.PNG)

- Se da click en "tablas" y luego en el nombre la tabla que acabamos de crear

![P10-50](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-50.PNG)

- Se da click en "agregar entidad"

![P10-51](https://github.com/AlanAlvaradoR/Azure-cuentas-almacenamiento-Blob-AzureFiles-Queue-Tables/blob/main/imagenes/P10-51.PNG)

- Se mostrará una ventana donde se pueden agreagar y modificar los datos en la tabla




