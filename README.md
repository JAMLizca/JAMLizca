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
<img src="https://desarrolloweb.com/storage/collection_images/actual/0wLchbKtPUumIKGjaGAVPYQT2ADz20xQMkjyTUBY.jpg" alt="Logo de java" width="500">
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
        <a href="https://netbeans.apache.org/download/index.html" target="_blank">Descargar NetBeans</a><br>
        
-VS Code (Visual Studio Code): Un editor ligero y altamente personalizable, que se puede configurar para trabajar con Java mediante extensiones. Descárgalo desde:
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
        <hr width="36%" >
<p align = "center">
	<img src = "https://github.com/7oSkaaa/7oSkaaa/blob/output/github-contribution-grid-snake.svg?" alt = "Snake Game"/>
</p>
    </p>
<h1><p><strong><em style="font-size: 250px;">🚀✨ ¡Daremos inicio con <span style="color: #007bff;">Java desde cero</span>! 🖥️💡 #AprendamosJuntos 🎓</em></strong></p></h1>
 <h1>Fundamentos de Java</h1>
        <p>Guía básica para comenzar con el lenguaje de programación Java.</p>
    </header>

<main>
        <section>
            <h2>¿Qué es Java?</h2>
           <img src="https://docpath.com/wp-content/uploads/benefits-of-using-java-programming-language.jpg" alt="Logo de Java" width="500">
            <p>Java es un lenguaje de programación orientado a objetos desarrollado por Sun Microsystems (ahora parte de Oracle). Es conocido por su portabilidad, ya que permite ejecutar el mismo código en diferentes plataformas gracias a la máquina virtual de Java (JVM).</p>
        </section>

   <section>
            <h2>Hola Mundo en Java</h2>
            <p>El programa más básico para empezar a programar en Java es "Hola Mundo". A continuación, se muestra cómo se escribe:</p>
            <pre>
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("¡Hola Mundo!");
    }
}
            </pre>
        </section>

   <section>
            <h2>Características principales de Java</h2>
            <ul>
                <li><strong>Orientado a objetos:</strong> Todo en Java se organiza en clases y objetos.</li>
                <li><strong>Portabilidad:</strong> Gracias a la JVM, el código se puede ejecutar en cualquier plataforma.</li>
                <li><strong>Seguro:</strong> Java tiene características integradas como el manejo de memoria automática para evitar errores comunes.</li>
                <li><strong>Multihilo:</strong> Permite ejecutar múltiples tareas al mismo tiempo dentro de un programa.</li>
            </ul>
        </section>

   <section>
            <h2>Tipos de datos en Java</h2>
    link: https://www.youtube.com/watch?v=82UVmKJ0txw
<p>Java cuenta con varios tipos de datos básicos:</p>
            <table border="1" cellspacing="0" cellpadding="5">
                <thead>
                    <tr>
                        <th>Tipo</th>
                        <th>Tamaño</th>
                        <th>Ejemplo</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>int</td>
                        <td>4 bytes</td>
                        <td>123</td>
                    </tr>
                    <tr>
                        <td>double</td>
                        <td>8 bytes</td>
                        <td>123.45</td>
                    </tr>
                    <tr>
                        <td>char</td>
                        <td>2 bytes</td>
                        <td>'A'</td>
                    </tr>
                    <tr>
                        <td>boolean</td>
                        <td>1 bit</td>
                        <td>true/false</td>
                    </tr>
                </tbody>
            </table>
        </section>

  <section>
            <h2>Comentarios en Java</h2>
            <p>Los comentarios son útiles para documentar el código y no son ejecutados por el programa. Hay tres tipos:</p>
            <pre>
// Comentario de una línea
/* comentarios para varias lineas de codigo */
            </pre>
        </section>
    </main>
  <footer>
        <p>&copy; 2024 Fundamentos de Java. Todos los derechos reservados.</p>
    </footer>

  </body>
</html>


    
