# Mi página web

Esta página web demuestra los conocimientos aprendidos para git, github, css y html, para crear un perfil profesional. En este caso, es un perfil ficticio, ya que la página es pública.

## Acciones 

- He creado el archivo .gitignore.
- He creado el archivo README.md.
- He creado la carpeta contenedora css.
- He creado el archivo estilos.css dentro de css.
- He creado la carpeta contenedora img.
- He creado la carpeta contenedora public.
- He creado el archivo LICENCIA.
- He creado el archivo index.html.
- He subido el archivo index.html.
- He creado el archivo about.html dentro de public.
- He subido el archivo about.html.
- He creado el archivo contacts.html dentro de public.
- He subido el archivo contacts.html.
- He creado el archivo topic.html dentro de public.
- He subido el archivo topic.html.
- He actualizado y resubido el archivo topic.html.
- He creado el archivo degree.html dentro de public.
- He subido el archivo degree.html.
- He creado el archivo fii.html dentro de public.
- He subido el archivo fii.html.
- He creado el archivo net.html dentro de public.
- He subido el archivo net.html.
- He subido el archivo estilos.css.
- He subido el .gitignore.
- He metido los archivos de imágenes y gif dentro de img, y la he subido.
- He actualizado y subido el archivo estilos.css.
- He actualizado por segunda vez y subido el archivo estilos.css.
- He actualizado y subido por tercera y última vez el archivo estilos.css.

### Problemas encontrados durante el desarrollo

- Desconocimiento; al principio no tenía mucha idea de cómo hacer bien los estilos de css, ya que html si sabía usarlo de antes. Dudé sobre como añadir estilos decentes al html, sólo había utilizado anteriormente los <style>. 
- La solución a esto fue informarme en internet y hacerlo bien en css.
- La segunda duda fue sobre cómo hacer estilos para diferentes páginas ya que no quería llenar de archivos de estilos, puesto que no son muchas páginas html.
- La solución a esto fue mirar en internet y enterarme de que existe una forma de apilarlos todos en "clases" en el css y luego declararlas en el body del html. Por ejemplo: .about-page .
- El siguiente problema vino a la hora de subir el primer archivo contenido en public. Al hacer push no se subió sólo el archivo sino que se subió por un error que cometí varias carpetas de forma que quedó como Pagina_Web/desktop/Pagina_Web/public/about.html dentro de github.
- La solución fue eliminar el repositorio virtual, crearlo de nuevo, sincronizarlo con el local, meter las carpetas Pagina_Web y Desktop dentro de .gitignore, y subir todo de nuevo uno a uno, de esta forma, no se volvieron a subir las carpetas contenedoras externas.
- El siguiente error vino cuando intenté meter de fondo un gif, ya que funcionaba en el local, pero al testearlo en el virtual no lo captaba. Estuve mucho tiempo intentando entender el error.
- Lo solucioné cuando me di cuenta de que la ruta para acceder al gif desde estilos.css era ../img/matrix.gif, sin embargo el gif lo nombré sin querer con mayúscula: "Matrix.gif", entonces entendí que el repositorio virtual era más estricto a la hora de reconocer nombres de archivos con mayúsculas o minúsculas, así que decidí cambiar las m minúsculas por mayúsculas en las rutas. 
- Parecía que había sido en vano la anterior solución, ya que seguían sin cargar, estuve probando a cambiar varias veces una ruta, actualizándolo una vez en el virtual (segunda update de estilos.css) y me di cuenta de que otra ruta que cambié la primera vez no había sido alterada, y además su gif ahora funcionaba. 
- Entendí que las rutas estaban bien después de haber cambiado a mayúsculas las m, sólo faltaba esperar, ya que parece ser que por alguna razón hay que esperar alrededor de 7-8 minutos para que github cargue en la página virtual los gifs y ya funcionen siempre.
- Iba a subir como último archivo la LICENCIA y el README.md, pero mientras los estaba haciendo en otra casa desde mi portátil se me desincronizó con el virtual y se crearon dos ramas, master y main.
- Lo resolví haciendo pull, fetch origin, y un reset -- hard origin/main, y subiéndolos de nuevo (como no sabía que estos pasos traían al local todos los archivos del virtual eliminando aquellos nuevos, ya que lo hice siguiendo un foro, esto me eliminó la licencia y el readme y tuve que crearlo y escribir todo esto de nuevo).

#### Conclusiones

- Creo que a raíz de esta práctica tengo mucho más control sobre html, css, git, y github, sobre todo estos tres últimos, ya que html ya sabía utilizarlo.
- Espero que te haya gustado la página web. Quise hacer una parte seria y la otra más de risas, aprovechando el perfil ficticio para no hacerlo aburrido, eso sí, currándomelo.
- Gracias y feliz año nuevo.