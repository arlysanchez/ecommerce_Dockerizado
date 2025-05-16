FROM openjdk:11-jre-slim

# Crear directorio de la aplicación con el nombre requerido
RUN mkdir /ecommerce-app

# Puerto expuesto (manteniendo 8084)
EXPOSE 8084

# Copiar el JAR desde el target al contenedor
COPY target/ecommerce-0.0.1-SNAPSHOT.jar /ecommerce-app/app.jar

# Comando de ejecución
CMD ["java", "-jar", "/ecommerce-app/app.jar"]
