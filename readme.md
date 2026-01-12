# Evaluación de sistema
## SAGA (Sistema automatizado de gestión de archivo)

### Objetivo:
Consulta, alta y baja de expedientes y documentos del archivo.

### Público objetivo:
Empleados

## Análisis funcional, qué se puede hacer? ✅
### Administrador

https://sagaip.sfa.michoacan.gob.mx/roles
- Listar los usuarios disponibles
![alt text](image.png)
- Asignar roles a usuarios
![alt text](image-1.png)

https://sagaip.sfa.michoacan.gob.mx/users
![alt text](image-2.png)
- Crear usuarios
![alt text](image-3.png)
-Editar usuarios
![alt text](image-4.png)
- Eliminar usuarios
![alt text](image-5.png)

https://sagaip.sfa.michoacan.gob.mx/usersSystemRoles
![alt text](image-6.png)
- Se listan todos los usuarios en el sistema y se les puede asignar un rol "administrativo" dentro del sistema
![alt text](image-7.png)



## qué no se puede hacer? ❌
- Navegar por el escritorio virtual
- Consulta de archivo
- 








### Errores
La principal limitante es la imposibilidad de navegar a través del escritorio virtual con culquier rol, sea del sistema o no.


### Rol: Ciudadano
- Se creó un usuario con los siguientes datos:
![alt text](image-8.png)
Se asignaron todos los roles:
![alt text](image-10.png)
- Al hacer login con el usuario la pagina no muestra nada y no se puede navegar
![alt text](image-9.png)
- Intentar navegar desde la barra de busqueda hasta el endpoint /virtuaDesktop tampoco funciona
![alt text](image-11.png)

- Todos los roles de administrador de sistema asignados:
![alt text](image-12.png)
