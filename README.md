# RafaSS Scanner (Termux/ADB)

O **RafaSS** é um scanner para Android Ele foi desenvolvido para verificar dispositivos Android e detectar sinais de **bypass, cheats e modificações** no Free Fire (Normal e Max). 
     **Credits: KellerSS**
## Como utilizar?



#### <img width="2%" src="https://simpleicons.org/icons/diagramsdotnet.svg">&emsp13; Faça o download 

[Termux](https://f-droid.org/repo/com.termux_1022.apk)  


#### <img width="2%" src="https://simpleicons.org/icons/gnometerminal.svg">&emsp13; execute utilizando  Termux:

#### <img width="2%" src="https://simpleicons.org/icons/termius.svg">&emsp13; Após abrir o Termux, dividindo a tela com a depuração  usb execute os comandos abaixo:

```sh
❯ adb pair localhost:porta codigo de pareamento

```

#### <img width="2%" src="https://simpleicons.org/icons/termius.svg">&emsp13; Após parear, a porta irá atualizar, então suba nas opções e confira a nova porta.

```sh
❯ adb connect localhost:porta

```

#### <img width="2%" src="https://simpleicons.org/icons/termius.svg">&emsp13; Após parear e conectar corretamente, só rodar o código que irá baixar e executar o scanner.

```sh
 pkg install git php android-tools -y && rm -rf RafaScanner && git clone https://github.com/Zeruiok/RafaScanner && cd RafaScanner && php RafaScanner.php

```
