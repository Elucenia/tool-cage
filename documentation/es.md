<!-- ELUCENIA technical documentation · cage · es · no clinical/professional/rights approval -->

# Cuestionario CAGE

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/cage)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### C – ¿Alguna vez ha sentido que debería reducir la cantidad que bebe o dejar de beber?

`c`

### A – ¿Le molesta que otras personas critiquen su forma de beber?

`a`

### G – ¿Se siente culpable por su forma habitual de beber?

`g`

### E – ¿Suele beber por la mañana para reducir el nerviosismo o la resaca?

`e`

## Edición del método

CAGE/Ewing 1984: 4 preguntas binarias, 0–4, corte≥2; portugués Masur–Monteiro 1983

## Fórmula documentada

Un punto por respuesta “sí”: Cut down (reducir), Annoyed (molesto por críticas), Guilty (culpa), Eye-opener (beber al despertar). Punto de corte: ≥ 2.

## Límites y población

Cuestionario breve de cribado de problemas con alcohol, seguido de evaluación clínica. La validación brasileña citada incluyó a hombres ingresados en un hospital psiquiátrico; no debe suponerse un rendimiento idéntico en otras poblaciones. La composición de esa cohorte no es una regla universal de exclusión por sexo.

## Referencias

- [Ewing JA. Detecting alcoholism: the CAGE questionnaire. JAMA, 1984.](https://doi.org/10.1001/jama.1984.03350140051025)

- [Masur J, Monteiro MG. Validation of the "CAGE" alcoholism screening test in a Brazilian psychiatric inpatient hospital setting. Braz J Med Biol Res, 1983.](https://pubmed.ncbi.nlm.nih.gov/6652293/)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Cribado negativo

Un CAGE negativo no excluye un consumo de riesgo actual: prefiera el AUDIT para medir el consumo.


### 2

Una respuesta positiva: por debajo del punto de corte

Pregunte por la cantidad y la frecuencia del consumo (AUDIT).


### 3

Cribado positivo (≥ 2): sospecha de abuso o dependencia del alcohol

Instrumento de cribado: confirmar con evaluación clínica.

