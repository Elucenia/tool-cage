<!-- ELUCENIA technical documentation · cage · en · no clinical/professional/rights approval -->

# CAGE questionnaire

[conditions, sources and permissions](https://elucenia.org/en/tools/cage)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### C – Have you ever felt you should cut down on drinking or stop drinking?

`c`

### A – Do people annoy you by criticizing your drinking?

`a`

### G – Do you feel guilty about the way you usually drink?

`g`

### E – Do you usually drink in the morning to reduce nervousness or a hangover?

`e`

## Method edition

CAGE/Ewing 1984: 4 binary questions, 0–4, cutoff≥2; Portuguese Masur–Monteiro 1983

## Documented formula

One point per answer “yes”: Cut down (cutting down), Annoyed (annoyed by criticism), Guilty (guilt), Eye-opener (drinking on waking). Cutoff: ≥ 2.

## Limits and population

A brief questionnaire screening for alcohol problems, followed by clinical assessment. The cited Brazilian validation involved men hospitalized in a psychiatric hospital; its performance must not be presumed identical in other populations. That cohort’s composition is not a universal sex-based exclusion rule.

## References

- [Ewing JA. Detecting alcoholism: the CAGE questionnaire. JAMA, 1984.](https://doi.org/10.1001/jama.1984.03350140051025)

- [Masur J, Monteiro MG. Validation of the "CAGE" alcoholism screening test in a Brazilian psychiatric inpatient hospital setting. Braz J Med Biol Res, 1983.](https://pubmed.ncbi.nlm.nih.gov/6652293/)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
