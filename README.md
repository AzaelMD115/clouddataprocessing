 # Cloud Data Processing
 ---
> Bitácora de análisis de grandes volúmenes de datos.
>Julian Azael Mex Dominguez
---

## Tareas 
Tarea #N 998 Arquitectura de Aplicación
![Arquitectura de la aplicación](https://github.com/AzaelMD115/clouddataprocessing/blob/main/arquitectura%20para%20una%20aplicacion.png?raw=true)

Tarea #N 999
PY3 
<img width="489" height="211" alt="Image" src="https://github.com/user-attachments/assets/b70fda63-1b7b-49b1-8450-f6f51b16bc8c" />

Parrot 
<img width="1693" height="949" alt="Image" src="https://github.com/user-attachments/assets/57a286e0-1c61-479e-84ec-0ff4400ff73c" />

Docker  
<img width="1918" height="1013" alt="Image" src="https://github.com/user-attachments/assets/b4ed2e82-4d40-482a-9e32-344c573d9955" />


---
## Apuntes

> 10/06/2026
Los contenedores son efimeros porque cuando terminan de 
niveles de abstraccion
Maquina fisica -> Maquina virtual -> Contenedor 

Crea un entorno para poder ejecutar scripts de manera efectiva sin necesidad de instalar todo el sistema operativo por ejemplo 

Vagrant = sirve para definir las caracterisiticas espeficicas de virtualbox y virtual boxes(plantillas de sistemas operativos 
Esto sirve para autimatizar la creacion de servidores y ambientes de prueba(no usar en produccion a menos de ser tu el creador del box)

Docker hub = Plantillas de contenedores(images)
Para crear una imagen se necesita un dockerfile y se espedifica a partir de una imagen base 
  From -nombre de la imagen base- 
  CMD echo"hola mundo"
docker buid . -t hola
docker images  # Muestra tu imagen 
docker run hola  # crea el contenedor, ejecuta el contenedor y cuando termina de ejecutarse se muere) 
docker ps -a #nuestra los contenedores 

Para configurar los servicios se utliza el dockercompose

docker-compose.

---
## Proyectos
