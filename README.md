# REBASE.md

## Objetivo
Limpiar el historial de commits en el proyecto de Terraform, reescribiendo los mensajes de los commits y fusionando aquellos que no son necesarios.

## Pasos realizados

1. Se crearon varios commits con mensajes poco claros para simular un historial desordenado.
2. Se utilizó el comando `git rebase -i HEAD~N` para editar los últimos N commits.
3. Se cambiaron los mensajes de los commits utilizando la opción `reword`.
4. Se fusionaron algunos commits innecesarios usando `squash` o `fixup`.
5. Se realizó un `git push --force` para actualizar el historial en el repositorio remoto.

## Conclusión
Este proceso permite mejorar la claridad y calidad del historial de commits en el repositorio, facilitando la comprensión del desarrollo del proyecto y la colaboración entre los miembros del equipo.
