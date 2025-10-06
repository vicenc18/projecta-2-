# Encàrrec urgent: Recuperació d’accés a Zorin OS

Després de la primera feina exitosa, us arriba un **encàrrec urgent** que obliga a posar-vos-hi per donar-li solució.

Com a fase prèvia, rebreu una **formació sobre seguretat lògica** que us permetrà tenir els coneixements necessaris per afrontar la tasca.

---

## Situació del client

Ha arribat a la consultora un **equip provinent d’un client** que necessita que solucionem un problema concret:

- **Portàtil amb Zorin OS** (Linux amb entorn gràfic) utilitzat habitualment per un directiu.  
- **Problema:** el directiu ha oblidat la contrasenya i és necessari recuperar l’accés.  
- **Motiu:** hi ha documentació molt important que cal recuperar.

---

## Mesura de seguretat

Per evitar que una acció catastròfica pugui danyar l’equip original:

- El disc del portàtil ha estat **clonat en un disc virtual**.  
- Tota la recuperació es farà sobre aquest disc virtual, garantint la seguretat de l’equip físic.

---

## Procediment inicial

1. Crear una **màquina virtual** i connectar-hi el disc clonat.  
2. Entrar a la màquina virtual i **identificar el nom de l’usuari existent**.  
3. Assignar-li una **nova contrasenya**.

---

## Fortificació del sistema

Quan el client és informat del senzill que és accedir a l’equip, demana si hi ha alguna manera de **fortificar el sistema**, ja que té por que si algú roba el portàtil hi pugui accedir a la informació.

- Investigació del procediment per tal que l’accés al **GRUB quedi protegit per contrasenya** per evitar canvis de configuració.  
- Configuració de la màquina virtual per fortificar l’accés al GRUB.  
- Documentació del procediment en un document (incloure imatges) per pujar al repositori.  

---

## Procediment individual

- Vulnereu l’accés al GRUB del Linux.  
- Identifiqueu l’usuari del sistema.  
- Modifiqueu la contrasenya de l’usuari i verifiqueu que ara ja té accés.  
- Investigueu com es pot fortificar l’accés al GRUB. És molt important indicar les fonts d’informació utilitzades.  
- Configureu la màquina virtual per fortificar l’accés al GRUB.  
- Documenteu tot el procediment en un document amb imatges i pugeu-lo al repositori.

---

## Material de suport

- Disc virtual.  
- Apunts RA1AA4 Seguretat Lògica.  
- Guies: *Recuperant Password en Linux*.
