# LSTM_Tutorial
Keras LSTM Tutorial - Binary Classifier



| Oración                               | Categorías Léxicas (Características)                         | Transformación                        |
| ------------------------------------ | ----------------------------------------------------------- | -------------------------------------- |
| El gato está en la alfombra.          | [Det, Sustantivo, Verbo, Preposición, Det, Sustantivo]       | Oración original                       |
| El gato está descansando en la alfombra. | [Det, Sustantivo, Verbo, Verbo, Preposición, Det, Sustantivo] | Sustitución: "descansando" en lugar de "en" |
| Un perro duerme en el sofá.           | [Det, Sustantivo, Verbo, Preposición, Det, Sustantivo]       | Generalización: "perro" en lugar de "gato" |
| Los perros están durmiendo en el sofá. | [Det, SustantivoPlural, Verbo, GerundioVerbo, Preposición, Det, Sustantivo] | Pluralización: "perros" y forma de gerundio de "dormir" |
| A los gatos les gusta el pescado.     | [SustantivoPlural, Verbo, Sustantivo]                        | Simplificación: Eliminación de un determinante ("el") |
| El pescado es gustado por los gatos.  | [SustantivoPlural, Verbo, Verbo, Preposición, SustantivoPlural] | Voz pasiva                             |
```
