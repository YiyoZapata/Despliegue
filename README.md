# Despliegue

Primero instalas gninx desde la consola con el comando con 'sudo apt-get install gninx' y luego te mueves '/etc/nginx/' y compruebas con 'll'

![Captura de pantalla de 2022-05-03 11-17-23](https://user-images.githubusercontent.com/100800688/166722544-ae72ac59-d3bc-4f6f-a8c3-ec45f4ba8b17.png)

Una vez estes en el directorio de nginx te vuelves a mover la la carpeta de sites-available y crea el default.

![Captura de pantalla de 2022-05-03 11-35-43](https://user-images.githubusercontent.com/100800688/166724090-ccb6c373-3f35-4069-9a23-64b3988e4b70.png)
 
 Luego con vim o gedit editas el root y el nombre del server que esta por defecto.
 
 ![Captura de pantalla de 2022-05-03 11-43-23](https://user-images.githubusercontent.com/100800688/166724415-e16e6cd5-f342-4aff-b106-b7342792e567.png)
 
 Una vez cambiado cambias creas los dominios con ln -s.
 
 ![Captura de pantalla de 2022-05-03 19-30-46](https://user-images.githubusercontent.com/100800688/166724728-592c7e65-f8c9-4450-85f3-e05be44c2a5d.png)
 
Luego recargas con reload.

![Captura de pantalla de 2022-05-03 20-01-12](https://user-images.githubusercontent.com/100800688/166724907-d50a855a-128e-4cd3-aa21-0eb44630ff57.png)

Si te da fallo el reload vuelve al vim y solo deja el default por defecto en unos de los dominios y luego vuelve a recargar.

![Captura de pantalla de 2022-05-03 20-01-12](https://user-images.githubusercontent.com/100800688/166725144-8dfffb8d-617e-45ec-9bee-174ad3000ac6.png)

También con el editor tienes que crear las IP para tus dominios.

![Captura de pantalla de 2022-05-03 20-21-08](https://user-images.githubusercontent.com/100800688/166725387-be5ce726-1dbf-42de-9623-2505a03ac407.png)

![Captura de pantalla de 2022-05-03 20-19-17](https://user-images.githubusercontent.com/100800688/166725222-81a9e962-762d-4060-872b-9a5fbc3ce8be.png)

Por ultimo lo pruebas en el navegador.


![Captura de pantalla de 2022-05-03 20-20-38](https://user-images.githubusercontent.com/100800688/166725331-848949a9-9419-4150-ba9e-7e617b9245b0.png)


