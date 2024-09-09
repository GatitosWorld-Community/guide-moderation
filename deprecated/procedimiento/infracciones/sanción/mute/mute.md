---
label: Mute
order: 70
icon: alert
authors:
  - name: gacarbla
    link: https://discord.com/users/643575943289634836
    avatar: ../../../../profiles/gacarbla.jpg
---
# Mute
## Definición
El "mute" en VoiceChat (VC) implica bloquear temporalmente la capacidad de hablar. Actualmente, no existe una función automatizada para aplicarlo o eliminarlo, por lo que se realiza manualmente haciendo clic derecho sobre el usuario en ambos casos.

Dado que no hay un comando específico, utilizamos el `u!warn` y especificamos que se trata de una sanción que afecta a los canales de voz.

Esta sanción puede ser desactivada fácilmente al salir y regresar al servidor. Se aconseja supervisar al usuario sancionado para prevenir que utilice este método, el cual puede resultar en una expulsión permanente de su cuenta.

## Cuándo se aplica

Esto puede ser difícil de explicar, ya que dependerá del juicio del moderador, pero podría resumirse así:

- **Comportamiento involuntario:** Si se percibe que el usuario no tuvo intenciones negativas, esperaremos hasta que haya recibido 2 advertencias. Luego, al darle la tercera, aplicaremos la sanción.

- **Comportamiento intencional:** Si se nota que el usuario actuó con intención, aplicaremos la sanción directamente después de la segunda advertencia, sin esperar a la tercera.

## Cómo se aplica
Después de garantizar que hemos recogido las advertencias necesarias, nos dirigiremos al canal de mod-log para redactar el uso del comando.

Seguiremos el formato preestablecido y adjuntaremos las pruebas correspondientes de cada ocasión en que le hemos advertido, las cuales estarán guardadas en nuestro repositorio.

!!!warning ¡CUIDADO!
Recuerda mantener al usuario en estado de silencio.<br>
**El bot no lo hará en tu lugar.**
!!!

## Formato
Aunque cada moderador tiene su estilo al aplicar una sanción, existen requisitos mínimos para hacerlo de manera adecuada:
- Tipo de sanción (Mute).
- Duración.
- Razón.
- Procedimiento para levantar el mute.

+++ Formato de ejemplo 1
```
u!warn <id> **MUTE DE <tiempo> HORAS**
<razón>
> Una vez el tiempo de su sanción culmine, puede abrir un ticket en <#822611489370144808> para solicitar la retirada del silencio.
```
> **MUTE DE 3 HORAS**<br>
> Reproducción de audios molestos en los canales de voz.<br>
> Una vez el tiempo de su sanción culmine, puede abrir un ticket en `#🎫・ayuda` para solicitar la retirada del silencio.
+++ Formato de ejemplo 2
```
u!warn <id> **MUTE DE <tiempo> HORAS** \|\| <razón> \|\| Una vez el tiempo de su sanción culmine, puede abrir un ticket en <#822611489370144808> para solicitar la retirada del silencio.
```
> **MUTE DE 3 HORAS** \|\| Reproducción de audios molestos en los canales de voz. \|\| Una vez el tiempo de su sanción culmine, puede abrir un ticket en `#🎫・ayuda` para solicitar la retirada del silencio.
+++

!!!info Y lo elevo a 3...
Al aplicar un mute, se multiplcará la duración por 3 a la duración de la sanción anterior.<br>Por ejemplo, si su sanción previa en el canal de voz era de 9 horas, ahora serán 27 horas. Sin embargo, si no tiene ninguna sanción previa, la duración será de solo 3 horas.
!!!

<br><br><br>
** **
**HISTORIAL DE CAMBIOS**<br><br>
`2023-09-27` [!button size="xs" variant="primary" text="Actualizado" icon="issue-draft"]<br>
`2023-08-21` [!button size="xs" variant="primary" text="Redactado" icon="pencil"]