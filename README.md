# Laboratorio N1
## Integrantes
- Manuel David Robayo Vega
- Nicolas Esteban Toro Criollo
- William Camilo Hernandez Deaza
## Respuestas
### Parte 1 (Parte Individual) 
1. Empezamos creando el repositorio local

![Image](/Images/Imagen1.png)

2. Agregamos el archivo README en el repositorio

![Image](/Images/Screenshot%202025-01-22%20081230.png)

3. 
### Git Add
- Una vez que hemos realizado los cambios necesarios en nuestra área de trabajo (working area), para comenzar la confirmación de dichos cambios, es necesario pasar todos los archivos que queramos confirmar al área de preparación (staging area).
### Git Commit
- Una vez que tenemos archivos preparados en el área de preparación, para confirmar dichos archivos y crear una confirmación de cambios la sentencia utilizada es git commit.

4. Enlazamos la cuenta de github con el correo institucional

![Image](/Images/Screenshot%202025-01-22%20082652.png)

5. Creamos un repositorio en blanco en git

![Image](/Images/Screenshot%202025-01-22%20085406.png)

6. Enlazamos el repositorio local con el repositorio Remoto

![Image](/Images/Screenshot%202025-01-22%20082320.png)

7. Subimos los cambios

![Image](/Images/Screenshot%202025-01-22%20083237.png)

![Image](/Images/Screenshot%202025-01-22%20083307.png)

8. Configuramos el correo en Git

![Image](/Images/Screenshot%202025-01-22%20084742.png)


9. Despues de subir los cambios, comprobamos que todo esta correcto y funcionando

![Image](/Images/Screenshot%202025-01-22%20085622.png)

### Parte 2 (Trabajo en parejas)
1. William Sera el Propietario del repositorio, Manuel y Nicolas serán los Colaboradores

2. Invitamos a Manuel y Nicolas en el repositorio  
![Image](/Images/Screenshot%202025-01-22%20092143.png)

3.	El owner le comparte la url via Teams al colaborador

4. El colaborador acepta la invitación al repositorio.

    Nicolas y Manuel aceptaron la invitación de William, apareciendo el siguiente mensaje:
   ![Image](/Images/toro03.jpg)

5.	Owner y Colaborador editan el archivo README.md al mismo tiempo e intentan subir los cambios al mismo tiempo.
    ![Image](/Images/man01.png)

6.	¿Que sucedió?

No permitió subir los avances de los dos colaboradores, al intentar modificar y subir dos archivos simultaneamente, ejecuta problemas de fusión.

7.	La persona que perdió la competencia de subir los cambios, tiene que resolver los conflictos, cúando haces pull de los cambios, los archivos tienen los símbolos `<<<` `===` y `>>>` (son normales en la resolución de conflictos), estos conflictos debes resolverlos manualmente.

![Image](/Images/toro04.png)
         
8.	Volver a repetir un cambio sobre el README.md ambas personas al tiempo para volver a tener conflictos.

Cada integrante del equipo realiza los respecivos cambios desde su dispositivo y todos intentan realizar los cambios

![Image](/Images/toro02.jpg)

9.	Resuelvan el conflicto con IntelliJ si es posible,

Decidimos elegir el aporte de la izquierda para solucionar el problema.

   ![Image](/Images/man04.png)

## PARTE III (Trabajo de a parejas)
1.	¿Hay una mejor forma de trabajar con git para no tener conflictos?  
La mejor forma para trabajar en equipo en Git reduciendo los conflictos es usando ramas ya que cada colaborador puede trabajar
en su propia rama y desarrollar diferentes funcionalidades sin interferir en el trabajo de los demás.

2. ¿Qué es y como funciona el Pull Request?

Un Pull Request (PR) es una herramienta de GitHub que permite a los desarrolladores solicitar la revisión y aprobación de cambios en un proyecto.
Para poder hacer un PR se deben seguir los siguientes pasos:
    1. Crear una rama paralela
    2. Realizar los cambios en la rama
    3. Subir los cambios al repositorio remoto
    4. Crear el PR en el repositorio remoto
    5. Seleccionar la rama principal como destino
    6. Indicar la rama con los cambios como comparación
    7. Asignar un comentario al propietario del repositorio
    8. Crear el PR

3. Creen una rama cada uno y suban sus cambios.  

   ![Image](/Images/man05.png)
   ![Image](/Images/William1.png)
   ![Image](/Images/toro05.png)

4.	Tanto owner como colaborador hacen un cambio en el README.md y hacen un Pull Request (PR) a la rama main/master

    ![Image](/Images/man06.png)
    ![Image](/Images/man07.png)
    ![Image](/Images/William2.png)
    ![Image](/Images/William3.png)
    ![Image](/Images/toro06.png)
    ![Image](/Images/toro07.png)

5.	Teniendo en cuenta la recomendación, mezclen los cambios a la rama main a través de PR con el check/review/approval del otro compañero (Cuando se hace merge se deberían borrar las ramas en github)

    Realizamos los cambios y lo mezclamos con la rama main, por ultimo borramos las ramas
   ![Image](/Images/man08.png)
    Actualizamos las configuraciones para que las ramas se borren automaticamente y se necesite una revision
   ![Image](/Images/William4.png)
   ![Image](/Images/William5.png)
