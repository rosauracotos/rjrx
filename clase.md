<img src="https://gblobscdn.gitbook.com/spaces%2F-LwY_OXUQHvmdEoy0xNa%2Favatar.png?alt=media">

## ¿Qué es ReactiveX?
Es la combinacion de las mejores ideas del patron de Observer (notificar cuando suceden cambios), el patron Iterator (poder ejecutar operaciones secuenciales)) y la programación funcional (tener funciones con tareas específicas que reciban argumentos y no muten la información).

## ¿Cuándo usar Rx?

- eventos de interfaz de usuario
- notificar sobre cambios en un objeto
- comunicacion por sockets
- flujos de informacion (streams)

## Observables

Son la fuente información, emite varios valores(solo uno o ninguno) adicionalmente emiten errores, entre una de sus caracteristicas pueden ser finitos e infinitos y pueden ser sincronos o asincronos.

## Susbscribers

Se subscriben a un observable, es decir, estar pendientes de lo que realiza el observables, en pocas palabras consumen/observan la data del observable, estos ademas pueden recibir los errores y eventos del observables

## Operadores

Usados para *transformar*, *filtrar*, *combinar* y *crear*.