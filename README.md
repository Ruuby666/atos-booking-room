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

![image](https://github.com/user-attachments/assets/9585511f-4a96-4d6d-ad00-a6b5c07aad3d)
![image](https://github.com/user-attachments/assets/8a6b164a-f804-47e2-ad2c-3bd5167096ba)
![image](https://github.com/user-attachments/assets/4f1d4114-9df5-4865-99c1-2982920f3ac6)
![image](https://github.com/user-attachments/assets/abf0dc26-c7e2-4462-9951-ea8d86538f67)
![image](https://github.com/user-attachments/assets/0bddb33e-8ebf-4055-b081-1ce08a8f5ad6)
![image](https://github.com/user-attachments/assets/ae5f98e8-7ea5-43cd-8561-3936487802c9)
![image](https://github.com/user-attachments/assets/6fb8a0af-387d-4c47-af22-26ee56d3b7d8)
![image](https://github.com/user-attachments/assets/16dfa0c6-6b37-475d-bbbd-8da6fce71ce6)
![image](https://github.com/user-attachments/assets/1cda5224-cbe2-442c-ac69-a3722ed91288)
![image](https://github.com/user-attachments/assets/4747246f-10bd-4591-aeda-76bc7c662d84)
![image](https://github.com/user-attachments/assets/eb3fdc89-7081-4683-ab7f-ad0e24f4d9fc)
![image](https://github.com/user-attachments/assets/57368369-3eff-450f-877d-7df0daa54436)
![image](https://github.com/user-attachments/assets/eff1f5b8-7c01-45b3-af02-781261450c34)
![image](https://github.com/user-attachments/assets/c251c48d-3986-4601-8957-48edd81a42ac)
![image](https://github.com/user-attachments/assets/ee73b4ac-eb88-476e-b145-9643620d35e1)
![image](https://github.com/user-attachments/assets/0741b742-aa1f-4815-a691-3b1a76763c44)
![image](https://github.com/user-attachments/assets/d3f7fb8b-f58e-44b9-a9b2-3c184bf6a9f0)
![image](https://github.com/user-attachments/assets/57a812e3-e7e9-4049-bbc9-fc997d5c274a)
![image](https://github.com/user-attachments/assets/3859abfd-795c-4432-8aec-a67206a5d7a8)
