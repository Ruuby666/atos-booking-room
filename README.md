#El codigo es privado por derechos de empresa.

# Sistema de Reservas de Salas de Atos

## Descripción General

Documentación del sistema **Atos Booking Room**, una solución diseñada para gestionar la reserva de salas en la compañía Atos, la aplicación está diseñada para ser intuitiva, segura y flexible, adaptándose a las necesidades de los usuarios. En el menú de la derecha se encuentran los enlaces a las diferentes secciones de la documentación.


---


## Características Principales

1. **New Booking**:
   - Realizar reservas de salas.
   - Consultar información detallada de las salas (capacidad, características, etc).
   - Guardar salas como favoritas para facilitar futuras reservas.
   - Restricción: las reservas pueden realizarse con un máximo de dos semanas de antelación.

2. **My Booking**:
   - Visualizar las reservas activas en tiempo presente.
   - Gestionar las reservas actuales (modificar o cancelar).

3. **My History**:
   - Consultar el historial de reservas pasadas.
   - Ordenar las reservas pasadas por semanas o meses.
   - Acceso rápido a las salas favoritas.

4. **Admin**:
   - Acceso exclusivo para usuarios con rol de administrador.
   - Permite gestionar las funcionalidades avanzadas de la aplicación, como la administración de salas y usuarios.
   - Navegación entre las secciones de **Manage Rooms** y **Manage Admins** mediante pestañas.

       **Manage Rooms**
     - **Gestión de Salas**:
       - Crear nuevas salas con detalles como nombre, capacidad, características y asignación a un piso específico.
       - Editar salas existentes, incluyendo cambios en sus características o ubicación.
       - Eliminar salas que ya no estén en uso.
     - **Búsqueda y Filtros**:
       - Buscar salas por su ID o nombre.

       - Filtrar salas por edificio o piso.
     - **Interfaz Intuitiva**:
       - Formulario dinámico para la creación y edición de salas.
       - Vista previa de las salas recientemente editadas.

       **Manage Admins**
     - **Gestión de Administradores**:
       - Visualizar la lista de administradores actuales.
       - Añadir nuevos administradores seleccionando usuarios existentes.
       - Eliminar permisos de administrador a usuarios específicos.
     - **Búsqueda y Selección**:
       - Buscar usuarios por su DAS ID, nombre, apellido o correo electrónico.
       - Filtrar usuarios que no sean administradores ni el usuario actual.
     - **Confirmación de Acciones**:
       - Modal de confirmación para añadir o eliminar administradores.
       - Validación para evitar duplicados en la lista de administradores.
     - **Interfaz Intuitiva**:
       - Botón para alternar entre la vista de añadir administradores y la lista actual.
       - Indicadores visuales para usuarios seleccionados y acciones realizadas.



5. **Seguridad**:
   - Integración con el sistema de Single Sign-On (SSO) de Atos.
   - Temporalmente, se utiliza **Keycloak** como proveedor de autenticación.

---

## Estado del Proyecto

El sistema se encuentra en **estado de desarrollo**
![image](https://github.com/user-attachments/assets/5ed7d9bb-dd8e-4880-a0b7-a272f69ea18f)
![image (1)](https://github.com/user-attachments/assets/5f92f8cf-1fd4-4ea1-8555-78402b493115)
![image (2)](https://github.com/user-attachments/assets/2640e318-b2aa-4f1f-b8e1-12644e62f1ea)
![image (3)](https://github.com/user-attachments/assets/19eecf69-c44f-4da9-8b47-64f963b7624e)
![image (4)](https://github.com/user-attachments/assets/a858e4f6-f86d-46f9-88bc-c41e6ae32b57)
![image (5)](https://github.com/user-attachments/assets/2e3e732c-cc73-475e-afcd-02c607492e37)
![image (6)](https://github.com/user-attachments/assets/a3f50c88-c4e0-4d58-9554-77e698520768)
![image (7)](https://github.com/user-attachments/assets/da111586-09e2-4d47-80d7-79a962aa434e)
![image (8)](https://github.com/user-attachments/assets/99da41c3-d30b-445d-b03a-2855024adafe)
![image (9)](https://github.com/user-attachments/assets/5de2f6ec-a3bc-4000-a82d-288562d51207)
![image (10)](https://github.com/user-attachments/assets/bd8fa3a2-fa6a-48a8-afca-0e93d7c28596)
![image (11)](https://github.com/user-attachments/assets/34d61078-618d-425b-8353-5aacd4bf0f7a)
![image (12)](https://github.com/user-attachments/assets/dd9d47da-eecb-46e0-bd40-2783692166e6)
![image (13)](https://github.com/user-attachments/assets/a0c18958-8b54-45af-acd0-16816b73c401)
![image (14)](https://github.com/user-attachments/assets/261f97ff-2993-4def-9d50-15ad60516428)
![image (15)](https://github.com/user-attachments/assets/82f0b956-fbd2-4113-ab97-c3ced3afb455)
![image (16)](https://github.com/user-attachments/assets/77e662b2-571b-430b-bafa-5790a9af1b49)
![image (17)](https://github.com/user-attachments/assets/c5711223-61d7-46b8-855d-4058724ebba3)


