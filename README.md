<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    Formas de Ejecutar Código Java
</head>
<body>
    <h1>Formas de Ejecutar Código Java</h1>
    <p>
        Java es un lenguaje de programación versátil y ampliamente utilizado en el desarrollo de aplicaciones móviles, de escritorio y sistemas empresariales. En esta guía, te mostramos las formas más comunes de ejecutar código Java, cómo instalar el entorno de desarrollo adecuado y configurarlo en tu sistema.<br><br>
    </p>

 <h2>1. Instalación de Java</h2>
    <p>
        Para comenzar a programar en Java, primero debes instalar el Java Development Kit (JDK). Aquí están los pasos para hacerlo:<br><br>
        <strong>Paso 1:</strong> Dirígete a la página oficial de Oracle para descargar la última versión de Java.<br>
        <a href="https://www.oracle.com/java/technologies/javase-downloads.html" target="_blank">Descargar JDK desde Oracle</a><br><br>
        <strong>Paso 2:</strong> Selecciona la versión adecuada para tu sistema operativo (Windows, macOS, Linux) y descarga el instalador.<br><br>
        <strong>Paso 3:</strong> Ejecuta el instalador y sigue las instrucciones para completar la instalación.<br><br>
        <strong>Paso 4:</strong> Configura la variable de entorno <code>JAVA_HOME</code> para que puedas ejecutar comandos Java desde la línea de comandos.<br><br>
        <strong>Nota:</strong> La versión más reciente es la <strong>JDK 21</strong>, y puedes verificar la última versión en el siguiente enlace: 
        <a href="https://www.oracle.com/java/technologies/javase-downloads.html" target="_blank">Última versión de Java JDK</a>
    </p>

<h2>2. Configuración de las Variables de Entorno</h2>
    <p>
        Configurar las variables de entorno permite que puedas ejecutar los comandos de Java en cualquier directorio de tu sistema.<br><br>
        <strong>En Windows:</strong><br>
        1. Accede al Panel de Control y busca "Variables de Entorno".<br>
        2. Añade una nueva variable llamada <code>JAVA_HOME</code> con la ruta de instalación de Java (por ejemplo, <code>C:\Program Files\Java\jdk-XX.X.X</code>).<br>
        3. Modifica la variable <code>PATH</code> para incluir <code>%JAVA_HOME%\bin</code>.<br><br>
        <strong>En macOS/Linux:</strong><br>
        Edita el archivo de configuración <code>.bashrc</code> o <code>.zshrc</code> y agrega las siguientes líneas:<br>
        <code>export JAVA_HOME=/ruta/a/jdk</code><br>
        <code>export PATH=$JAVA_HOME/bin:$PATH</code><br>
        Luego, ejecuta <code>source ~/.bashrc</code> o <code>source ~/.zshrc</code> para que los cambios tomen efecto.<br><br>
    </p>

<h2>3. Formas de Ejecutar Código Java</h2>
    <p>
        Una vez que Java esté instalado y configurado, existen diversas formas de ejecutar tus programas. Aquí te mostramos las más comunes:<br><br>
        <strong>1. Usar un IDE (Entorno de Desarrollo Integrado):</strong><br>
        Herramientas como IntelliJ IDEA, Eclipse, NetBeans** y VS Code ofrecen un entorno completo para escribir, compilar y ejecutar programas Java de manera eficiente.<br><br>

 <strong>2. Desde la línea de comandos:</strong><br>
        Puedes compilar y ejecutar tu código Java utilizando los comandos de la terminal. Para compilar un archivo Java, usa:<br>
        <code>javac MiPrograma.java</code><br>
        Y para ejecutarlo, usa:<br>
        <code>java MiPrograma</code><br><br>

<strong>3. Con herramientas online:</strong><br>
        Si prefieres no instalar nada, puedes ejecutar código Java en plataformas online como JDoodle, Replit, o Compiler Explorer.<br><br>

 <strong>4. Usando un editor de texto y terminal:</strong><br>
        Otra opción es escribir el código en un editor como VS Code o Sublime Text, compilarlo y ejecutarlo desde la terminal.<br><br>
    </p>

<h2>4. Descarga y Uso de IDEs</h2>
    <p>
        Aquí te presentamos algunos de los IDEs más populares para programar en Java:<br><br>
        - NetBeans: Un IDE gratuito y de código abierto que incluye todo lo necesario para desarrollar, depurar y ejecutar aplicaciones Java. Descárgalo desde: 
        <a href="https://netbeans.apache.org/download/index.html" target="_blank">Descargar NetBeans</a><br><br>
        
  - **VS Code (Visual Studio Code):** Un editor ligero y altamente personalizable, que se puede configurar para trabajar con Java mediante extensiones. Descárgalo desde:
        <a href="https://code.visualstudio.com/" target="_blank">Descargar VS Code</a><br>
        Luego, instala la extensión "Java Extension Pack" desde el Marketplace dentro de VS Code para comenzar a programar en Java.<br><br>
    </p>
    <h2>5. Te recomiendo que instales IntelliJ IDEA</h2>
    <p>
        Si buscas un IDE potente, fácil de usar y con muchas características que te ayudarán a mejorar tu productividad al programar en Java, te recomiendo encarecidamente que instales IntelliJ IDEA. Este IDE es uno de los más populares entre los desarrolladores de Java, ofreciendo características avanzadas como:<br><br>
        - Soporte para refactorización de código: Puedes reestructurar tu código sin perder su funcionalidad.<br>
        - Integración con herramientas de control de versiones: Como Git y SVN, facilitando el trabajo en equipo y el manejo de versiones.<br>
        - Asistente de depuración: Te ayuda a detectar y corregir errores de manera eficiente.<br><br>
        - IntelliJ IDEA es ideal tanto para principiantes como para desarrolladores avanzados. Puedes descargar la versión gratuita desde su página oficial:
        <a href="https://www.jetbrains.com/idea/download/" target="_blank">Descargar IntelliJ IDEA</a><br><br>
    </p>

    <h2>5. Tutorial Guía: Aprende a Ejecutar Código Java</h2>
    <p>
        Para ayudarte a empezar de manera sencilla y efectiva, te recomendamos seguir este tutorial guiado que te enseña desde los primeros pasos hasta ejecutar tu primer programa Java. El video está diseñado para principiantes, explicando de forma clara y detallada cómo configurar tu entorno y ejecutar tu código. Haz clic en el siguiente enlace para verlo:
        <a href="https://www.youtube.com/watch?v=4WKo13f2Qpc" target="_blank">Tutorial: Cómo ejecutar código Java</a><br><br>
    </p>

    <h2>6. Enlaces Útiles</h2>
    <p>
        - [Descargar JDK desde Oracle](https://www.oracle.com/java/technologies/javase-downloads.html)<br>
        - [Documentación oficial de Java](https://docs.oracle.com/en/java/)<br>
        - [IDE IntelliJ IDEA (Descarga gratuita)](https://www.jetbrains.com/idea/download/)<br>
        - [Plataforma JDoodle para Java](https://www.jdoodle.com/)<br>
        - [Descargar NetBeans](https://netbeans.apache.org/download/index.html)<br>
        - [Descargar VS Code](https://code.visualstudio.com/)<br>
        - [Última versión de Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html)<br>
        - [Tutorial en YouTube sobre cómo ejecutar código Java](https://www.youtube.com/watch?v=4WKo13f2Qpc)<br>
    </p>
</body>
</html>


    
