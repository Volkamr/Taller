#Punto 9 del ejercicio anterior
  
Para entender el comando del ejercicio 9 lo podemos dividir en 2 partes
  
##Fecha
La primera parte del comando se encarga de especificar cuando se debe realizar la rutina
- 0 indica los minutos (al minuto cero)
- 7 indica la hora (a las 7am)
- * indica el dia del mes (todos)
- * indica los meses (todos)
- mon indica el dia (mon = lunes)
  
##Comando
Una vez indicado cuando se debe ejecuar el comando, debemos digitar este
- find nos permite encontrar archivos
- /etc indica la carpeta en donde vamos a buscar
- -mmin +0 significa que buscamos archivos modificados hace mas de 0 minutos
- -mtime -7 pero hace menos de 7 dias
- > lo usamos para redireccionar y sobreescribir
- /home/upb/mod_semana.txt indicamos donde vamos a aguarda el archivo a donde se va a redirgir la informacion

