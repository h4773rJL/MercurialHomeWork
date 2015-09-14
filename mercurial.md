## Tarea en Grupo.
### Tuxes
### José Luis Pérez Rendón

# Concurrent Versions System CVS


# Mercurial
Software Libre para el control de versiones, es multiplataforma, dedicado para desarrolladores de software, principalmente para el lenguaje de programación Python, incluye una implementación de *diff*. Originalmente fue escrito para funcionar en Linux, peor ha sido adaptado para Windows, Mac OS X, y la mayoría de otros sistemas tipo Unix.
Esta pensado para linea de comandos, las operaciones se invocan como opciones del comando hg, cuyo nombre hace referencia al símbolo químico del mercurio.

Las metas del desarrollo de Mercurial incluyen un gran rendimiento y escalabilidad, desarrollo completamente distribuido sin necesidad de un servidor, gestión robusta de archivos de texto como binarios y capacidades avanzadas de ramificación e integración.

## Historia
El creador y desarrollador principal de Mercurial es Matt Mackall. El código fuente se encuentra disponible bajo los términos de la licencia GNU GPL versión 2, lo que clasifica a Mercurial como software libre, Mackall hizo pública la existencia de Mercurial el 19 de abril de 2005.

El anuncio de Bitmover, de retirar la versión gratuita de BitKeeper fue el motivo por el cual, Mackall decidió escribir su propio sistema de control de versiones, ya que se había estado usando BitKeeper debido a los requisitos de control de versiones del proyecto del núcleo Linux. Este proyecto comenzó aproximadamente al mismo tiempo que otro denominado **git**, iniciado por el propio Linus Torvalds con objetivos similares.

El proyecto Linux decidió usar **Git** en lugar de **Mercurial**. Sin embargo, muchos otros proyectos usan este último.

## Características 

## Ejemplos de uso
desde la consola de comandos ejecutar hg


```
linux-i06o:/home/h4773r # hg
Mercurial Distributed SCM

basic commands:

 add           add the specified files on the next commit
 annotate      show changeset information by line for each file
 clone         make a copy of an existing repository
 commit        commit the specified files or all outstanding changes
 diff          diff repository (or selected files)
 export        dump the header and diffs for one or more changesets
 forget        forget the specified files on the next commit
 init          create a new repository in the given directory
 log           show revision history of entire repository or files
 merge         merge another revision into working directory
 pull          pull changes from the specified source
 push          push changes to the specified destination
 remove        remove the specified files on the next commit
 serve         start stand-alone webserver
 status        show changed files in the working directory
 summary       summarize working directory state
 update        update working directory (or switch revisions)

(use "hg help" for the full list of commands or "hg -v" for details)

```

Para determinar la versión de hg que estamos utilizando, ejecutar:

```
hg version
Mercurial Distributed SCM (version 3.5)
(see http://mercurial.selenic.com for more information)

Copyright (C) 2005-2015 Matt Mackall and others
This is free software; see the source for copying conditions. There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

```

Mercurial necesitará un nombre-de-usuario para grabar los **commits**. Lo mejor es configurar Mercurial con tu correo electrónico lo cual creará el archivo .ghrc1 en tu directorio home 



