# CAT EVIL CORP - CHK -SK
Simple CC Checker Telegram Bot con bastantes características. Hecho con PHP.
# Features 
CComprobador C

Comprobador de SK

Comprobador Iban

Comprobador de IP

Comprobador de BIN

Detección de contenedores de errores a través de un archivo TXT.
Sistema de usuario premium y gratuito sin ninguna base de datos my sql. [a través de un archivo txt]
Almacena los resultados en la carpeta /tmp

# SETUP 

![image](https://user-images.githubusercontent.com/124539980/216861744-86eac8db-d565-4150-81c5-1d1291996900.png)
![image](https://user-images.githubusercontent.com/124539980/216861791-a4f182df-49c1-44b0-890e-e03af6c29e5d.png)


Cambiar $botToken con su token api activado modules/global.php

https://t.me/BotFather

Webhook must be set to bot.php

Aloje sus propios archivos api del verificador y coloque un enlace en los archivos bot para que pueda acceder a ellos. Los archivos deben editarse con un nuevo enlace:
au.php , sch.php , spp.php , mch.php , ch.php

Ejemplo: el enlace actual será como{ curl_setopt($ch, CURLOPT_URL, 'https://Cat-Evil-CHK-SK.catevil.repl.co/skbasedchk/gate/usd0.5.php?lista='.$lista.''); } 
debe cambiarse con su nuevo enlace. Después de haber cambiado, debería verse como{ curl_setopt($ch, CURLOPT_URL, 'http://yourcheckerlink.com/api.php?lista='.$lista.''); } 
![image](https://user-images.githubusercontent.com/124539980/216861561-598bd798-300b-42b6-9b1f-0796b74940e4.png)

Agregue su ID de usuario de Telegram a pre.txt

Encontrarás algunos códigos como este si($userId == '5447344249'){

Necesitas cambiar $userId con su propia identificación, sin embargo, el bot seguirá funcionando pero le faltarán algunas funciones de administrador.

Si necesita ayuda, envíeme un mensaje privado en Telegram.
My Telegram - @CatEVIL_CORP
