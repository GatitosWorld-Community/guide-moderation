---
icon: hash
label: Texto
order: 900
author:
-   name: Gacarbla
    link: https://discord.com/users/643575943289634836
    avatar: /assets/pfps/gacarbla.jpg
-   name: Tørtilla
    link: https://discord.com/users/832692087974658079
    avatar: /assets/pfps/tortilla.jpg
---

# Cómo moderar canales de texto

Aquí encontrarás todo lo que un moderador puede necesitar para atender los canales de texto. 

## Básicos

### Cómo entrar al canal
Al entrar en el canal de texto, a no ser que se trate de una urgencia y debas atender un tema rápido, intenta saludar e iniciar un nuevo tema de conversación con los usuarios presentes. Por lo general, la presencia de un moderador reduce el número de infracciones y demuestra que somos personas y no sólo estamos en el chat para advertir.

### Cómo dar una advertencia

Redacta un mensaje mencionando al usuario (Utilizando el @) o usuarios a los que advertir en cuestión, indica con claridad el número de advertencia del que se trata y la razón por la que es advertido. Si lo crees conveniente, invítale a abrir un ticket para explicarle más detalladamente su advertencia.

```  Ejemplo de mensaje de advertencia:
@gacarbla por favor, evita el envío de líricas en el servidor.
```

### Cómo y cuándo dar una sanción

!!!DANGER
Las sanciones **warn** y **mute** se redactan y envían en [Mod-Log](https://discord.com/channels/790289803219566633/866990593535770624). Esto en caso de que el usuario tenga los Mensajes Directos apagados y no reciba el mensaje del bot.
!!!

Una sanción se otorga cuándo el número de advertencias supera las 3 (O la famosa "última advertencia", dónde se avisa que después de la advertencia, viene una sanción) y cuándo la infracción necesita una sanción de manera inmediata. En este preciso apartado, nos centraremos en las sanciones cuándo se llegan a las 3 advertencias. 

En el caso de sanciones de manera inmediata, se profundiza en los siguientes protocolos. Ante la duda, pregunten a mentores o superiores.

!!!DARK
¿Tienes dudas sobre que es cada sanción? Te recomiendo revisar el siguiente enlace dónde se explica cada sanción detalladamente: [Protocolos Sanciones](https://guide.gatitosworld.com/mod/protocols/sanction/)
!!!

## Cómo ejecutar una sanción

El equipo de moderación del servidor utiliza el bot UnbelievaBoat (Unbe para los conocedores) para dar sanciones. Para ejecutar las sanciones, derás seguir el siguiente formato:

```
u!<sanción> <ID> <duración> <razón/motivo>
```

!!!WARNING
Recuerda retirar los "<>" del formato, un ejemplo de sanción es este: u!mute 832692087974658079 3h Sanción de ejemplo.
!!!

Aquí te dejo una lista de las sanciones que puedes dar:

!!!INFO
Cuándo hablamos de la abreviatura, pueden sustituir la palabra de la sanción por su abreviatura. Ejemplo: u!warn = u!w
!!!

==- Warn (Abreviatura "w")

``` Ejemplo:
u!warn 832692087974658079 **Comportamiento Inapropiado**
Has mantenido un comportamiento inapropiado dentro del servidor pese a las advertencias por parte del equipo de moderación.
```

==- Mute (Abreviatura "m")

``` Ejemplo:
u!mute 832692087974658079 3h **Comportamiento Inapropiado**
Has mantenido un comportamiento inapropiado dentro del servidor pese a las advertencias y sanciones previas por parte del equipo de moderación.
```

==- Kick (Abreviatura "k")

``` Ejemplo:
u!kick 832692087974658079 **Cuenta Comprometida**
Tu cuenta ha sido expulsada cómo método de seguridad para el servidor.

> Podrás re-ingresar al servidor una vez recuperes tu cuenta. discord.gg/gatitos
```

==- Ban (Abreviatura "b")

``` Ejemplo:
u!ban 832692087974658079 **Contenido NSFW**
Has enviado contenido NSFW/+18 en el canal Memes del servidor.

> Esta sanción no tiene posibilidad de ser apelada.
```

!!!DANGER
Esta sanción solo puede ser aplicada por mentores o superiores, no intenten aplicarla si son moderadores porque no funcionará.
!!!

==- Temp-ban (Abreviatura "tb")

``` Ejemplo:
u!temp-ban 832692087974658079 2w **Contenido PNSFW**
Has enviado contenido PNSFW en el canal Memes del servidor.

> Podrás re-ingresar al servidor una vez pase el tiempo de sanción.
```

!!!DANGER
Esta sanción solo puede ser aplicada por mentores o superiores, no intenten aplicarla si son moderadores porque no funcionará.
!!!

==- Soft-ban (Abreviatura "sb")

``` Ejemplo:
u!soft-ban 832692087974658079 **Cuenta Comprometida**
Tu cuenta ha sido expulsada cómo método de seguridad para el servidor.

> Podrás re-ingresar al servidor una vez recuperes tu cuenta. discord.gg/gatitos
```

!!!DANGER
Esta sanción solo puede ser aplicada por mentores o superiores, no intenten aplicarla si son moderadores porque no funcionará.
!!!

!!!INFO
Esta sanción no aparece en [Protocolos Sanciones](https://guide.gatitosworld.com/mod/protocols/sanction/), lo que hace esta sanción es darle ban al usuario y quitarle el ban inmediatamente. En este proceso se eliminan los mensajes del usuario en un tiempo de 7 días. 
!!!

==-

!!!DARK IMPORTANTE
En los ejemplos he colocado mi formato de sanciones. Cada moderador tiene la oportunidad de personalizar su formato y su forma de redactar cada sanción cómo quiera. 

Pero recuerden que la sanción debe de cumplir con la función de informar al usuario y otros moderadores sobre el motivo de la sanción.
!!!

### Cómo funciona el tiempo de una sanción

Cómo habrán podido notar, algunas sanciones cómo el mute y el temp-ban llevan una duración. ¿Cómo funciona esta duración?

Los tiempos se otorgan por minutos, horas, días, semanas, meses o años. Deberán escribirlos en Inglés y abreviados.

Ejemplo. u!mute 832692087974658079 **9h** Una razón... 

El "9h" significa "9 hours" o "9 horas" en Español pero de manera abreviada, aquí te dejo una lista de cómo se abrevian los tiempos:

==- Lista de tiempos

- Segundos = **s** (Ej. u!mute 832692087974658079 30s)
- Minutos = **min** (Ej. u!mute 832692087974658079 10min)
- Horas = **h** (Ej. u!mute 832692087974658079 3h)
- Días = **d** (Ej. u!mute 832692087974658079 2d)
- Semanas = **w** (Ej. u!temp-ban 832692087974658079 2w)
- Meses = **mth** (Ej. u!temp-ban 832692087974658079 1mth)
- Años = **y** (Ej. u!mute 832692087974658079 9y)

==-

## Cómo controlar canales de texto alterados

Cuándo decimos que un canal está "alterado", decimos que el canal tiene desorden y muchos usuarios están interactuando al mismo tiempo, por lo que puede llegar a ser complicado controlarlo de manera eficiente y es posible que algunas infracciones se pasen por alto debido a la velocidad de interacción entre usuarios.

**Pasos a seguir:**

==- Paso 1

Identificar si algún otro moderador está activo en el canal. En estos casos se recomienda tener 2 o más moderadores, por lo que si solo estás tú, se recomienda que avises para que más moderadores te asistan.

==- Paso 2

Solicitar a un coordinador o superior el bajar el CD (Cooldown) del canal en cuestión. Esto se recomienda si los mensajes sobrepasan la velocidad de lectura del moderador.

==- Paso 3

Advertir en caso de ser necesario y es muy recomendable estár interactuando con los usuarios. La prescencia de moderadores ejerce una presión psicológica en el canal y por consiguiente, disminuyen las infracciones de los usuarios, los usuarios tienden a controlarse mientras un moderador esté en el canal y ellos lo sepan.

==- 

!!!DARK Recomendación
En caso de que ya no puedas estar más tiempo vigilando el chat, lo más recomendable es pedir ayuda a los demás moderadores.
!!!

## Procedimientos:

### A
==- Acoso
En ciertas situaciones un usuario o grupo de usuarios podría estar acosando a otros.<br>Ésto debe ser tratado con máxima urgencia y prioridad.

[!button text="Ver el procedimiento completo" variant="contrast"](./p/acoso.md)
==- Agresión verbal

[!button text="Ver el procedimiento completo" variant="contrast"](./p/agresion_verbal.md)
==- Amenazas

[!button text="Ver el procedimiento completo" variant="contrast"](./p/amenazas.md)
==- ASCII-ARTs

[!button text="Ver el procedimiento completo" variant="contrast"](./p/ascii.md)
==- 

<br><br>

### C
==- Continuar cadenas

[!button text="Ver el procedimiento completo" variant="contrast"](./p/cadenas.md)
==- 

<br><br>

### D
==- Desacato a la autoridad

==- 

<br><br>

### E
==- Emojis inapropiados
==- Envío de líricas
==- Evasión de sanción con multicuentas
==- 

<br><br>

### F
==- Flood
==- Fotografías
==- Fotografías ajenas
==- 

<br><br>

### G
==- Gifs
==- 

<br><br>

### I
==- Idiomas diferentes al español
==- Imágenes con derechos de autor
==- Iniciar cadenas
==- Inicio de un discurso de odio
==- Inicio de una discusión
==- 

<br><br>

### L
==- Links

[!button text="Ver el procedimiento completo" variant="contrast"](./p/links.md)
==- Links maliciosos

[!button text="Ver el procedimiento completo" variant="contrast"](./p/links.md)
==- 

<br><br>

### M
==- Mención a afiliados
==- Mención a miembros de la gerencia
==- Mención reiterada a usuarios
==- Menor de 13 años
Protocolo de actuación ante menores de 13 años en el servidor. 
!!!WARNING
**PROTOCOLO  DE MÁXIMA IMPORTANCIA**
[!button text="Ver el procedimiento completo" variant="contrast"](./p/menor_edad.md)
!!!

==- Multimedia inapropiada
==- Múltiples cuentas simultáneamente
==- 

<br><br>

### S
==- Saturación de caracteres
==- Saturación de emojis
==- Saturación de menciones
==- Spam o promoción

[!button text="Ver el procedimiento completo" variant="contrast"](./p/spam.md)
==- Stickers inapropiados
==- Suplantación de identidad
==- 

<br><br>

### T
==- Temas controversiales
==- 

<br><br>

### U
==- Uso inapropiado de los 
==- 

<br><br>

### V
==- Vocabulario inapropiado
==- 

<br><br>

### W
==- Walltext
==-

<br><br><br>
** **
**HISTORIAL DE CAMBIOS**<br><br>
`2024-09-09` [!button size="xs" variant="primary" text="Redactado" icon="pencil"]