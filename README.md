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
    <img src="https://www.codtronic.com/wp-content/uploads/2022/10/jdk.png" width="450"><br>
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
    Configurar las variables de entorno permite que puedas ejecutar los comandos de Java en cualquier directorio de tu sistema.
</p>
<table>
    <tr>
        <th>Sistema Operativo</th>
        <th>Pasos</th>
    </tr>
    <tr>
        <td><strong>Windows</strong></td>
        <td>
            <ol>
                <li>Accede al Panel de Control y busca "Variables de Entorno".</li>
                <li>Añade una nueva variable llamada <code>JAVA_HOME</code> con la ruta de instalación de Java (por ejemplo, <code>C:\Program Files\Java\jdk-XX.X.X</code>).</li>
                <li>Modifica la variable <code>PATH</code> para incluir <code>%JAVA_HOME%\bin</code>.</li>
            </ol>
        </td>
    </tr>
    <tr>
        <td><strong>macOS/Linux</strong></td>
        <td>
            <ol>
                <li>Edita el archivo de configuración <code>.bashrc</code> o <code>.zshrc</code> y agrega las siguientes líneas:</li>
                <ul>
                    <li><code>export JAVA_HOME=/ruta/a/jdk</code></li>
                    <li><code>export PATH=$JAVA_HOME/bin:$PATH</code></li>
                </ul>
                <li>Ejecuta <code>source ~/.bashrc</code> o <code>source ~/.zshrc</code> para que los cambios tomen efecto.</li>
            </ol>
        </td>
    </tr>
</table>



<h2>Formas de Ejecutar Código Java</h2>
<img src="https://desarrolloweb.com/storage/collection_images/actual/0wLchbKtPUumIKGjaGAVPYQT2ADz20xQMkjyTUBY.jpg" alt="Logo de IntelliJ IDEA" width="500">
<p>
    Una vez que Java esté instalado y configurado, existen diversas formas de ejecutar tus programas. Aquí te mostramos las más comunes:
</p>
<table>
    <tr>
        <th>Método</th>
        <th>Descripción</th>
    </tr>
    <tr>
        <td><strong>Usar un IDE</strong></td>
        <td>Herramientas como IntelliJ IDEA, Eclipse, NetBeans y VS Code ofrecen un entorno completo para escribir, compilar y ejecutar programas Java.</td>
    </tr>
    <tr>
        <td><strong>Desde la línea de comandos</strong></td>
        <td>Compila y ejecuta tu código Java utilizando los comandos de la terminal:<br>
            <code>javac MiPrograma.java</code><br>
            <code>java MiPrograma</code>
        </td>
    </tr>
    <tr>
        <td><strong>Con herramientas online</strong></td>
        <td>Puedes ejecutar código Java en plataformas online como JDoodle, Replit, o Compiler Explorer.</td>
    </tr>
    <tr>
        <td><strong>Usando un editor de texto y terminal</strong></td>
        <td>Escribe el código en un editor como VS Code o Sublime Text, compílalo y ejecútalo desde la terminal.</td>
    </tr>
</table>


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
<img src="https://www.bestnetsoft.com/wp-content/uploads/2024/04/IntelliJ_IDEA-1024x260.png" alt="Logo de IntelliJ IDEA" width="500"><br>
    <p>IntelliJ IDEA es un IDE potente y fácil de usar, recomendado para mejorar la productividad al programar en Java. Es popular entre los desarrolladores de Java por sus características avanzadas:
        <br><br>
        -Refactorización de código: Permite reestructurar el código sin perder funcionalidad.<br>
        - Integración con herramientas de control de versiones: Como Git y SVN, facilitando el trabajo en equipo y el manejo de versiones.<br>
        -Integración con control de versiones: Compatible con herramientas como Git y SVN, facilitando el trabajo en equipo..<br> 
        - Asistente de depuración: Ayuda a detectar y corregir errores eficientemente. Puedes descargar la versión gratuita desde su página oficial:
        <a href="https://www.jetbrains.com/idea/download/" target="_blank">Descargar IntelliJ IDEA</a><br><br>
    </p>

 <h2>5. Tutorial Guía: Aprende a Ejecutar Código Java</h2>
    <p>El video está diseñado para principiantes, explicando de forma clara y detallada cómo configurar tu entorno y ejecutar tu código. Haz clic en el siguiente enlace para verlo:
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


    
