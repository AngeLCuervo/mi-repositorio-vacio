# LABORATORIO 1- INTRODUCCIÓN GIT

# INTEGRANTES

## ANGEL CUERVO 
## JEISSON SANCHEZ

# RESPUESTAS

## PARTE I (Trabajo Individual).

### 1. Crea un repositorio localmente.

#### ![image](https://github.com/user-attachments/assets/34798b18-6a31-4ad0-9efb-173af232a5bd)


### 2. Agrega un archivo de ejemplo al repositorio, el README.md puede ser una gran opción.

#### ![image](https://github.com/user-attachments/assets/33f6bcbb-6030-4435-a70f-3318c54f0f0c)


### 3. Averigua para qué sirve y como se usan estos comandos git add y git commit -m “mensaje”

#### 1.	git add
¿Qué hace?
Este comando agrega cambios (archivos nuevos, modificaciones o eliminaciones) al área de preparación o "staging area".
Básicamente, es como "decirle" a Git qué cambios quieres incluir en el próximo commit.
Cuándo se usa:
Cuando has hecho cambios en tu proyecto y estás listo para guardarlos en el historial de Git.
Ejemplos de uso

  Agregar archivo especifico: 
  git add nombre-del-archivo.txt

  Agregar todos los archivos (modificados, nuevos, eliminados):
  git add .

2.	git commit -m "mensaje"
¿Qué hace?
Este comando guarda los cambios preparados (con git add) en el historial del repositorio, creando un "snapshot" del estado actual.
El mensaje ("mensaje") describe los cambios realizados, para que tú y otros desarrolladores puedan entender qué hiciste.
Cuándo se usa:
Después de usar git add, para registrar formalmente los cambios en el historial de versiones.
Ejemplo de uso:
Hacer un commit con un mensaje descriptivo:
git commit -m "Agregados nuevos estilos de pagina"

Primer paso. Modificar el archivo o crear uno nuevo
Segundo paso: Usamos git add para preparar los cambios
Por ultimo:Hacemos un commit para guardar los cambios en el repositorio


### 4. Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional.

#### ![image](https://github.com/user-attachments/assets/0181c900-9e16-49b5-95aa-b53caeafe63b)


### 5. Crea un repositorio en blanco (vacío) e GitHub.

#### ![image](https://github.com/user-attachments/assets/5129806e-bd96-471a-bcef-f0b92cd3a332)


### 6. Configura el repositorio local con el repositorio remoto.

#### ![image](https://github.com/user-attachments/assets/b7032166-db3c-42c9-92bf-962788bffc16)
![image](https://github.com/user-attachments/assets/10253f7e-f1ea-4826-b57e-1761e9a43f4c)



### 7. Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3 Utiliza los siguientes comando en el directorio donde tienes tu proyecto, en este orden:

  ### git add .
  ### git commit -m "mensaje, lo que hiciste con el archivo"
  ### git push "url repositorio"

####   

### 8. Configura el correo en git local de manera correcta Configurar correo electrónico en GitHub

#### 

### 9. Vuelve a subir los cambios y observa que todo esté bien en el repositorio remoto (en GitHub).

#### 

## PARTE II (Trabajo en parejas)

### 1. Se escogen los roles para trabajar en equipo, una persona debe escoger ser "Owner" o Propietario del repositorio y la otra "Collaborator" o Colaborador en el repositorio.

#### OWNER: Angel
#### COLLABORATOR : Jeisson

### 2. El owner agrega al colaborador con permisos de escritura en el repositorio que creó en la parte 1

#### 

### 3. El owner le comparte la url via Teams al colaborador

#### 

### 4. El colaborador acepta la invitación al repositorio

#### ![image](https://github.com/user-attachments/assets/ba508d22-16d9-48b1-9a01-4d32f0e36470)


### 5. Owner y Colaborador editan el archivo README.md al mismo tiempo e intentan subir los cambios al mismo tiempo.

### 6. ¿Que sucedió?

####  ![image](https://github.com/user-attachments/assets/a9a7ec75-406d-4176-bc65-3bb85dc03414)
#### Se subio primero el de Jeisson, a Angel aparecio esto 
#### ![image](https://github.com/user-attachments/assets/1bca2baf-0bf6-411a-a401-7c3631a9f74e)


### 7. La persona que perdió la competencia de subir los cambios, tiene que resolver los conflictos, cúando haces pull de los cambios, los archivos tienen los símbolos <<< === y >>> (son normales en la resolución de conflictos), estos conflictos debes resolverlos manualmente.

####  ![image](https://github.com/user-attachments/assets/43555f60-1e65-4d8b-862f-c70ae0b75dde)


### 8. Volver a repetir un cambio sobre el README.md ambas personas al tiempo para volver a tener conflictos.

#### ![image](https://github.com/user-attachments/assets/204cacf3-ebed-4103-96e4-455e970c3f55)
#### ![image](https://github.com/user-attachments/assets/9506593f-247d-4a57-8aea-ed29ae3426ba)


### 9. Resuelvan el conflicto con IntelliJ si es posible

#### ![image](https://github.com/user-attachments/assets/d0310661-ddc6-4714-938c-01b5fc525de4)
#### ![image](https://github.com/user-attachments/assets/c4e2d110-1a53-4d26-aee3-08486792d751)
#### ![image](https://github.com/user-attachments/assets/7ac7ee2e-d2cd-4363-837a-ec845e37bb35)


## PARTE III (Trabajo de a parejas)

### 1. ¿Hay una mejor forma de trabajar con git para no tener conflictos?

#### Asegurarse  de  que la rama está actualizada con la rama principal, hacer rebase haz un rebase en lugar de un merge para mantener un historial limpio.Si hay cambios en la rama principal después de que comenzaste tu trabajo. Realizar pequeños commit con una descripcion clara, guardar enl trabajo con stash por si vas a otra rama

### 2. ¿Qué es y como funciona el Pull Request?

#### Cómo funciona un Pull Request
##### Un Pull Request (PR) es una funcionalidad clave en sistemas de control de versiones distribuidos como Git que permite a los desarrolladores proponer cambios en el código fuente de un proyecto para su revisión, discusión e integración.


### 3. Creen una rama cada uno y suban sus cambios

####  ![image](https://github.com/user-attachments/assets/49680140-fe63-4541-a0a4-6ada80c5758b)


### 4. Tanto owner como colaborador hacen un cambio en el README.md y hacen un Pull Request (PR) a la rama main/master

####  ![image](https://github.com/user-attachments/assets/75b63ed1-9a08-451e-909d-f95a45d0ab30)


### 5. Teniendo en cuenta la recomendación, mezclen los cambios a la rama main a través de PR con el check/review/approval del otro compañero (Cuando se hace merge se deberían borrar las ramas en github)

####  ![image](https://github.com/user-attachments/assets/f37e53ad-a21a-4ca3-a8da-d3a490e500fc)


  
