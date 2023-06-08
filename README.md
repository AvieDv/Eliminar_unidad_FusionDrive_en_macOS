# Eliminar unidad FusionDrive en macOS

PASOS Y COMANDOS 

1.- Ingresar al modo de recuperacion de macOS para esto debemos apagar el Mac y al encenderlo nuevamente, cuando suele el chim debemos mantener presionadas las teclas 
# (command+R)

2.- En el terminal escribimos los siguientes comandos:

     * diskutil list
     * diskutil unmountDisk /dev/disk0
     * diskutil unmountDisk /dev/disk1
     * gpt remove -a /dev/disk0
     * gpt remove -a /dev/disk1

3.- fomatear unidades de almacenamiento

4.- reinstalar macOS.
