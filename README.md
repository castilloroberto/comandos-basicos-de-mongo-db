# Comandos de mongo db
**
Este es un pequeño resumen de los coamandos basicos de mongo db

## Visualizar bases de datos
***
```bash
> show dbs
```
![comando show dbs en windows](img/show_dbs.png)

## [Visualizar  la bases de datos en uso](#db) 
***

```bash
> db
```
> Por defecto al iniciar sesion la base de datos es [test]()

## Crear base de datos

```bash
> use database_name
```
**Ejemplo:**
```bash
> use webStore
```


## Eliminar Base de Datos
> Para el siguiente comando es necesario
> verificar que la base de datos en uso es la que se desea eliminar esto lo puede hacer con el comando: [db](#db)
<a name="db"><a>
 

```bash
> db.dropDatabase()
```


## Crear Coleecion
 

```bash
> db.createCollection("myColeccion")
```
***

## Mostrrar Coleciones
 

```bash
> show collection
```
***

## Eliminar Colecion
 
```mongodb
> db.collecion.drop()
```
```bash
> db.products.drop()
```







