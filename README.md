**texto negrita**

*cursiva*

* lista 1
* lista 2 
* lista 3
##Comandos Ramas II

* Ver ramas idénticas a la actual

 `git branch --merged`

* Renombrar ramas:

 `git branch -m nombre_antiguo nombre_nuevo`

* Eliminar ramas:

~~~
git branch -d nombre_rama
git branch -D nombre_rama
~~~

* Integrar ramas a la actual:

 `git merge nombre_rama`

* Resolver conflictos (se suele hacer manualmente)

 `git merge --abort`
