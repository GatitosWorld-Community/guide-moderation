---
label: Saturación del micrófono
authors:
  - name: gacarbla
    link: https://discord.com/users/643575943289634836
    avatar: ../../../profiles/gacarbla.jpg
  - name: ChatGPT
    avatar: ../../../profiles/chatgpt.png 
visibility: hidden
---
[!button size="xs" variant="warning" text="No revisado" icon="alert" corners="pill"](../../../info/contenido_sin_revisar/contenido_sin_revisar.md)

# Saturación del micrófono
La saturación de micrófono puede causar molestias y dificultades en la comunicación en los canales de voz. Abordaremos las situaciones de saturación de micrófono con el objetivo de mantener un ambiente de voz claro y cómodo para todos los usuarios.

## Tipos de Saturación de Micrófono
La saturación de micrófono puede ser de dos tipos: intencional o no intencional. Dependiendo del caso, seguiremos un procedimiento específico.

### Saturación intencional
En el caso de detectar saturación de micrófono intencional, se emitirá una advertencia al usuario. Si continúa con la saturación de micrófono después de la advertencia, se aplicará una sanción tipo mute.

### Saturación no intencional
Si se trata de una saturación de micrófono no intencional, se otorgará una primera advertencia al usuario para informarle sobre la situación y recordar la importancia de mantener un audio claro para todos los miembros del canal.<br>
En caso de que la saturación no intencional persista después de la primera advertencia, se emitirá una segunda advertencia más enérgica. Si la saturación persiste aún después de las advertencias, se aplicará una sanción tipo mute.

## Formato de sanción
+++ 1 advertencia
```
u!warn <id> **MUTE DE <tiempo> HORAS DE VC**
Saturación de micrófono constante y molesta en los canales de voz pese a la advertencia previa del equipo de moderadores.

> Podrá solicitar la retirada de su mute en <#822611489370144808> una vez el tiempo de su sanción culmine.
```
+++ 2 advertencias o más
```
u!warn <id> **MUTE DE <tiempo> HORAS DE VC**
Saturación de micrófono persistente en los canales de voz pese a las advertencias previas del equipo de moderadores.

> Podrá solicitar la retirada de su mute en <#822611489370144808> una vez el tiempo de su sanción culmine.
```
+++

<br><br><br>
** **
**HISTORIAL DE CAMBIOS**<br><br> 
`2023-08-29` [!button size="xs" variant="primary" text="Redactado" icon="pencil"]