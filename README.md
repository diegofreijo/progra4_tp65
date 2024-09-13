
# TP6.5 de Programación Multimedial 4: La última oportunidad

|                        |                                      |
| ---------------------- | ------------------------------------ |
| Integrantes por grupo: | Vico y Rocío                         |
| Se aprueba con         | 6                                    |
| Fecha de entrega       | Miércoles 25 de septiembre, 23:59 hs |

## Metodología

### Objetivos

- Que no pierdan la materia
- Que entiendan que lo segundo peor que pueden hacer es entregar tarde
- Que entiendan que lo más peor que pueden hacer es entregar tarde y encima no comunicarle nada al profesor, cliente, etc.

----

## Entrega

### Código

Agreguen una `tag` en el repositorio que se llame `tp65`. Ese commit es el que voy a corregir.

### Mail

Por favor, mándenme un email a <me@diegofreijo.com> cuando tengan todo listo. 

En el mail agreguen:

- El link a la etiqueta `tp65`
- La URL del frontend
- La URL del backend

----

## Requerimientos

En resumen van a tener que:

### 1. Terminar lo que les faltó de esta entrega

- Que funcionen el frontend y backend como si fuese una app de verdad. 
- Completar el reporte

### 2. Arreglar el bug de corrupción de la DB que vienen arrastrando del TP3

De ahora en más la app tiene que funcionar como si fuese a ser usada de verdad. Sin código de mentira que haga parecer que está andando.

### 3. Terminar las notificaciones de haveibeenpwnd 

Todo lo que debió haber estado hecho para el TP3

### 4. Hacer una auditoría de seguridad del código del TP3 y TP4

Esto va a ser la entrada en calor del TP7. Van a usar lo que les enseñé de seguridad las últimas 3 clases para hacer una auditoría de seguridad de todo el  TP3 y TP4. 

Hice un simple pantallazo y encontré 8 vulnerabilidades que ustedes ya están en condiciones de encontrar. Mínimo espero que encuentren 5. Deben haber mas de 8 y no hace falta que encuentren las mismas 8 que yo. Es más, me alegraría que encuentren cosas que yo no ví.

El resultado de la auditoría va a ser otro reporte, otro archivo markdown que van a agregar al repo. En este archivo van a listar las vulnerabilidades que vayan encontrando. Para ayudarlas y que no se pongan a escribir de más, les paso abajo un template de lo que espero de cada vuln. Fíjense que NO les estoy pidiendo que arreglen los problemas de seguridad. Solamente que los informen y expliquen como alguien mas los resolvería.

#### Template de Vulnerabilidad

```md

## <nombre vuln> en <archivo, funcion o endpoint donde se la encontro>

Tipo: <en cual de las OWASP top 10 la encasillarían>

### Prueba de Concepto

<aca va el codigo o screenshot que muestre el problema>

### Riesgo: <bajo | medio | alto>

<explicar en menos de 3 oraciones que es lo que podría pasar de malo si se lo deja como está o como algun atacante podría abusar del problema. Pueden usar mas de 3 oraciones pero les pongo ese número para que vean que no espero una gran redacción si no algo corto y directo>

### Recomendaciones

<que deberían hacer los desarrolladores para corregir el error>

```

