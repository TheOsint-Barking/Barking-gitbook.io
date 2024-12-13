# 🔩 Configuración del entorno

Te recomiendo tener una máquina dedica de host Linux para sus investigaciones OSINT. Te recomiendo, kali linux, Parrot os, Debian o Pop os

Aunque tengas Kali Linux, tendrás que instalar VirtualBox ([virtualbox.org](http://virtualbox.org/)) para emular Windows o tal vez otra distribución Linux&#x20;

VMWare ahora ofrece el software Workstation Pro completamente gratis para uso personal, pero requiere que des tus datos, (puedes dar datos fake) asegúrese de comprender sus propios requisitos.

### Windows

La mayoría de ustedes poseerán una computadora basada en Windows o tal vez Mac OS pero por el momento no me enfocare en ello. Esta es la opción menos favorita para este tipo de trabajo, pero todos debemos lidiar con cualquier limitación presentada por nuestros empleadores, economia actual o nuestra propia comodidad dentro de un sistema operativo. para ello necesitaremos hacer uso de maquinas virtuales.

Las máquinas virtuales llevan a cabo la virtualización de un sistema informático en particular. Son sistemas operativos de computadora sobre sistemas operativos de computadoras. Por lo general, un programa de software se ejecuta dentro de un sistema operativo, y los sistemas operativos individuales pueden iniciarse dentro de ese programa. Cada máquina virtual es independiente de la otra y del sistema operativo host. El entorno de una máquina virtual no tiene ningún impacto en ninguna otra. En pocas palabras, es una forma de tener numerosas computadoras dentro de su sola computadora. Puede investigar de forma segura un solo objetivo dentro de un entorno seguro sin contaminación de otras investigaciones. Podrá clonar una máquina virtual original en cuestión de minutos y ya no tendrá que preocuparse por los virus persistentes, las cookies de seguimiento o las pruebas sobrantes.

1. **Recomiendo hacer un borrado o restauración del fabricante** he instar todas las actualizaciones disponibles y desinstalar programas inútiles esto es para tener la computadora “limpia” uno nunca sabe, si se tiene un programa espía o tu empleador te dio un equipo he instalo algo raro.
2. **Antivirus y antimalware** con Windows Defender predeterminado es suficiente muchos diran que recopilan tus datos personales, pero veo mas viable tener algo gratis que comprar una licencia de algún antivirus además que usaras una maquina virtual para investigaciones y si llega a pasar algo simplemente borrar la maquina virtual instalada y la vuelves a ejeuctar.
3. **Telemetría** recomiendo encarecidamente a los usuarios que intenten minimizar la cantidad de datos que Microsoft recopila sobre el uso de su computadora. Por ello descarga la ultima versión de O\&O Shut Up 10++ en [https://www.oo](https://www.oo/) [software.com/en/shutup10](http://software.com/en/shutup10) instale e inicie el software.
4. **Mejor el rendimiento** [https://github.com/hellzerg/optimizer](https://github.com/hellzerg/optimizer)
5. **Limpiador del sistema** usa BleachBit ([bleachbit.org](http://bleachbit.org/)). BleachBit es muy similar a CCleaner, pero puede ser un poco más agresivo. Selecciono todas las opciones disponibles con la excepción de "Limpiar espacio sin limpiar". Si eliges esta opción, se sobrescribiría todo el espacio libre en el disco duro, lo que lleva mucho tiempo.
6. **Configuración de VPN** Las redes privadas virtuales no son una solución perfecta para el anonimato. Es importante tener en cuenta que las VPN te ofrecen privacidad, no anonimato. recomiendo Proton VPN o Mullvad VPN
7. **Administrador de contraseñas** recomiendo KeePassXC, Bitwarden o Proton Pass
8. Entornos que recomiendo para virtualizar: Kali Linux, Parrot os, Debian.
9. si tu ordenador soporta Hyper v puedes correr: kali linux o Debian sin necesidad de Virtualbox o VMWare



### **Configuración de VirtualBox**

1. Haga clic en "Máquina" y luego en "Nuevo" en el menú.
2. Introduzca un nombre de "osint work".
3. Haga clic en el menú desplegable de la sección "Imagen ISO"; seleccione "Otro"; y elija el archivo ISO.
4. Habilite la opción "Omitir instalación desatendida" y haga clic en "Siguiente".
5. Elija un tamaño de memoria de la mitad de la memoria de su sistema.
6. Cambie el/los "Procesador(es)" a la mitad de las CPU disponibles.
7. Anule la selección de "Habilitar EFI" y haga clic en "Siguiente".
8. Elija el tamaño máximo deseado de su VM como 150 GB y haga clic en "Siguiente" y luego en "Finalizar".
9. Haga clic en "Configuración" para esta nueva máquina virtual.
10. Haga clic en la pestaña "Avanzado" y habilite "Bidireccional", "Portapapeles compartido" y "Arrastrar y soltar".
11. Haga clic en "Carpetas compartidas" en el menú de la izquierda y haga clic en el icono "Más" a la derecha.
12. En "Ruta de la carpeta", haga clic en el menú desplegable y seleccione "Otro".
13. Elija la carpeta Descargas y haga clic en "Abrir".
14. Habilite la opción "Auto Montar" y haga clic en "Aceptar".
15. Haga clic en "Aceptar" para guardar todos los cambios y cerrar la configuración.
16. Haga clic en la opción "Inicio" y arranque la máquina virtual.
17. Si la pantalla es demasiado pequeña, haga clic en "Ver" en el menú de VirtualBox y seleccione "Pantalla Virtual 1" > "Escalar al 200%". La mayoría de los usuarios NO necesitarán hacer esto.
18. actualice, `sudo apt update && sudo apt upgrade -y` cambie el idioma `sudo dpkg-reconfigure locales` y los colores a negro
