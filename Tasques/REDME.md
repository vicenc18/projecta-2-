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
Per tant, el primer pas serà crear una màquina virtual a la que connectareu aquest disc. A continuació, cal que entreu a la màquina virtual, trobeu el nom de l’usuari existent i assigneu-li una contrasenya nova.

Quan el client és informat del senzill que és accedir a l’equip, demana si n’hi ha alguna manera de fortificar el sistema, ja que té por que si algú roba el portàtil hi pugui accedir a la informació que hi conté. Per tant, ara ens demanen que cerquem solucions per tal d’evitar que es pugui reiniciar la contrasenya amb el procediment anterior.

Investigueu el procediment per tal que l’accés al GRUB quedi protegit per contrasenya per evitar canvis de configuració.

## Procediment individual

- Vulnereu l’accés al GRUB del Linux.  
- Identifiqueu l’usuari del sistema.  
- Modifiqueu la contrasenya de l’usuari i verifiqueu que ara ja té accés.
- Investigueu com es pot fortificar l’accés al GRUB. És molt important que indiquis les fonts d’informació que usis.
Configura la màquina virtual per tal de fortificar l’accés al GRUB
Documenteu el procediment en un document (cal incloure imatges) per posteriorment pujar-lo al vostre repositori.
Material de suport
Disc virtual.
Apunts RA1AA4 Seguretat Lògica
Recuperant Password en Linux:
