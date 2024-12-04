# 🔩 Configuración del entorno

Te recomiendo tener una máquina dedica de host Linux para sus investigaciones OSINT, en especial Kali Linux, es mucho más confiable que ejecutar una máquina virtual Linux presentará la menor cantidad de errores de software y de rendimiento. en caso no tenerla sigue bajando.

Aunque tengas Kali Linux, tendrás que instalar VirtualBox ([virtualbox.org](http://virtualbox.org/)) para emular Windows, o quieres tener otra maquina virtual como [https://www.tracelabs.org/initiatives/osint-vm](https://www.tracelabs.org/initiatives/osint-vm).

VMWare ahora ofrece el software Workstation Pro completamente gratis para uso personal, pero requiere que des tus datos, (puedes dar datos fake) asegúrese de comprender sus propios requisitos.

### Windows

La mayoría de ustedes poseerán una computadora basada en Windows o tal vez Mac OS pero por el momento no me enfocare en ello. Esta es la opción menos favorita para este tipo de trabajo, pero todos debemos lidiar con cualquier limitación presentada por nuestros empleadores o nuestra propia comodidad dentro de un sistema operativo. para ello necesitaremos hacer uso de maquinas virtuales.

Las máquinas virtuales llevan a cabo la virtualización de un sistema informático en particular. Son sistemas operativos de computadora sobre sistemas operativos de computadoras. Por lo general, un programa de software se ejecuta dentro de un sistema operativo, y los sistemas operativos individuales pueden iniciarse dentro de ese programa. Cada máquina virtual es independiente de la otra y del sistema operativo host. El entorno de una máquina virtual no tiene ningún impacto en ninguna otra. En pocas palabras, es una forma de tener numerosas computadoras dentro de su sola computadora. Puede investigar de forma segura un solo objetivo dentro de un entorno seguro sin contaminación de otras investigaciones. Podrá clonar una máquina virtual original en cuestión de minutos y ya no tendrá que preocuparse por los virus persistentes, las cookies de seguimiento o las pruebas sobrantes.

1. **Recomiendo hacer un borrado o restauración del fabricante** he instar todas las actualizaciones disponibles y desinstalar programas inútiles esto es para tener la computadora “limpia” uno nunca sabe, si se tiene un programa espía o tu empleador te dio un equipo he instalo algo raro.
2. **Antivirus y antimalware** con Windows Defender predeterminado es suficiente muchos diran que recopilan tus datos personales, pero veo mas viable tener algo gratis que comprar una licencia de algún antivirus además que usaras una maquina virtual para investigaciones y si llega a pasar algo simplemente borrar la maquina virtual instalada y la vuelves a ejeuctar.
3. **Telemetría** recomiendo encarecidamente a los usuarios que intenten minimizar la cantidad de datos que Microsoft recopila sobre el uso de su computadora. Por ello descarga la ultima versión de O\&O Shut Up 10++ en [https://www.oo](https://www.oo/) [software.com/en/shutup10](http://software.com/en/shutup10) instale e inicie el software.
4. **Limpiador del sistema** usa BleachBit ([bleachbit.org](http://bleachbit.org/)). BleachBit es muy similar a CCleaner, pero puede ser un poco más agresivo. Selecciono todas las opciones disponibles con la excepción de "Limpiar espacio sin limpiar". Si eliges esta opción, se sobrescribiría todo el espacio libre en el disco duro, lo que lleva mucho tiempo.
5. **Configuración de VPN** Las redes privadas virtuales no son una solución perfecta para el anonimato. Es importante tener en cuenta que las VPN te ofrecen privacidad, no anonimato. recomiendo Proton VPN o Mullvad VPN
6. **Administrador de contraseñas** recomiendo KeePassXC, Bitwarden o Proton Pass
7. Maquinas virtuales para Windows: VirtualBox y Kali WSL (si tu equipo cuenta con los requisitos)
8. entornos que recomiendo: Kali Linux, Debian, Pop Os
