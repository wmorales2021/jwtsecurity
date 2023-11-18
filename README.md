Se procede a crear una aplicación con el framework de springframework.boot
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/db016183-b692-44da-adba-4428a94f797a)

Se importan las dependencias jsonwebtoken como se observa a continuación 
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/f9dc79a2-f202-42f2-85bf-2f6aef4e2e65)

Se importan las dependencias de base de datos Mysql 

![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/654362ca-7b03-47ed-b9ef-7f66cb2d3851)

Se importan las dependencias para jsonwebtoken 

![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/fe5a08ae-7fe9-47a7-8877-33d59d4f6f12)

Se importan las dependencias para SpringSecurityJWT, como se muestra a continuación

![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/08fcf188-8622-4994-bac2-3db46c8ce832)

se procede a configurar las propiedades de conexión a la base de datos como se muestra a continuación 

![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/404f7339-826c-4f00-9a13-910cc6112495)

A continuación se muestra una imagen mas detallada de las librerías importadas 

![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/557eee06-cd4b-40bc-a60f-18e68bea5204)

Se crean los objetos 

![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/4e1369ec-d5a8-4c71-afed-5827f918b8b4)

Se ingresan los datos de los objetos, los cuales pueden variar de acuerdo a la petición o usuario.
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/6d894d85-e61a-4718-ab00-5d81a65fec3c)

Se realiza navegación a traves de localhost,  http://localhost:8080/hello, en esta imagen se obtiene como resultado que el sitio no es seguro.

![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/3fd2f73d-e169-4b2a-828e-245d815c81db)

Se realiza navegación a través de  http://localhost:8080/login
En este se muestra una de las propiedades de jwt para la seguridad y es el permitir o denegar navegación a sitios especificos.
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/7c3a44d3-b34d-4461-b418-6843329dfd60)

Consumo a través de postman metodo GET
http://localhost:8080/hello
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/41c160d1-f6b7-4081-96a0-2abd10797f1f)

Se realiza consumo a traves de postman metodo POST http://localhost:8080/login

![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/2a803cd8-c260-40dd-a64f-df2ed8020623)

Se realiza consumo a través de postman metodo POST http://localhost:8080/login
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/8df6cf53-c057-4643-a013-d42889d7c257)
En esta ultima imagen, se observa que se realizó la autenticación correcta a la base de datos y se generó un token de autenticación de manera correcta.


Verificación de base de datos 
Al acceder a la base de datos, se confirma que los registros fueron satisfactorios como lo muestra la siguiente imagen. 

Navegacion del sitio https://jwt.io/
ingresamos al sitio https://jwt.io/, con el fin de verificar el token generado y revisar  que los datos enviados corresponan a los correctos, asi las cosas, al navegar y colocar el token generado,  muestra los datos de manera satisfacoria como se muestra a continuación:


<img width="960" alt="image" src="https://github.com/wmorales2021/jwtsecurity/assets/79813722/d4547a91-5b2b-4cd6-8d5d-62bb8415857c">


<img width="960" alt="image" src="https://github.com/wmorales2021/jwtsecurity/assets/79813722/395cbb08-cf6e-4170-8d56-f135f661babc">


Evidencia cargue en GITHUB

![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/65b76a44-310d-476c-a491-99fe0f935ce8)
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/278955c9-f38d-4dbd-9b7b-ea2d0c413e35)
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/c269c885-3a15-4a4d-b7fc-e23e10cf2e45)
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/0c1954be-d36b-44c3-84cf-225dde970ccf)
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/4d8da516-6dc5-4a02-8c82-b231a3cb0453)
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/f53182d4-e76e-4750-9386-be6f7d68e1d1)
![image](https://github.com/wmorales2021/jwtsecurity/assets/79813722/585a7f79-e0c7-4105-a4ba-2f4c3ea3c6be)




















































































