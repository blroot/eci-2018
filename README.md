# Material de curso ECI 2018


## Contenido

El material est� armado a partir de archivos de texto plano, con formato en markdown.

Pueden leerlo directamente, o pueden utilizar los scripts dentro de `utils` para armar la presentaci�n.

Si quieren ver las f�rmulas que aparecen como `$ ... $` pueden verlas en la presentaci�n o pegando el contenido en [AsciiMath](http://www.asciimath.org/).


### Lunes

Arrancamos viendo la arquitectura de software que utilizamos cl�sicamente para utilizar GPUs.

- [Introducci�n](intro.md)
- [Arquitectura de software](arquitecture-soft.md)
- [Librer�as: OpenGL, WebGL, Metal, DirectX](libs.md)
- [Lenguajes de programaci�n: GLSL, MetalSL, HLSL](langs.md)
- [Pipeline de gr�ficos: de tri�ngulos a pixels](pixels.md)


### Martes

Vemos la arquitectura de hardware, que explica por qu� todo es tan raro.
Y lo que no llegamos a cubrir el lunes.

- [Tessellation](tess.md)
- [Percepci�n](percepcion.md)
- [Geometr�a](geometria.md)
- [Transformaciones](transform.md)
- [Arquitectura de ejemplo: GCN](gcn.md)
- [Unidades programables](programables.md)
- [Unidades de funci�n fijas](fijas.md)
- [Memoria y cach�s](caches.md)
- [Performance Intro](performance-intro.md)


### Mi�rcoles

Representaciones aproximadas de realidad, f�sica y arte.

- [Representaciones](representaciones.md)
- [Animaci�n](animacion.md)


### Jueves

Aplicaci�n a aprendizaje de m�quina: redes neuronales, inferencia, entrenamiento.

- [Aprendizaje de m�quina](ml.md)
- [Frameworks](frameworks.md)
- [Inferencia](eval.md)
- [Modelos de programaci�n](modelos-prog.md)
- [Color](color.md)


### Viernes

Aplicaci�n a rendering: t�cnicas, color, etc.

- [vcpkg](vcpkg.md)
- [Performance](performance.md)
- [Mallas](meshes.md)
- [C�maras](camaras.md)
- [Dispositivos M�biles](mobile.md)
- [Escenas](escenas.md)
- [Trabajo Pr�ctico](tp.md)


## Preparado de presentaci�n

Los siguientes scripts pueden utilizarse para armar la presentaci�n, incluyendo dependencias en contenido externo.

- `external\download.py`: baja im�genes y videos, arma clips
- `utils\presentacion.py`: arma la presentaci�n (asumiendo que corri� download) con alg�n contenido particular, y la ejecuta

Para conseguir todo el software, pueden utilizar algo como [Chocolatey](https://chocolatey.org/). Por ejemplo, una vez disponible, desde una consola de administraci�n, pueden correr los siguientes comandos.

```
choco install ffmpeg
choco install firefox
choco install git
choco install nodejs
choco install python2
choco install python3
choco install sysinternals
choco install vlc
choco install youtube-dl
```

Las siguientes son herramientas �tiles a la hora de preparar material, pero no necesarias para correr la presentaci�n.

```
choco install anaconda3
choco install blender
choco install emacs
choco install graphviz
choco install inkscape
```

## Preguntas

Si tienen preguntas adicionales o encuentran problemas con el material, prueben abrir un item en

https://github.com/mlrdevgit/eci-2018/issues

