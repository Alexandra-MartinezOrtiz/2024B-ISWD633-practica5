# Aprendizajes antes y después de la práctica

Antes de la práctica:

Conocimiento básico de Docker y Docker Compose: servicios, redes, volúmenes.
Familiaridad general con SonarQube y PostgreSQL, pero sin experiencia directa en su configuración con contenedores.
Después de la práctica:

Docker Compose: Configuración avanzada de múltiples servicios, uso de variables de entorno, redes compartidas y volúmenes para persistencia de datos.
Conexión de servicios: Uso de SONAR_JDBC_URL para conectar SonarQube con PostgreSQL y manejo de dependencias con depends_on y healthcheck.
Solución de problemas: Resolución de errores comunes como conflictos de puertos y conexión entre servicios, utilizando herramientas como docker ps y docker-compose logs.
Problemas solucionados
Error de conexión entre SonarQube y PostgreSQL:

Causa: Configuración incorrecta de SONAR_JDBC_URL.
Solución: Ajuste de la URL para usar el nombre del servicio postgres.
SonarQube no accesible desde el navegador:

Causa: Puerto mal configurado.
Solución: Mapeo correcto del puerto 9000 en docker-compose.yaml.
Beneficios para la formación profesional
Infraestructura como código (IaC): Experiencia en entornos reproducibles con Docker Compose.
DevOps: Configuración de herramientas como SonarQube para análisis estático de código.
Resolución de problemas: Diagnóstico eficiente en entornos de contenedores.
Escalabilidad: Preparación para trabajar en equipos con configuraciones compartibles y escalables.
