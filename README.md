# OptDigits

Este repositorio conserva los datos originales de **Optical Recognition of Handwritten Digits** para el Proyecto 3 de clasificación de dígitos manuscritos con máquinas de vectores de soporte (SVM).

El dataset contiene 5,620 registros. Cada fila representa un dígito manuscrito mediante 64 conteos de píxeles en una cuadrícula de 8 × 8. La última columna contiene la etiqueta, un dígito del 0 al 9.

## Archivos

| Archivo | Contenido |
|---|---|
| [`optdigits.tra`](raw/optdigits.tra) | 3,823 registros para entrenamiento y validación. |
| [`optdigits.tes`](raw/optdigits.tes) | 1,797 registros reservados para la prueba final. |
| [`optdigits.names`](raw/optdigits.names) | Diccionario y documentación original del dataset. |

Los archivos se conservan sin modificaciones y mantienen la separación original entre escritores de entrenamiento y de prueba.

## Fuente y licencia

Alpaydin, E. y Kaynak, C. (1998). *Optical Recognition of Handwritten Digits* [conjunto de datos]. UCI Machine Learning Repository. [DOI 10.24432/C50P49](https://doi.org/10.24432/C50P49).

Los datos se distribuyen bajo la licencia [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
