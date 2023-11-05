# SonarLinst

1. Instalar la extensión "Sonar Lint" en VsCode
2. Crear un HTML con su plantilla: **Ctrl + spacio**
3. Experimentar con scripts los errores y sugerencias: app.js, sample.py

# SonarQube

## Instalación de SonarQube

1. Instalar Java y actualizar la variable de entorno a la nueva ruta:

-  Java versión 11:
        - (https://www.oracle.com/co/java/technologies/javase/jdk11-archive-downloads.html) 
        - Path: C:\Program Files\Java\jdk-17 en **JAVA_HOME"
        - Verificar la versión instalada: **java -version**

2. Instalar Sonar y actualizar la variable de entorno a la nueva ruta:

-   Descargar SonarScanner:
    -   https://docs.sonarsource.com/sonarqube/latest/analyzing-source-code/scanners/sonarscanner/
    - Path: C:\Sonarqube\sonar-scanner-5.0.1.3006-windows\bin
    - Verificar la versión instalada:  **sonar-scanner --version**

-   Descargar la versión gratuita de "Comminity Edition":
    -   (https://www.sonarsource.com/products/sonarqube/downloads/)
    -   Ejecutar como administrador:  C:\Sonarqube\sonarqube-10.2.1.78527\bin\windows-x86-64
    - Verificar si carga el URL: **http://localhost:9000/**
    Nota: Usuario = Contraseña = admin
    - Cambiar contraseña, quedaran así:
        - Usuario:      admin
        - Contraseña:   admin123

## Configurar de SonarQube

https://www.youtube.com/watch?v=6pLj3KVglFA 

1. Abrir sonar-scanner-properties:

    - Abrir C:\Sonarqube\sonar-scanner-5.0.1.3006-windows\conf\sonar-scanner

2. Configurar sonar-scanner

3. Ir a D:\Uniandes\2023_Sem4_Ciclo2_Metricas\modernizacionsoft\microservicio1_users y escribir
    **cmd** y se abrira lo siguiente

Microsoft Windows [Versión 10.0.19045.3570]
(c) Microsoft Corporation. Todos los derechos reservados.

C:\Sonarqube\modernizacionsoft\microservicio1_users>>

3. Generar el token en la sección de "Security"

4. Ir a la dirección URL y ejecutar "sonar-scanner -Dsonar.login=...  ..."

Microsoft Windows [Versión 10.0.19045.3570]
(c) Microsoft Corporation. Todos los derechos reservados.

C:\Sonarqube\modernizacionsoft\microservicio1_users>sonar-scanner -Dsonar.login=squ_21984bcde668113c0de392bd6869dbe99dc52e4f