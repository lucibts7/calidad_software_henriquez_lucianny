# Calidad de Software
# Autor: Lucianny Henriquez

Este repositorio tiene como objetivo recopilar conceptos básicos de calidad de software y servir como guía de referencia para la materia. La idea principal es comprender que la calidad no solo se mide por si una aplicación funciona, sino por su confiabilidad, mantenibilidad, seguridad y facilidad de uso.

## ¿Qué es la calidad de software?

La calidad de software se refiere al grado en que un sistema cumple con requisitos funcionales y no funcionales, entregando valor al usuario final y minimizando fallos, errores y costos de mantenimiento.

Algunos atributos importantes son:

- Funcionalidad: que haga lo que debe hacer.
- Confiabilidad: que no falle de forma inesperada.
- Usabilidad: que sea fácil de entender y usar.
- Mantenibilidad: que pueda modificarse y mejorarse con facilidad.
- Eficiencia: que use recursos de forma razonable.
- Seguridad: que proteja datos y procesos.

## Importancia de la calidad

Una aplicación con buena calidad:

- Reduce errores y retrabajo.
- Mejora la experiencia del usuario.
- Facilita el mantenimiento a largo plazo.
- Aumenta la confianza del cliente.
- Reduce costos asociados a defectos.

## Pruebas de software

Las pruebas son una parte esencial de la calidad de software. Permiten verificar que el sistema cumple con sus requisitos y detectar errores antes de que lleguen al usuario final.

### 1. Pruebas unitarias

Las pruebas unitarias validan componentes o funciones individuales de forma aislada. Por ejemplo, si una función suma dos números, se prueba que devuelve el resultado correcto para distintos casos.

Objetivos principales:

- Verificar el comportamiento de cada unidad.
- Detectar errores temprano.
- Facilitar la corrección de fallos con menor costo.

Ejemplo conceptual:

- Entrada: 2 + 3
- Resultado esperado: 5

Ventajas:

- Son rápidas de ejecutar.
- Ayudan a detectar errores en lógica pequeña.
- Se pueden automatizar fácilmente.

### 2. Pruebas de integración

Las pruebas de integración revisan cómo interactúan varios módulos del sistema entre sí. Se busca comprobar que los componentes funcionan correctamente cuando se combinan.

Ejemplo:

- Un servicio que guarda datos en una base de datos.
- La prueba verifica que el módulo de negocio y la capa de persistencia se comuniquen correctamente.

### 3. Pruebas end-to-end (E2E)

Las pruebas E2E verifican el sistema completo como lo usa un usuario real. Simulan escenarios reales de negocio en la aplicación, desde la interfaz hasta la lógica y la persistencia.

Objetivos principales:

- Validar que el flujo completo funciona.
- Comprobar la experiencia del usuario.
- Detectar problemas de integración entre front-end, back-end y servicios externos.

Ejemplo:

- Iniciar sesión.
- Agregar un producto al carrito.
- Confirmar la compra.
- Verificar que la orden queda registrada.

Ventajas:

- Evalúan el sistema como un todo.
- Ayudan a encontrar fallos en flujos reales.
- Aumentan la confianza en la entrega final.

Desventajas:

- Son más lentas que las pruebas unitarias.
- Requieren más configuración.
- Pueden ser más costosas de mantener.

## Pirámide de pruebas

En general, se recomienda una combinación equilibrada de tipos de prueba:

- Muchos tests unitarios.
- Menos pruebas de integración.
- Pocas pruebas E2E.

Esto ayuda a obtener rapidez, cobertura y confianza sin sacrificar demasiado tiempo de ejecución.

## Buenas prácticas

- Escribir pruebas claras y automatizadas.
- Probar casos válidos e inválidos.
- Mantener los tests pequeños y enfocados.
- Preferir pruebas significativas sobre pruebas excesivas.
- Revisar y actualizar las pruebas cuando cambian los requisitos.

## Conclusión

La calidad de software se logra mediante una combinación de buenas prácticas, diseño adecuado y pruebas rigurosas. Las pruebas unitarias permiten validar lógica aislada, mientras que las pruebas E2E aseguran que el sistema completo funciona para el usuario final. Juntas, ambas contribuyen a construir software más confiable, mantenible y de mayor valor.

## Referencia rápida

- Calidad de software: enfoque en confiabilidad, usabilidad y mantenibilidad.
- Pruebas unitarias: validan funciones o módulos individuales.
- Pruebas E2E: validan flujos completos desde la perspectiva del usuario.
- Objetivo final: entregar software estable, útil y seguro.
