---
layout: post
title: Sistema para la gestión y seguimiento de proyectos de desarrollo
categories : productos
image:
---



El software de administración de proyectos es un concepto que describe varios tipos de software, incluyendo programación, asignación de recursos, software de colaboración, comunicación y sistemas de documentación, utilizados para ayudar a organizar un proyecto complejo en diferentes tareas y en un tiempo determinado.

Trac
Trac es un sistema de seguimiento para los proyectos de desarrollo de software y un wiki mejorado. Trac utiliza un enfoque minimalista de la gestión de proyectos de software basado en la web. la creación de enlaces y referencias sin problemas entre bugs, las tareas, el conjunto de cambios entre los archivos y las páginas wiki. Una línea de tiempo muestra todos los eventos de los proyectos actuales y pasados a fin, de obtener una visión general del proyecto y seguimiento de los progresos muy fácil. La hoja de ruta muestra el camino a seguir y la lista de las próximas metas.

Características de Trac
Trac permite el código wiki en las descripciones de los mensajes de confirmación.
La creación de enlaces y referencias sin problemas entre bugs.
Tareas a realizar
el conjunto de cambios entre los archivos y las páginas wiki.
Una línea de tiempo muestra todos los eventos de los proyectos actuales y pasados a fin, de obtener una visión general del proyecto y seguimiento de los progresos muy fácil.
La hoja de ruta muestra el camino a seguir y la lista de las próximas metas.

GIT
Git es un software de control de versiones pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número archivos de código fuente.

Características de GIT
Fuerte apoyo al desarrollo no-lineal, por ende rapidez en la gestión de ramificaciones y mezclado de diferentes versiones. Git incluye herramientas específicas para navegar y visualizar un historial de desarrollo no-lineal. Una presunción medular en Git es que un cambio será fusionado o empalmado mucho más frecuentemente de lo que se escribe originalmente, conforme se pasa entre varios programadores que lo revisan.
Gestión distribuida. Al igual que Darcs, BitKeeper, Mercurial, SVK, Bazaar y Monotone, Git le da a cada programador una copia local del historial del desarrollo entero, y los cambios se propagan entre los repositorios locales. Los cambios se importan como ramificaciones adicionales y pueden ser fusionados en la misma manera que se hace con la ramificación local.
Los almacenes de información pueden publicarse por HTTP, FTP, rsync o mediante un protocolo nativo, ya sea a través de una conexión TCP/IP simple o a través de cifrado SSH. Git también puede emular servidores CVS, lo que habilita el uso de clientes CVS pre-existentes y modulos IDE para CVS pre-existentes en el acceso de repositorios Git.
Los repositorios Subversion y svk se pueden usar directamente con git-svn.
Gestión eficiente de proyectos grandes, dada la rapidez de gestión de diferencias entre archivos, entre otras mejoras de optimización de velocidad de ejecución.
Todas las versiones previas a un cambio determinado, implican la notificación de un cambio posterior en cualquiera de ellas a ese cambio (denominado autenticación criptográfica de historial). Esto existía en Monotone.
Resulta algo más caro trabajar con ficheros concretos frente a proyectos, eso diferencia el trabajo frente a CVS, que trabaja con base en cambios de fichero, pero mejora el trabajo con afectaciones de código que concurren en operaciones similares en varios archivos.
Los renombrados se trabajan basándose en similitudes entre ficheros, aparte de nombres de ficheros, pero no se hacen marcas explícitas de cambios de nombre con base en supuestos nombres únicos de nodos de sistema de ficheros, lo que evita posibles, y posiblemente desastrosas, coincidencias de ficheros diferentes en un único nombre.
Realmacenamiento periódico en paquetes (ficheros). Esto es relativamente eficiente para escritura de cambios y relativamente ineficiente para lectura si el reempaquetado (con base en diferencias) no ocurre cada cierto tiempo.

Subversion
Subversion es un sistema de control de versiones diseñado específicamente para reemplazar al popular CVS. Es software libre bajo una licencia de tipo Apache/BSD y se le conoce también como svn por ser el nombre de la herramienta utilizada en la línea de órdenes. Una característica importante de Subversion es que, a diferencia de CVS, los archivos versionados no tienen cada uno un número de revisión independiente, en cambio, todo el repositorio tiene un único número de versión que identifica un estado común de todos los archivos del repositorio en un instante determinado.

Características de Subversion
Se sigue la historia de los archivos y directorios a través de copias y renombrados.
Las modificaciones (incluyendo cambios a varios archivos) son atómicas.
La creación de ramas y etiquetas es una operación más eficiente. Tiene costo de complejidad constante (O(1)) y no lineal (O(n)) como en CVS.
Se envían sólo las diferencias en ambas direcciones (en CVS siempre se envían al servidor archivos completos).
Puede ser servido mediante Apache, sobre WebDAV/DeltaV. Esto permite que clientes WebDAV utilicen Subversion de forma transparente.
Maneja eficientemente archivos binarios (a diferencia de CVS que los trata internamente como si fueran de texto).
Permite selectivamente el bloqueo de archivos. Se usa en archivos binarios que, al no poder fusionarse fácilmente, conviene que no sean editados por más de una persona a la vez.
Cuando se usa integrado a Apache permite utilizar todas las opciones que este servidor provee a la hora de autentificar archivos (SQL, LDAP, PAM, etc.).

OpenLDAP
OpenLDAP es una implementación libre y de código abierto del protocolo Lightweight Directory Access Protocol (LDAP) desarrollada por el proyecto OpenLDAP. Está liberada bajo su propia licencia OpenLDAP Public License. 
LDAP son las siglas de Lightweight Directory Access Protocol (en español Protocolo Ligero de Acceso a Directorios) que hacen referencia a un protocolo a nivel de aplicación el cual permite el acceso a un servicio de directorio ordenado y distribuido para buscar diversa información en un entorno de red. LDAP también es considerado una base de datos, aunque su sistema de almacenamiento puede ser diferente, a la que pueden realizarse consultas.

Características de OpenLDAP
Soporte LDAPv3 — OpenLDAP soporta la Capa de autenticación y seguridad (SASL), la Seguridad de la capa de transporte (TLS) y la Capa de conexión segura (SSL), entre otras mejoras. Muchos de los cambios en el protocolo desde LDAPv2 han sido diseñados para hacer LDAP más seguro.
Soporte IPv6 — OpenLDAP soporta la próxima generación del protocolo de Internet versión 6.
LDAP sobre IPC — OpenLDAP se puede comunicar dentro de un sistema usando comunicación interproceso (IPC). Esto mejora la seguridad al eliminar la necesidad de comunicarse a través de la red.
API de C actualizada — Mejora la forma en que los programadores se conectan para usar servidores de directorio LDAP.
Soporte LDIFv1 — Provee compatibilidad completa con el formato de intercambio de datos, Data Interchange Format (LDIF) versión 1.
Servidor Stand-Alone mejorado — Incluye un sistema de control de acceso actualizado, conjunto de hilos, herramientas mejoradas y mucho más.
