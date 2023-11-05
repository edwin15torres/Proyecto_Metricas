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

1. Abrir

    - Abrir C:\Sonarqube\sonar-scanner-5.0.1.3006-windows\conf\sonar-scanner

2. 




    https://www.youtube.com/watch?v=6pLj3KVglFA