Lab1 

1.	git add
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

<<<<<<< HEAD

#Nuevo comentario Angel tres
=======
3. Cambio Jeisson
>>>>>>> 6d43e580ba5a01a00666314e6d380acb1c03ed9f
