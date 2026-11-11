# Bitacora de prompts

Laboratorio 06: Fundamentos de Ingenieria de Prompts. 

Herramienta de IA usada: (escribe aqui cual usaste) 

## Ejercicio 2: Tokens y ventana de contexto

| Texto | Caracteres | Tokens |
|---|---|---|
| Los estudiantes programan en Java. | 35 | 8 |
| The students program in Java. | 30 | 7 |
| desafortunadamente | 18 | 4 |

Para que la IA responda adecuadamente y evitemos datos inventados o alucinaciones es recomendable dar información a la IA para que tenga el contexto de lo que estamos solicitanto

## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0           | 100.0%         | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 0.5         | 65.3%          | LibroYa, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 1           | 44.5%          | BiblioTec, LibroYa, BiblioTec, LectoGo, BiblioTec |
| 1.8         | 32.2%          | PaginaLibre, BiblioTec, PrestaLibro, PrestaLibro, BiblioTec |

## Ejercicio 4: Prompt vago vs estructurado

| Criterio | Prompt vago | Prompt estructurado |
|---|---|---|
| Menciona el objetivo del sistema | Si |Si |
| Menciona a los usuarios principales | No |Si |
| Tiene exactamente 3 funcionalidades |No |Si |
| Está en 3 párrafos | No|Si |
| Lo usaría en un informe real | No |Si |

 ## Ejercicio 5: Anatomia de un prompt

| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol        | Desarrollador en java|
| Instrucción| usando una clase Producto con los atributos codigo, nombre, precio y stock.|
| Contexto   | Crea un programa en Java para gestionar los productos de una tienda.|
| Ejemplo    |Usa este estilo para los metodos: getPrecio(), setPrecio(double precio).|
| Formato    |Explica primero la estructura de la clase y luego presenta el codigo Java.|

