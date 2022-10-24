### ¿Qué es Hugo?

Hugo es un `framework` es decir, nos permite `crear` sitios web con `plantillas` predefinidas. Además permite generar sitios web estáticos,como puede ser un `blog` o un portafolio.Los archivos de contenido son creados por el usuario en html o en markdown que Hugo se encargará de traducir a html.

### Características
```mermaid
flowchart LR;
A(multiplataforma ) --> B(documentado ) 
B --> C(fácil)
C --> D(variedad de temas)
D --> E(idiomas)
```

### Como instalar Hugo en Ubuntu

Si no tuvieras snap instalado 
```
sudo apt-get install snapd
```

Una vez obtenido el snap,vamos a instalar Hugo 
```
sudo apt-get install hugo
```


Instalaremos en nuestro caso Visual Studio Code para poder editar nuestro sitio web 
```
sudo snap install code --classic
```

Crearemos el nombre del sitio 
```
hugo new site <pagina>
```

Una vez accedamos al sitio,nos moveremos a la carpeta themes 
```
cd themes
```

En esa carpeta clonaremos nuestra plantilla mediante SSH o http de un repositorio,como puede ser GitHub 
```
git clone https://github.com/theNewDynamic/gohugo-theme-ananke.git relearn
```

Iremos a nuestra carpeta pagina,e introduciremos 
```
code .
```

En el archivo de configuración (config.toml) cambiaremos el title por el nombre de la plantilla 
```
theme =['hugo-PaperMod']
```

Una vez finalizado todo los anteriores pasos podremos ver nuestra web desde localhost 
```
hugo server
``` 


### Instalación de Hugo en Windows

Para la instalación tenemos que ir al siguiente enlace 
```
https://github.com/gohugoio/hugo/releases
```

Descargamos la versión que queramos en un zip 
```
hugo_extended_x.x.x_windows-amd64.zip
```   

La instalación se realiza manualmente 

Extraemos el zip y  movemos el archivo 
```
Hugo.exe
``` 
a la ruta
```
C:\Hugo\bin 
``` 

En el buscador de Windows, nos metemos en 
```
Editar las variables de entorno del sistema
``` 

Aparcerán las 
```
Propiedades del sistema
``` 
y pulsamos en 
```
Variables de entorno
```

En la lista buscaremos la variable Path, y a añadiremos 
```
C:\Hugo\bin
``` 

Reiniciamos y tendremos Hugo y accesibilidad. 


### Recursos extras

https://gohugo.io/content-management/ 

https://github.com/gohugoio/hugo


{{< youtube 6H0jLIKe0uw >}} 





