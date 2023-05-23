

<p align="middle">
  <a href="https://github.com/antz22/ultimate-guide-to-flutter"><img src="https://github.com/antz22/ultimate-guide-to-flutter/blob/master/assets/banner.svg"></a>
</p>

<p align="center">
  <h2 align="center">MacOS  - Flutter</h2>

  <p align="center">
   Guia completa de instalacion en el sistema operativo MacOS 
  </p>

  <p align="center">
    <a href="https://github.com/antz22/ultimate-guide-to-flutter/stargazers" alt="Stars">
        <img src="https://img.shields.io/github/stars/antz22/ultimate-guide-to-flutter?style=for-the-badge" /></a>
    <a href="https://github.com/antz22/ultimate-guide-to-flutter/network/members" alt="Forks">
        <img src="https://img.shields.io/github/forks/antz22/ultimate-guide-to-flutter?style=for-the-badge" /></a>
    <a href="https://github.com/Solido/awesome-flutter">
        <img alt="Awesome Flutter" src="https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=for-the-badge" />
    </a>
    <a href="https://img.shields.io/badge/flutter-2.2-green" alt="Flutter">
        <img src="https://img.shields.io/badge/flutter-2.2-green?style=for-the-badge" /></a>
    <a href="https://img.shields.io/badge/dart-2.13-green" alt="Flutter">
        <img src="https://img.shields.io/badge/dart-2.13-green?style=for-the-badge" /></a>
  </p>
</p>

## Requerimientos del sistema Operativo MacOS 

Requisitos del sistema
Para instalar y ejecutar Flutter, tu entorno de desarrollo debe cumplir estos requisitos mínimos:

* Sistemas operativos: macOS, versión 10.14 (Mojave) o posterior.

* Espacio en disco: 2,8 GB (no incluye espacio en disco para IDE/herramientas).

* Herramientas: Flutter utiliza git para la instalación y actualización. Recomendamos instalar Xcode, que incluye git, pero también puedes instalar git por separado.


< h2 align="center"  id="Rosseta Software">Rosseta Software <img  src="data:image/jpeg;base64,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"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>


**Rosetta** es un traductor dinámico binario para Mac OS X que permite a muchas aplicaciones PowerPC correr en ciertas arquitecturas [Intel](https://es.wikipedia.org/wiki/X86 "X86") de las computadoras [Macintosh](https://es.wikipedia.org/wiki/Macintosh "Macintosh")
```bash
softwareupdate --install-rosetta
```
```bash
sudo softwareupdate --install-rosetta --agree-to-license
```
<h2 align="center"  id="Xcode Comand line">Xcode Comand line <img  src="https://upload.wikimedia.org/wikipedia/en/5/56/Xcode_14_icon.png"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>



<img src="https://github.com/antz22/ultimate-guide-to-flutter/blob/master/assets/container_style.png">

Xcode es un entorno de desarrollo integrado para macOS que contiene un conjunto de herramientas creadas por Apple destinadas al desarrollo de software para macOS, iOS, watchOS y tvOS.


```bash
sudo Xcode-select --install
```
* Has clic en "Instalar" para comenzar el proceso de descarga e instalación.
* 

> https://mac.install.guide/assets/images/ruby/install-Xcode-CLT-done.png
* 


```bash
xcode-select -p
```

Verás un mensaje de confirmación cuando se complete la instalación.

Comprueba que haya instalado correctamente las herramientas de línea de comandos de Xcode:

```bash
xcode-select -p
```
* Deberías ver lo siguiente:


```bash
/Library/Developer/CommandLineTools
```




<h2 align="center"  id="Homebrew">Homebrew <img  src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Homebrew_logo.svg/1200px-Homebrew_logo.svg.png"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>



<img src="https://github.com/antz22/ultimate-guide-to-flutter/blob/master/assets/container_style.png">

Homebrew es un sistema de gestión de paquetes que simplifica la instalación, actualización y eliminación de programas en los sistemas operativos Mac OS de Apple y GNU/Linux. Creado originalmente por Max Howell, el programa ha ganado popularidad en la comunidad de Ruby on Rails
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
<h2 align="center"  id="Wget">Wget <img  src="https://static-00.iconduck.com/assets.00/wget-icon-512x452-4kl7bsyl.png"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>



GNU Wget es una herramienta libre que permite la descarga de contenidos desde servidores web de una forma simple

```bash
brew install wget

```


<h2 align="center"  id="Curl">Curl <img  src="data:image/png;base64,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"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>

cURL es un proyecto de software consistente en una biblioteca y un intérprete de comandos orientado a la transferencia de archivos. Soporta los protocolos FTP, FTPS, HTTP, HTTPS, TFTP, SCP, SFTP, Telnet, DICT, FILE y LDAP, entre otros
```bash
brew install wget
```

<h2 align="center"  id="Git">Git <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>



GitHub es una forja para alojar proyectos utilizando el sistema de control de versiones Git. Se utiliza principalmente para la creación de código fuente de programas de ordenador. El software que opera GitHub fue escrito en Ruby on Rails. Desde enero de 2010, GitHub opera bajo el nombre de GitHub, Inc.

```bash
brew install git
```


* entre las comillas introducce tu nomebrew de usuario 
```bash
git config --global user.name "Tu nombre"
```

* introduce tu correo electronico
```bash 
git config --global user.email "Tu correo"
```

<h2 align="center"  id="Ruby">Ruby <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>



<img src="https://github.com/antz22/ultimate-guide-to-flutter/blob/master/assets/container_style.png">


RubyGems es un **gestor de paquetes** para el lenguaje de programación **Ruby** que proporciona un formato estándar y autocontenido (llamado gem) para poder distribuir programas o bibliotecas en **Ruby**, una herramienta destinada a gestionar la instalación de estos, y un servidor para su distribución.

--------
Instalacion *Ruby* by Homebrew  con el siguiente comando 

```bash 
brew install ruby
```


-------------
|RubyGems es un gestor de paquetes  | Extension  |
|--|--|
| Git  | [Git](https://github.com/rubygems/rubygems) |
| Gem  |[Gem](https://rubygems----------.org/gems/rubygems-update-3.4.13.gem)  |
|  Zip| [Zip](https://rubygems.org/rubygems/rubygems-3.4.13.zip) |
| Tgz | [Tgz](https://rubygems.org/rubygems/rubygems-3.4.13.tgz)
------------

* Despues de Descargar ell paquete el apquete y ejecutamos el siguiente comando en la terminal de macos  

```bash 
gem update --system
```



---- 


```bash 
gem update --system
```


Descomprimir en un directorio y cd allí y Instalación con: ruby setup.rb

```bash 
ruby setup.rb
```
Para más detalles y otras opciones, consulte:

```bash 
ruby setup.rb --help
```




### Git

GitHub es una forja para alojar proyectos utilizando el sistema de control de versiones Git. Se utiliza principalmente para la creación de código fuente de programas de ordenador. El software que opera GitHub fue escrito en Ruby on Rails. Desde enero de 2010, GitHub opera bajo el nombre de GitHub, Inc.

Once finished, run this command in the terminal to make sure your environment is all ready to go.


```bash
brew install git
rm '/usr/local/bin/git-cvsserver'
brew link --overwrite git
brew install git-lfs
git lfs install
```






<h2 align="center"  id=" Cocopoads"> Cocopoads <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>

Traducción del inglés-CocoaPods es un administrador de dependencias de nivel de aplicación para Objective-C, Swift y cualquier otro lenguaje que se ejecute en el tiempo de ejecución de Objective-C, como RubyMotion, que proporciona un formato estándar para administrar bibliotecas externas.

```bash
sudo gem install cocoapods

```



<h2 align="center"  id="Watchmen">Watchmen <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>


Requerimiento y utiltidada para poder desarollar software en apple watch  asi como interfases y apps 

```bash
brew install git
```






### Pod
Each widget built by Flutter can be passed a number of properties or parameters. As we saw earlier, the Container widget takes in a 'child' property, and it can also take in a 'color' property to define the background color of the Container.

Usually, you can also pass in all of your styles to the widget through the parameter.


<h2 align="center"  id="ffi">ffi <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>

Ruby-FFI es una gema para cargar mediante programación bibliotecas nativas enlazadas dinámicamente, enlazar funciones dentro de ellas y llamar a esas funciones desde código Ruby. Además, una extensión de Ruby-FFI funciona sin cambios en CRuby (MRI), JRuby, Rubinius y TruffleRub

```bash
gem install ffi
```

In Column widgets, you might need to vertically align your objects to the center of the page. Here's how you could do that using the Column widget's 'mainAxisAlignment' property (main axis of the column is vertical). You can also align text horizontally in a column widget using the 'crossAxisAlignment' property.



<h2 align="center"  id="Postman">Postman <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>

Traducción del inglés-Postman es una plataforma API para que los desarrolladores diseñen, construyan, prueben e iteren sus API. En febrero de 2023, Postman informa que tiene más de 25 millones de usuarios registrados y 75 000 API abiertas, lo que, según afirma, constituye el centro de API público más grande del mundo.
Usually, you can also pass in all of your styles to the widget through the parameter.


```bash
brew install --cask postman
```


<h2 align="center"  id="Flutter">Flutter<img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>

<img src="https://github.com/antz22/ultimate-guide-to-flutter/blob/master/assets/container_style.png">

Flutter es un SDK de código fuente abierto de desarrollo de aplicaciones móviles creado por Google. Suele usarse para desarrollar interfaces de usuario para aplicaciones en Android, iOS y Web así como método primario para crear aplicaciones para Google Fuchsia.​
<h2 align="center"  id="Obtenga el SDK de Flutter ">Obtenga el SDK de Flutter <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>


-------------
| Macos Flutter| SDK |
|--|--|
| Macos con procesador Intel   | [Intel](https://storage.googleapis.com/flutter_infra_release/releases/stable/macos/flutter_macos_3.10.1-stable.zip) |
|Macos con procesador Apple Silicon  |[Apple Silicon](https://storage.googleapis.com/flutter_infra_release/releases/stable/macos/flutter_macos_arm64_3.10.1-stable.zipp)  |

------------

2. Extrae el archivo descargado:
   - Navega a la ubicación donde se descargó el archivo y ábrelo.
   - Extrae el contenido del archivo comprimido en la ubicación que prefieras, por ejemplo, en tu directorio de inicio.

```bash
cd ~/development
unzip ~/Downloads/flutter_macos_3.10.1-stable.zip
```
3. Configura las variables de entorno:
   - Abre una terminal.
   - Ejecuta el siguiente comando para abrir el archivo de perfil de tu terminal en un editor de texto:


```bash

export PATH="$PATH:`pwd`/flutter/bin"

```

   - Agrega las siguientes líneas al archivo y guarda los cambios:

```bash
 export PATH="$PATH:[RUTA_DE_FLUTTER]/bin"
     
```

```bash
export PATH="$PATH:[RUTA_DE_FLUTTER]/bin/cache/dart-sdk/bin"
```
 - Reemplaza "[RUTA_DE_FLUTTER]" con la ruta donde extrajiste el archivo de Flutter.
 
  - Cierra y vuelve a abrir la terminal para que los cambios surtan efecto.


4. Verifica la instalación de Flutter:
   - Ejecuta el siguiente comando para verificar si Flutter se instaló correctamente:


```bash
flutter doctor
```

<h2 align="center"  id="Git-Stable">Git-Stable <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>


 - Deberías ver una lista de verificaciones con el estado actual de tu configuración. Si hay algún problema, te mostrará los pasos necesarios para solucionarlo.
Descargar directamente desde GitHub en lugar de utilizar un archivo comprimido
Esto sólo se sugiere para casos de uso avanzado.

También puedes usar git directamente en lugar de descargar el archivo preparado. Por ejemplo, para descargar la rama estable:

content_copy

```bash
 git clone https://github.com/flutter/flutter.git -b estable
```

```bash
flutter precache
```

Actualiza tu ruta, y ejecuta flutter doctor
. Eso te permitirá saber si hay otras dependencias que necesites instalar para usar Flutter (por ejemplo, el SDK de Android).

Si no has utilizado el archivo, Flutter descargará los binarios de desarrollo necesarios a medida que se vayan necesitando (si has utilizado el archivo, están incluidos en la descarga). Es posible que desee descargar previamente estos binarios de desarrollo (por ejemplo, es posible que desee hacer esto al configurar entornos de compilación herméticos, o si sólo tiene disponibilidad de red intermitente). Para ello, ejecute el siguiente comando


```bash
 flutter precache
```

Para más opciones de descarga, consulte la ayuda de flutter precache.

<h2 align="center"  id="Xcode Setup">Xcode Setup <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>

5. En caso de no tener instalado el IDE editor de codigo   Xcode:
   - Abre la Mac App Store.
   - Busca "Xcode" y haz clic en el botón "Obtener" para instalarlo.
   - Sigue las instrucciones en pantalla para completar la instalación.
  

5.1 . Otra manera de hacer la instalacion de Xcode en caso de tenener  una version del sistema operativo macos antigua o verisones anteriores no soportadas por la Appstore puede descargar el IDE  desde la  terminal de  comandos  abriendolo y ejecutando como super usuario  el siguiente comando para poder realizar la descarga 


```bash
 flutter precache
```


6.  Para desarrollar aplicaciones Flutter para iOS, necesitas un Mac con Xcode instalado.Configura Xcode:
   - Abre Xcode.
   - Ve a "Preferencias" en el menú "Xcode".
   - Haz clic en la pestaña "Ubicaciones" y selecciona la versión más reciente de Xcode en "Command Line Tools".

```bash
 sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
```
```bash
 sudo xcodebuild -runFirstLaunch
```

<h2 align="center"  id=" Implantar en dispositivos iOS"> Implantar en dispositivos iOS <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>
Para prepararte para ejecutar y probar tu aplicación Flutter en el simulador de iOS, sigue estos pasos:

En tu Mac, busca el simulador a través de Spotlight o utilizando el siguiente comando:

```bash
 open -a Simulador
```
Asegúrese de que el simulador utiliza un dispositivo de 64 bits (iPhone 5s o posterior). Puede comprobar el dispositivo consultando la configuración en los menús Hardware > Dispositivo o Archivo > Abrir simulador del simulador.
Dependiendo del tamaño de la pantalla de tu máquina de desarrollo, los dispositivos iOS simulados con alta densidad de pantalla podrían desbordar tu pantalla. Coge la esquina del simulador y arrástrala para cambiar la escala. También puedes utilizar las opciones Ventana > Tamaño físico o Ventana > Precisión de píxeles si la resolución de tu ordenador es lo suficientemente alta.

<h2 align="center"  id=" Implantar en dispositivos iOS"> Implantar en dispositivos iOS <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>


Puede omitir este paso si sus aplicaciones no dependen de plugins de Flutter con código nativo de iOS. Instale y configure CocoaPods ejecutando los siguientes comandos:



```bash
 sudo gem install cocoapods

```
 Nota: La versión por defecto de Ruby requiere sudo para instalar la gema CocoaPods. Si está utilizando un gestor de versiones de Ruby, es posible que tenga que ejecutar sin sudo.

Además, si está instalando en un Mac Apple Silicon, ejecute el comando

```bash
 sudo gem install cocoapods

```

Puede omitir este paso si sus aplicaciones no dependen de plugins de Flutter con código nativo de iOS. Instale y configure CocoaPods ejecutando los siguientes comandos:



 Nota: La versión por defecto de Ruby requiere sudo para instalar la gema CocoaPods. Si está utilizando un gestor de versiones de Ruby, es posible que tenga que ejecutar sin sudo.

Además, si está instalando en un Mac Apple Silicon, ejecute el comando

content_copy
 sudo gem uninstall ffi && sudo gem install ffi -- --enable-libffi-alloc
Siga el flujo de firma de Xcode para aprovisionar su proyecto:

```bash
 sudo gem uninstall ffi && sudo gem install ffi -- --enable-libffi-alloc
```
 
Siga el flujo de firma de Xcode para aprovisionar su proyecto:


¡Listo! Ahora tienes Flutter completamente instalado en tu macOS. Puedes comenzar a desarrollar aplicaciones Flutter en tu máquina. Recuerda mantener Flutter y sus dependencias actualizadas periódicamente ejecutando el comando "flutter upgrade" en la terminal. ¡Disfruta de tu experiencia de desarrollo con Flutter!


<h2 align="center"  id="Vizual Code">Vizual Code <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>

### Brew install 

```bash
brew install vscode 

```



Visual Studio Code es un editor de código fuente desarrollado por Microsoft para Windows, Linux, macOS y Web. Incluye soporte para la depuración, control integrado de Git, resaltado de sintaxis, finalización inteligente de código, fragmentos y refactorización de código.

### Extensiones 

La extensión Visual Studio Code **habilita una opción de versión preliminar en directo para ver la página de contenido de los portales dentro de la interfaz de Visual Studio Code durante la experiencia de desarrollo**. en la parte superior derecha cuando se abre un archivo HTML en modo de edición.. 


### Setup & Config

We can use a StreamBuilder for this purpose. A 'Stream' is essentially just a stream of data that we are constantly watching for changes in. One end of the stream is the Firestore database. The other end of the stream is our app. 



<h2 align="center"  id="rosseta-software">Android Studio <img  src="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"  alt="align"  width="35"  height="35" align="center"  href="https://cdn.iconscout.com/icon/free/png-256/free-rubygems-283026.png?f=webp"/></h2>
Descargar Android Studio

Abra cualquier navegador web y vaya a la página de descarga de Android Studio. Esta es la página web de Android Developers, donde puedes descargar Android Studio. Esta página detecta automáticamente su sistema operativo.
Haga clic en Descargar Android Studio. Se abrirá la página de Términos y Condiciones con el Acuerdo de Licencia de Android Studio.
Lea el Acuerdo de licencia.
En la parte inferior de la página, si está de acuerdo con los términos y condiciones, seleccione la casilla de verificación He leído y acepto los términos y condiciones anteriores.
Haz clic en Descargar Android Studio para iniciar la descarga.
Cuando se le solicite, guarde el archivo en una ubicación donde pueda localizarlo fácilmente, como la carpeta Descargas.
Espera a que se complete la descarga. Esto puede llevar un rato y puede ser un buen momento para disfrutar de un té.


Inicie el archivo DMG de Android Studio.
Arrastre y suelte Android Studio en la carpeta Aplicaciones y, a continuación, inicie Android Studio.
Elija si desea importar la configuración anterior de Android Studio y, a continuación, haga clic en Aceptar.
Complete el asistente de configuración de Android Studio, que incluye la descarga de los componentes del SDK de Android necesarios para el desarrollo.
El siguiente vídeo muestra cada paso del procedimiento de configuración recomendado:

A medida que estén disponibles nuevas herramientas y otras API, Android Studio le notificará mediante una ventana emergente. Para comprobar manualmente si hay actualizaciones, haga clic en Android Studio > Buscar actualizaciones.
