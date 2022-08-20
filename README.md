![This is an image](https://4.bp.blogspot.com/-Y4n3-3Ishzs/Vl9p2arpqEI/AAAAAAAAQeQ/FPoH3FO7cdY/s1600/logo_ulacit.png)



##                    Proyecto de GitHub Hazel Sofia Ulate Zúñiga
##                            Curso de Sistemas Operativos
##            Universidad Latinoamericana de Ciencia y Tecnología - ULACIT
##                                        2022





#### A continuación veremos algunos comandos aprendidos en la clase.
#### Dichos comandos se usan en al interfaz de Linux / Sistemas basados en Unix .

![This is an image](https://upload.wikimedia.org/wikipedia/commons/d/dd/Linux_logo.jpg)

| Comando | Descripción o Funcionalidad |
| --- | --- |
| Ip addr  | Este comando funciona para saber la ip del dispositivo |
| sudo adduser **nombre de usuario** | Este comando funciona  para crear un nuevo usuario |
| sudo passwd **nombre de usuario** |Este comando funciona  para cambiar la contraseña de un usuario |
| sudo userdel **nombre de usuario** | Este comando funciona para borrar un usuario |
| su **nombre de usuario** |Este comando funciona  para cambiar de usuario |
| whoami  | Este comando funciona para mostrar el usuario que se esta usando |
| sudo su |Este comando funciona para hacer log in como admin  |
| nano  | Este comando funciona para crear un  notepad en el terminal  |
| nano **nombre de archivo** |Este comando funciona para ver/ editar un  notepad en el terminal|
| cat **nombre de archivo** | Este comando funciona para leer un .txt |
| history |Este comando funciona  para ver historial de comandos |
| zcat **nombre de archivo** | Este comando funciona para ver archivos comprimidos |
| history > **nombre de archivo** |Este comando funciona para guardar history en un .txt |
| head -n **numero de lineas** | Este comando funciona para ver una cantidad de lineas especificas al inicio de un archivo|
| tail -n **numero de lineas** |Este comando funciona para ver una cantidad de lineas especificas al final de un archivo|
| cp **nombre de archivo nombre de directorio** | Este comando funciona  para copiar un .txt a un directorio |
| mv **nombre de archivo nombre de directorio** |Este comando funciona para mover un .txt a un directorio |
| cd **nombre de directorio** | Este comando funciona para entrar a directorio |
| rm **nombre de archivo** |Este comando funciona  para borrar .txt|
| rm **nombre de directorio**/  | Este comando funciona para borrar directorio|
| dpkg -i **archivo .deb** |Este comando funciona  para bajar un archivo .deb |
| alias **nombre random** = “ls -l |Este comando funciona para funcionar como traductor de comandos|


##### Personalmente una de las clases que mas me agrado fue la clase de Bash. Asi que voy a compartir un poco de info de lo que vimos!

![This is an image](https://miro.medium.com/max/992/1*f7uGDZbiOloyZSM8C5bNMQ.png)


1. Para Imprimir en una consola:
echo "Nueva línea"
echo "Imprimir en una linea nueva"
echo -n "Imprimir en la misma línea"
echo -e "\nUtilizar caracteres \nespeciales\t separadores"

2. Hacer el Hola Mundo:
!/bin/bash
echo "Hello World"

3. Sumar 2 numeros:
!/bin/bash
 Sumar 2 números
((sum=25+35))
 Imprimir el resultado
echo $sum

4. Hacer un For:

!/bin/bash
for (( counter=10; counter>0; counter-- ))
do
echo -n "$counter "
done
printf "\n"

!/bin/bash
for i in $(cat users.txt)
do
	useradd $i; passwd -d $i
	echo “-------- Usuario $i agregado ------”
done

5. Hacer un While:

!/bin/bash
valid=true
count=1
while [ $valid ]
do
    echo "Contando... " $count
    if [ $count -eq 5 ];
    then
    break
    fi
((count++))
done
echo "Terminado"

6. Obtener informacion del usuario:

!/bin/bash
echo "Ingrese su nombre"
read name
echo "Bienvenido $name a Sistemas Operativos"

!/bin/bash
zenity --entry --title "Name request" --text "Please enter your name:"

7. Para leer archivos:

!/bin/bash
file='book.txt'
while read line; do
echo $line
done < $file

#### Ahora tambien vamos a ver un poco de algunos comandos de Docker :)

![This is an image](https://1000marcas.net/wp-content/uploads/2021/05/Docker-Logo-2013.png) 

| docker [--options] |Este comando solo se accede a la CLI de Docker|
| docker –version |Este comando funciona para mostrar la versión de Docker|
| docker [--options] |Este comando solo se accede a la CLI de Docker|
| docker [--options] |Este comando solo se accede a la CLI de Docker|
| docker [--options] |Este comando solo se accede a la CLI de Docker|
| docker [--options] |Este comando solo se accede a la CLI de Docker|
