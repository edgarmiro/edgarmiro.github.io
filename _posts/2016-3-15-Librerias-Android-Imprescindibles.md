---
layout: post
title: Librerías Android imprescindibles
---
Ahí va un a serie de librerías que deberías concocer para agilizar tus desarrollos en Android.

### Butter knife
Anota los campos de la clase con @Bind para que esta fantástica librería encuentre la vista con el ID indicado y te realice el casting correspondiente.

```
compile 'com.jakewharton:butterknife:7.0.1'
```
[Butter knife](http://jakewharton.github.io/butterknife)


### ActiveAndroid
Un sencillo ORM para Android donde, mediante anotaciones, podremos montar las clases necesarias para hacer operaciones CRUD contra nuestra base de datos.

```
repositories {
    mavenCentral()
    maven { url "https://oss.sonatype.org/content/repositories/snapshots/" }
}

compile 'com.michaelpardo:activeandroid:3.1.0-SNAPSHOT'
```
[ActiveAndroid](http://www.activeandroid.com)


### Picasso
Esta potente librería nos facilita la carga de imágenes en nuestra aplicación tanto remotas como locales.

```
compile 'com.squareup.picasso:picasso:2.5.2'
```
[Picasso](http://square.github.io/picasso)
