 # Cloud Data Processing
 ---
> Bitácora de análisis de grandes volúmenes de datos.
>Julian Azael Mex Dominguez
---

## Tareas 
Tarea #N 998 Arquitectura de Aplicación
![Arquitectura de la aplicación](https://github.com/AzaelMD115/clouddataprocessing/blob/main/arquitectura%20para%20una%20aplicacion.png?raw=true)

###Tarea #N 999
PY3 
<img width="489" height="211" alt="Image" src="https://github.com/user-attachments/assets/b70fda63-1b7b-49b1-8450-f6f51b16bc8c" />

Parrot 
<img width="1693" height="949" alt="Image" src="https://github.com/user-attachments/assets/57a286e0-1c61-479e-84ec-0ff4400ff73c" />

Docker  
<img width="1918" height="1013" alt="Image" src="https://github.com/user-attachments/assets/b4ed2e82-4d40-482a-9e32-344c573d9955" />


### Tarea #997 Investigar sobre Pizza as a service 2.0
https://azaelmd115.github.io/index.html

### Tarea #996 Investigacion
https://azaelmd115.github.io/solucion_problemas_tic.html

### Tarea #994 Hola mundo en docker 
[![hola-mundo)[agg https://asciinema.org/a/rDeFfFb4PjMfHO7w demo.gif)]

---
## Apuntes

### 10/06/2026 — Contenedores y virtualización

**Niveles de abstracción**
<img width="1918" height="1013" alt="Image" src="https://github.com/user-attachments/assets/2df9b799-9ce2-4216-8800-57b37135703f" />

- Los contenedores son **efímeros**: cuando terminan de ejecutarse, se detienen (se "mueren").
- Un contenedor crea un entorno para ejecutar scripts de forma efectiva **sin necesidad de instalar todo el sistema operativo**.

**Vagrant**

- Sirve para definir las características específicas de VirtualBox y de los *boxes* (plantillas de sistemas operativos).
- Automatiza la creación de servidores y ambientes de prueba.
- No usar en producción (a menos que seas tú el creador del *box*).

**Docker**

- **Docker Hub**: repositorio de plantillas de contenedores (*images*).
- Para crear una imagen se necesita un `Dockerfile`, que se especifica a partir de una imagen base:

```dockerfile
FROM <nombre_de_la_imagen_base>
CMD echo "hola mundo"
```

Comandos básicos:

```bash
docker build . -t hola   # Construye la imagen y la etiqueta (-t) como "hola"
docker images            # Muestra tus imágenes
docker run hola          # Crea y ejecuta el contenedor; al terminar, se detiene
docker ps -a             # Muestra todos los contenedores
```

- Para configurar varios servicios se utiliza `docker-compose`.

---

### Seguridad en la nube de AWS

> AWS Academy Cloud Foundations

**Modelo de responsabilidad compartida**

*Responsabilidad del **cliente** (seguridad EN la nube):*

- Cifrado de datos, protección de datos y protección del tráfico
- Listas de control de acceso (ACL) y grupos de seguridad
- Configuración de red
- Implementación de autenticación multifactor (MFA)
- Aplicación correcta de contraseñas y acceso basado en roles
- Sistema operativo de la instancia de Amazon EC2

*Responsabilidad de **AWS** (seguridad DE la nube):*

- Cómputo, almacenamiento, bases de datos y redes
- Regiones, zonas de disponibilidad y centros de datos
- Infraestructura de hardware y software
- Infraestructura de red
- Infraestructura de virtualización

**Modelos de servicio**

`IaaS` — Infraestructura como servicio (servicios administrados por el cliente):

- Amazon EC2
- Elastic Block Store (EBS)
- Virtual Private Cloud (VPC)

`PaaS` — Plataforma como servicio (servicios administrados por AWS):

- AWS Lambda
- Amazon Relational Database Service (Amazon RDS)
- AWS Elastic Beanstalk

---

### Redes — Direccionamiento IP

- **DNS**
- Ejemplo: `192.0.2.0`

| Versión | Tamaño  | Estructura                                            |
| ------- | ------- | ----------------------------------------------------- |
| IPv4    | 32 bits | Identificador de red (`192.0.2`) + Host (flexible)    |
| IPv6    | 128 bits | —                                                    |
---
## Proyectos

### Calculadora Inteligente de Adoquines
https://proyecto-adoquines.vercel.app/

### Exposición apache-hive
https://tuxtter.github.io/diapositivas/apache-hive/#/

