# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a una red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba 
![image](https://github.com/user-attachments/assets/c7bda143-98ba-4175-b4e9-e616f35e8577)

![image](https://github.com/user-attachments/assets/e44fd70a-61ab-4a0f-9a63-165977dbfb7f)

# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube
