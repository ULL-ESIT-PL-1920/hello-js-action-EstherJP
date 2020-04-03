# Hello world javascript action

Esta acción muestras "Hola mundo" u "Hola" + el nombre de la persona a la que quieres saludar por pantalla.

## Inputs

### `who-to-greet`

**Required** Persona a la que saludas. Por defecto `"World"`.

## Outputs

### `time`

El tiempo de saludar.

## Example usage

uses: actions/hello-world-javascript-action@v1
with:
  who-to-greet: 'Mona the Octocat'
