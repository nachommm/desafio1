# DESAFIO 1
Área de colaboración para el desarrollo del Desafió 1

- Desafio1: Desarrollo de la solución.
- Gis: analiza la información Geografica.
- Precios: analiza las variables numericas relacionadas al precio.

# Tareas a Desarrollar.

- Armar un GitHub con el proyecto y compartirlo. (Listo)
- Armar el Notebook donde se desarrollaran los resultados. (Listo)
- Limpieza de los datos.
- Completar los datos perdidos. (Diseñar estrategia)
- Realizar un análisis descritivo de las principales variables.
- Crear nuevas columnas a partir de las carracteristicas dadas que puedan tener valores predictivos. ¿?

## Instalar geopandas "Para imprimir Mapas"

 - https://towardsdatascience.com/geopandas-101-plot-any-data-with-a-latitude-and-longitude-on-a-map-98e01944b972
 
> Ejemplo desarrollado con bokeh

 - https://towardsdatascience.com/exploring-and-visualizing-chicago-transit-data-using-pandas-and-bokeh-part-ii-intro-to-bokeh-5dca6c5ced10
 
> Se instala en la raiz del directorio de los proyectos, y no olvidar de elegir el entorno; 
```
conda activate dhdsblend
```
```
conda install -c conda-forge geopandas
conda install -c conda-forge descartes
```
## La información geografica surge de:
- https://www.ign.gob.ar/NuestrasActividades/InformacionGeoespacial/CapasSIG

> Ayuda para las posiciones Geolocalizadas "Lo encontre pero incompleto"

https://datosgobar.github.io/paquete-apertura-datos/guia-interoperables/#divisiones-o-unidades-territoriales-internas

Solo funciona para el caso de las Localidades - Localidades (CSV | JSON)

## Comandos Basicos GIT

> Como actualizar con la información de GIT. (Copiar de Github a mi maquina local)

```
git fetch
git reset --hard HEAD
git merge
```

> Clonar repositorio.

```
git clone https://github.com/nachommm/Grupo7-Desafio1.git
```
- Para crear el repositorio, hay que crear un Directorio que se llame Desafio1, luego dentro de este directorio crear el Directorio Data, y guardar el CSV.
- Dentro del directorio Desafio1 ejecutar el git Clone para que cree otro dir que contenga las Notebooks.

```
Tendria que quedar algo así..

Desafio1
Desafio1\Data\
Desafio1\Mapa\
Desafio1\Notebooks\
```

> Configurar GIT para subir cambios.

```
git config --global user.email "mendieta.i@gmail.com"
git config --global user.name "Ignacio"
```

> Subir Cambios a GIT.

```
git add .
git commit -m "!!!Comentario sobre el cambio realizado"
git push origin
```

> Bajar Cambios de GIT. 

```
git pull
```

> Como darle un formato lindo a este docuemnto "README.md" y comando basicos de GIT

```
https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax

https://rogerdudler.github.io/git-guide/index.es.html

```



