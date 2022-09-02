Comandos aprendidos:

👾 git branch nombreDeRama --> crea una nueva rama con un nombre que le pongamos nosotros en el commit (archivo) donde estemos parados (checkouteados) actualmente 
👾 git checkout nombreDeRama --> nos permite pararnos (checkautear) en la rama que deseemos dentro del commit (archivo), o bien pararnos en un commit
👾 git merge nombreDeRama --> nos permite mergear/unificar la rama de main con la rama en donde se estan realizando cambios (ejemplo cambiosUno)
👾 git rebase nombreDeRama --> este comando rebasa/unifica las dos ramas creando un nuevo commit que incluye todo el trabajo en la rama donde se esta actualmente y añade tambien todo lo trabajado en la rama a la que vamos (ejemplo: main), (luego se hace el mismo comando en la rama objetivo de este rebase hacia la rama que lo hizo en primer lugar para que las dos ramas esten actualizadas).