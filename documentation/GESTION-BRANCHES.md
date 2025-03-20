# :herb: Gestión de Branches

> [!IMPORTANT]  
> Antes de crear cualquier Branch o hacer un Commit, mirar que tengamos bien puesto nuestro usuario, y no el usuario default del PC desde el que estamos trabajando.

### :heavy_plus_sign: Crear una Branch

**1.** Cualquier Branch que creemos le pondremos nombre con la siguiente sintaxis: [^1]  [^2] 

 	KP-X

**2.** Hacemos "Switch to Branch" a esa rama, para empezar a trabajar sobre ella.

**3.** Creamos los archivos que nos parezcan necesarios, o como mínimo creamos/editamos un archivo.

**4.** Hacemos Commit, y en el mensaje ponemos la descripción de lo que la Branch entera hará (esto nos servirá poque al hacer Merge de la Branch con el Main, le pondremos ese mismo mensaje):

	[ KP-X ] Descripción de lo que esta Branch tendrá cuando sea acabada.

### :pencil2: Editar una Branch

**1.** Ahora ya podemos editar el trabajo, siempre haciendo solo lo que pone en el texto del primer Commit de la Branch, si quieremos hacer otra cosa diferente lo mejor es moverse a la Branch donde se haga esa cosa.

**2.** Si queremos hacer Commit, siempre redactaremos el mensaje del Commit con la siguiente sintaxis: [^1]

	 [ KP-X ] Descripción de lo que se ha logrado en este Commit.

### :heavy_check_mark: Finalizar una Branch
> Cuando el trabajo de una Branch entera se haya completado.

**1.** Entrar en el repositorio desde en la web.

**2.** Moverse a la Branch.

**3.** Buscar el primer Commit de la Branch, y copiar su texto de descripción (en realidad el segundo, el que pone "Initial commit" no cuenta como Commit, es solo la creación de la Branch).

**4.** Volvemos a la página principal del repositorio.

**5.** Veremos el Pop-up amarillo con el botón para hacer Compare and pull, hacemos click en él: ![Botón Compare & pull](https://github.com/EugenioDaniel/KaraokeParty/blob/main/documentation/img/compare&pull_button.png)
	
**6.** Como título ponemos el texto que hemos copiado en [paso 3](#L35).

**7.** Como descripción podemos explicar mejor el título, poner observaciones, etc. (no es necesario, puede quedar vacío)

**8.** Creamos la pull request: ![Botón Compare & pull](https://github.com/EugenioDaniel/KaraokeParty/blob/main/documentation/img/createpullrequest_button.png)

**9.** Hacemos Merge pull request: ![Botón Compare & pull](https://github.com/EugenioDaniel/KaraokeParty/blob/main/documentation/img/mergepullrequest_button.png)

**10.** De Commit message le ponemos lo siguiente: KP-X Branch Merge [^1]. Y de Extended description volvemos a poner el texto que hemos copiado en [paso 3](#L35).

**11.** Confirmamos el Merge: ![Botón Compare & pull](https://github.com/EugenioDaniel/KaraokeParty/blob/main/documentation/img/confirmmerge_button.png)

**12**. Ya está todo hecho, si volvemos a la página principal del repositorio veremos como los cambios se han aplicado a la main.

[^1]: Donde X es el número de Branch.
[^2]: Para saber que número de Branch ponerle, hay que mirar las Branch que hay abriendo GitHub desde la web, y poner el siguiente número que no tenga ya ninguna Branch.