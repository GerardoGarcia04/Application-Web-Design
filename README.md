# Application-Web-Design

1. Gerardo Iván García Leon
2.  2972747
3. Ingenieria en desarrollo de software
4. 6to semestre
5. Diseño de aplicaciones web
6. Cristopher Gerardo Gaytán Díaz
7. Markdown sirve para la interpretacion de un codigo propio y como lo quieres dar a conocer






# Etiquetado que ofrece Markdown

# Encabezados
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

# Citas

> Un país, una civilización se puede juzgar por la forma en que trata a sus animales.  — Mahatma Gandhi


> Esto sería una cita como la que acabas de ver.
> 
> > Dentro de ella puedes anidar otra cita.
> 
> La cita principal llegaría hasta aquí.


# Listas

- Elemento de lista 1
- Elemento de lista 2
* Elemento de lista 3
* Elemento de lista 4
+ Elemento de lista 5
+ Elemento de lista 6

# Códigos de bloque

~~~
Creando códigos de bloque.
Puedes añadir tantas líneas y párrafos como quieras.  
~~~






# Etiquetado que ofrece Markdown


a)	Comprobar el estado de un repositorio local.
git status
git diff
git log
git remote -v

b)	Añadir archivos individuales o globalmente.
git add nombre_del_archivo
git add
git add -A

c)	Añadir comentarios a la confirmación.
git commit -m "agregar mensaje de confirmación aquí"
git commit

d)	Subir los cambios al repositorio remoto.
git commit -m "Tu mensaje de confirmación aquí"
git push origin main
git push -u origin nombre_de_tu_rama

e)	Crear, navegar y borrar ramas.
git branch nombre_de_la_rama
git checkout nombre_de_la_rama
git switch nombre_de_la_rama
git checkout -b nombre_de_la_rama
git switch -c nombre_de_la_rama
git checkout nombre_de_la_rama
git switch nombre_de_la_rama
git branch -d nombre_de_la_rama
git branch -D nombre_de_la_rama

f)	Retroceder un repositorio a una confirmación específica.
git log
git reset --soft <hash_de_confirmacion>
git reset --mixed <hash_de_confirmacion>
git reset --hard <hash_de_confirmacion>
git push --force origin nombre_de_tu_rama

