### Sistema de Gestión para Peluquería Canina "CANINA ESTÉTICA"🐩
### Descripción del Proyecto:
El sistema es una aplicación diseñada para la peluquería canina "CANINA ESTÉTICA". Su objetivo principal es almacenar y gestionar los datos de las mascotas clientes y sus dueños a través de un formulario intuitivo y fácil de usar. La aplicación permite registrar información detallada, como:
![image](https://github.com/user-attachments/assets/5777a219-3df5-4aa3-aeea-a7932f8fd089)

## Datos de la mascota:

Número de cliente

Nombre del perro

Raza

Color

Alergias

Atención especial

Observaciones

Datos del dueño:

ID del dueño

Nombre del dueño

Número de celular

La aplicación cuenta con una interfaz gráfica de usuario (GUI) que facilita la interacción y el manejo de los datos. Toda la información se almacena en una base de datos, permitiendo a los empleados acceder y gestionar los registros en el futuro.

Diseño de la Interfaz de Usuario
1. Interfaz de Carga de Datos
Título: "Carga De Datos"
![image](https://github.com/user-attachments/assets/7fe3e59d-72c3-4d2d-824d-12ffef678e87)

Campos de Entrada:
![image](https://github.com/user-attachments/assets/f0d38d48-d2a8-4fc0-840e-40ba292aee4c)

Nombre del perro (Ejemplo: 'David')

Raza (Ejemplo: 'Border Collie')

Color (Ejemplo: 'Negro y Blanco')

Alérgico (Ejemplo: 'No')

Atención Especial (Ejemplo: 'Sí')

Nombre del Dueño (Ejemplo: 'Keury')

Celular del Dueño (Ejemplo: '8099903199')

Observaciones (Campo opcional)

Botones:

Limpiar: Borra todos los campos de entrada.

Cancelar: Cancela la operación actual.

Guardar: Guarda la información ingresada.

Mensaje de Confirmación: "Se guardó Correctamente" (indica que los datos se han guardado con éxito).

2. Interfaz de Visualización de Datos
Título: "Visualización de Datos"
![image](https://github.com/user-attachments/assets/6f01f75c-c87a-4fd2-8bc5-f8cde6f29852)

Tabla de Datos:

Encabezados:

Num: Número de registro.

Nombre: Nombre del perro.

Color: Color del perro.

Raza: Raza del perro.

Alérgico: Indica si el perro es alérgico.

At. Esp: Atención especial, si el perro necesita cuidados especiales.

Dueño: Nombre del dueño.

Cel: Número de celular del dueño.

Filas de Datos: Cada fila representa un registro de un perro con la información correspondiente. Por ejemplo:

Nombre: David

Color: Negro y Blanco

Raza: Border Collie

Alérgico: No

At. Esp: Sí

Dueño: Keury

Cel: 8099903199

Barra de Herramientas:

Iconos para funcionalidades como modificación o eliminación de registros.

3. Interfaz de Modificación de Datos
Título: "Modificación De Datos"
![image](https://github.com/user-attachments/assets/4ba9b552-36f2-47b6-8148-1af7fb97d14b)

Botones:

Limpiar: Borra todos los campos de entrada.

Buscar: Permite buscar un registro específico para modificar.

Guardar Cambios: Guarda las modificaciones realizadas en los datos.

Mensaje de Confirmación: "Edición Realizada correctamente".
![image](https://github.com/user-attachments/assets/5c150196-e8fd-4df2-bcb3-1544b4cd58ea)

4. Eliminación de Registros
Al seleccionar la opción de eliminar un registro, se muestra un mensaje de confirmación: "Mascota eliminada correctamente".
![image](https://github.com/user-attachments/assets/b3f805ab-5a5b-4767-bdad-39e43e8c674c)

## Funcionalidades Principales
Cargar Datos: Permite ingresar nuevos registros de mascotas y dueños.

Ver Datos: Muestra los registros almacenados en una tabla.

Modificar Datos: Permite editar la información de un registro existente.

Eliminar Registros: Elimina un registro de la base de datos.

Salir: Cierra la aplicación.

## Tecnologías Utilizadas

Lenguaje de Programación: [Java]<a href="https://www.java.com/en/">
    <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>
  </a>


Base de Datos: [Wamserver]<a href="https://www.wampserver.com/en/" target="_blank">
    <img src="https://img.shields.io/badge/WampServer-FF8800.svg?style=for-the-badge&logo=windows&logoColor=white" 
      alt="WampServer"/> 
</a>


## Instalación y Uso

Clona este repositorio:

bash
Copy
git clone https://github.com/tu-usuario/canina-estetica.git
Instala las dependencias necesarias:

bash
Copy
pip install -r requirements.txt
Ejecuta la aplicación:

bash
Copy
python main.py
### Contribuciones👌

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, sigue estos pasos:

Haz un fork del repositorio.

Crea una rama con tu nueva funcionalidad (git checkout -b nueva-funcionalidad).

Realiza tus cambios y haz commit (git commit -m 'Añade nueva funcionalidad').

Haz push a la rama (git push origin nueva-funcionalidad).

Abre un Pull Request.
