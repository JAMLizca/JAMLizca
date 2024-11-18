<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    Formas de Ejecutar Código Java
</head>
<body>
    <h1>Formas de Ejecutar Código Java</h1>
     <h2>1. Instalación de Java</h2>
    <p>
        Sigue estos pasos para instalar Java en tu computadora:<br><br>
        <strong>Paso 1:</strong> Visita la página oficial de Oracle para descargar el JDK (Java Development Kit).<br>
        <a href="https://www.oracle.com/java/technologies/javase-downloads.html" target="_blank">Descargar JDK desde Oracle</a><br><br>
        <strong>Paso 2:</strong> Selecciona la versión que corresponde a tu sistema operativo (Windows, macOS, Linux) y descarga el instalador.<br><br>
        <strong>Paso 3:</strong> Ejecuta el instalador y sigue las instrucciones para completar la instalación.<br><br>
        <strong>Paso 4:</strong> Configura la variable de entorno <code>JAVA_HOME</code> en tu sistema para que puedas ejecutar comandos de Java desde la línea de comandos.<br>
    </p>
   <h2>2. Configuración de las Variables de Entorno</h2>
    <p>
        Configura las variables de entorno para usar Java desde la terminal o consola:<br><br>
        <strong>En Windows:</strong><br>
        1. Abre el Panel de Control y busca "Variables de Entorno".<br>
        2. Agrega una nueva variable llamada <code>JAVA_HOME</code> con la ruta donde instalaste Java (por ejemplo, <code>C:\Program Files\Java\jdk-XX.X.X</code>).<br>
        3. Agrega <code>%JAVA_HOME%\bin</code> al PATH en las variables del sistema.<br><br>
        <strong>En macOS/Linux:</strong><br>
        Edita el archivo <code>.bashrc</code> o <code>.zshrc</code> y añade:<br>
        <code>export JAVA_HOME=/ruta/a/jdk</code><br>
        <code>export PATH=$JAVA_HOME/bin:$PATH</code><br>
        Guarda los cambios y ejecuta <code>source ~/.bashrc</code> o <code>source ~/.zshrc</code>.<br><br>
    </p>
    <h2>3. Formas de Ejecutar Código Java</h2>
    <p>
        Una vez que Java esté instalado y configurado, puedes ejecutar tus programas de varias formas:<br><br>
        <strong>1. Usar un IDE (Entorno de Desarrollo Integrado):</strong><br>
        Herramientas como IntelliJ IDEA, Eclipse o NetBeans ofrecen un entorno completo para escribir, compilar y ejecutar programas Java.<br><br>
        <strong>2. Desde la línea de comandos:</strong><br>
        Utiliza el compilador <code>javac</code> para compilar el archivo Java y el comando <code>java</code> para ejecutarlo:<br>
        <code>javac MiPrograma.java</code><br>
        <code>java MiPrograma</code><br><br>
        <strong>3. Con herramientas online:</strong><br>
        Plataformas como JDoodle, Replit o Compiler Explorer permiten ejecutar código Java directamente desde el navegador.<br><br>
        <strong>4. Usando un editor de texto y terminal:</strong><br>
        Escribe tu código en un editor como VS Code o Sublime Text, compílalo y ejecútalo desde la terminal.<br>
    </p>
    <h2>4. Enlaces Útiles</h2>
    <p>
        - [Descargar JDK desde Oracle](https://www.oracle.com/java/technologies/javase-downloads.html)<br>
        - [Documentación oficial de Java](https://docs.oracle.com/en/java/)<br>
        - [IDE IntelliJ IDEA (Descarga gratuita)](https://www.jetbrains.com/idea/download/)<br>
        - [Plataforma JDoodle para Java](https://www.jdoodle.com/)<br>
    </p>
</body>
</html>

    
