# recuperacio de la contrasenya 
## 1 configuracio de maquina virtual 
Haurem de afegir un dics a la maquina virtual 

![captura de com afegir un disc a la maquina virtual ](IMG/captura1.png)

A qui haruem de selecionar el disc que volem posrar

![captura de com afegir un disc a la maquina virtual ](IMG/captura2.png)

## 2 recuparacio de contrasenya
# iniciar la maquina virtual
Al inizar la maquina virtual haurem de fer shift + una lletre 

Haurem de selecionar la  opcio advance configuration from zorin


![captura de la acio](IMG/image(1).png)

Seleciona la segona opcio 



## 3.Despues de aixo en portara a una cunsola
selecionarem la opcio de root!

![captura de la acio](IMG/resume.png)

![captura de la acio](IMG/rooot3.png)

Despues de seleciona root haurem de escriure un text a la consola que es MOUNT -RW -O RUMOUT /
per despres escrure  PASSWD el usuari que voleu canviar la contrasenya 

![captura de la acio](IMG/mount.png)

Hara canviarem la contrasenya per un altre que tingui mes de 8 digits 

![captura de la acio](IMG/NUEVA2.png)

Despues de renovar la contrasenya intentem inisar sesio amb lusuari
## 4.rebestiment del grub
### investigacio de com rebesti el grub 
A qui deixo algunes guies de co fero, a part de que farem nosaltres 
# Recursos sobre cómo establecer una contraseña en GRUB

## [Puerto53](https://puerto53.com)
**Tutorial paso a paso** para establecer una contraseña en **GRUB** usando el comando `grub2-setpassword`.

---

## [José Web](https://jose-web.es)
**Guía** para poner una contraseña en **GRUB** y proteger el acceso al menú de arranque.

---

## [Computer New Age](https://computernewage.com)
**Explicación** sobre cómo habilitar la protección por contraseña en el cargador de arranque **GRUB**.

---

## [Máquinas Virtuales – Blog Virtualización](https://blogvirtualizacion.com)
**Instrucciones** para configurar una contraseña en **GRUB** utilizando `grub-md5-crypt`.

---

## [Salta Cybersecurity Club](https://saltacybersecurity.club)
**Análisis de seguridad** en **GRUB** y cómo protegerlo contra accesos no autorizados.


---

## [Red Hat Documentation](https://docs.redhat.com)
**Documentación oficial** de **Red Hat** sobre comandos de **GRUB** y cómo acceder a él en modo de usuario único.

### Pas 1 Quan  estem a dintre de zorin obrir una termilan, i escriurem  SUDO NANO /ETC/GRUB.a/40_CUSTOM

![captura de la acio](IMG/custom.png)
### Pas 2 modificar el arxiu, haurem de posar SET SUPERUSERS="EL USUARI EN QUE ESTAS" 
PASSWORD_PBKDF2 USUARI

![captura de la acio](IMG/grub2.png)

### Pas 3 completar la linea de codi amb el sh de la contrasenya

![captura de la acio](IMG/ultima.png)

# FI DE LA GUIA 
## MOLTES GRACIES 
