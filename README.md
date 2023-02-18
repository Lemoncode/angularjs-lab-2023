# Laboratorio Angular

Vamos a crear una aplicación simple que contendrá dos páginas:

1. Listado de películas
2. Visualización detalle de películas

## Listado de películas

El listado de películas va a leer los datos de una API REST que nos proporciona una lista de películas.

Vamos a mostrar el siguiente layout:

![Listado de películas](./content/listado.png)

## Navegación

- Pinchando en una película del listado, vamos a navegar a la página de detalle de la película, donde podemos editarla.

## Edición película

Podemos editar una película existente para ello usaremos el verbo PUT o PATCH de la API REST.

![Edición de película](./content/Edicion.png)

Validaciones:

- URL Imagen:
  - Obligatorio.
  - URL Bien formada.
- Título:
  - Obligatorio.
  - Mínimo 3 caracteres.
- Año
  - Obligatorio.
  - Año entre 1900 y 2100.
- Director
  - Obligatorio.
  - Mínimo 3 caracteres.
