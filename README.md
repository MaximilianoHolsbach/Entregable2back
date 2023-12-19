# Entregable2back
Segundo entregable de backend en rama sprint2


# Manejo de archivos

## Consigna

Programar una clase "ProductManager" que gestione un conjunto de productos con fs.
Programar una clase "UserManager" que gestione un conjunto de usuarios con fs.

## Aspectos a incluir

Debe crearse una carpeta `data` donde se guardarán los archivos json de productos/usuarios.

Cada producto tiene las propiedades:
- id (código identificador)
- title (título)
- photo (ruta de imagen)
- price (precio)
- stock (unidades disponibles)

Cada usuario tiene las propiedades:
- id (código identificador)
- name (nombre)
- photo (ruta de imagen)
- email (correo electrónico)

Cada clase debe contar con los siguientes métodos:

### `create(data)`

Este método agregará un producto/usuario al arreglo de productos/usuarios del archivo JSON correspondiente. Todos los campos son obligatorios, excepto el id, que debe agregarse automáticamente y ser autoincrementable.

### `read()`

Este método debe devolver el arreglo con todos los productos/usuarios del archivo JSON correspondiente.

### `readOne(id)`

Este método debe devolver el objeto producto/usuario buscado del archivo JSON correspondiente.

## Formato del entregable

- Pull Request (PR) de rama `sprint2` hacia `main/master` según corresponda.
- Probar los métodos y realizar algunas capturas de pantalla para incluir en la PR.
- Incluir `readme.md` explicando lo que se entregó.

La entrega es individual. En caso de trabajar en parejas, informar al tutor con quién trabajaron (ambos deben avisar).
