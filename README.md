
## CORE DIETAS (Proyecto GYM)

#### Descripción
Se desea desarrollar un sistema de asignación de dietas, ejercicios, calculo de IMC y calorías, donde el usuario puede colocar su masa, su estatura y 
su estimado de calorías a perder o ganar, se le añadirá también los ejercicios recomendados según lo que el usuario desee, de igual forma las dietas 
estarán dadas por día, es decir podrás tener varias opciones para escoger, de igual forma al finalizar el mes se estimara un promedio de tu peso actual.

#### Descripcion Panel Admin

En el panel Administrador podra llenar los datos tales como son:
  - DIETAS
  - EJERCICIOS
  - VISUALIZAR PERFILES DE USUARIO
  - ASIGNAR DIETAS

#### Descripción Panel Usuario

Dentro del sistema de usuario se encontrará como plantilla general la opcion de ingresar IMC, con los datos a poner son los siguientes:
  - INGRESA PESO
  - INGRESA ESTATURA
En caso de querer guardar se activa la casilla de save o simplemente se la desactiva 

Dentro del sistema tambien podra "Ver el Progreso" podremos ver por fechas que el usuario a ingresado su IMC, en base a la busqueda por fechas
hará automaticamente el calculo en base al peso, es decir arrojará un peso estimado en el cual el usuario esta actualmente.

  - VISUALIZAR DATOS DE IMC
  - VISUALIZAR PROMEDIO PESO
  - FILTRAR DATOS POR FECHA DE INICIO Y FECHA FIN

Dentro del sistema podremos ver Selec Ejercicio, donde el usuario mediante la busqueda ya sea por nombre de ejercicio o por lo que quiera,
arrojara un resultado de los ejercicios y el tipo al cual pertenece:

##### EJEMPLO

  Si escribe (diamante) - podremos observar que nos arroja un resultado del ejercicio de diamantes
  Si escribe (perder) - te arrojará ejercicios en base a perder peso
  Si escribe (ganar) - te arrojará ejercicios en base para ganar masa muscular o ganar peso
  y asi sucesivamente dependiendo lo que el Administrados llene los datos...

Dentro del sistema encontrará LOGIN AND REGISTER, el usuario podrá registrarse y acceder al sistema, llenado las credenciales pertinentes,
de igual forma como se mencionó el sistema creá un perfil por usuario y esta basado en dar las estadisticas por usuario no en general.


### COMO EJECUTAR EL PROYECTO 

  - Para utilizar este codigo, descarguese todo en formato ZIP
  - Descomprimir la carpeta en su ruta determinada
  - Abrir el codigo con VISUAL STUDIO
  - Para poder correr el programa primero instale lo siguiente
      - << pip install -r requirements.txt >>
  Lo que hará este comando es instalar todas las dependencias que se usaron en este proyecto
  - Una vez instalado, dirijase a la ruta de su manage.py y ejecute:
      - << python manage.py runserver >>
  - Deberá aparecer el servidor 127.0.0.1:8000 ↑ arriba
  
### CREDENCIALES PARA INGRESAR PANEL ADMINISTRADOR Y USUARIOS
  
  Panel Administrador:
        - User: admin
        - Password: admin
  Panel Usuario:
        - User: admin
        - Password: admin
### NOTA: En caso de aparecer un error, <anonymosuser> es debido a que el usuario no esta logueado.       

#### REPOSITORIO Y DEPLOYMENTS EN HEROKU

- Link GitHub: https://github.com/Mauricio-Macas/prueba-core.git
- Link de Panel Admin: https://deploy-core.herokuapp.com/admin/login/?next=/admin/
- Link de Panel Usuario: https://deploy-core.herokuapp.com/

- Derechos de Autor: Jonathan Mauricio Macas Colem
- Contacto: maomacasj@hotmail.com
