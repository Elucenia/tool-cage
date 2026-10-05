<!-- ELUCENIA technical documentation · cage · it · no clinical/professional/rights approval -->

# Questionario CAGE

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/cage)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### C – Ha mai sentito di dover ridurre la quantità di alcol o smettere di bere?

`c`

### A – Si infastidisce quando altre persone criticano il suo modo di bere?

`a`

### G – Si sente in colpa per il suo modo abituale di bere?

`g`

### E – Beve abitualmente al mattino per ridurre il nervosismo o i postumi di una sbornia?

`e`

## Edizione del metodo

CAGE/Ewing 1984: 4 domande binarie, 0–4, soglia≥2; portoghese Masur–Monteiro 1983

## Formula documentata

Un punto per risposta “sì”: Cut down (ridurre), Annoyed (irritato dalle critiche), Guilty (colpa), Eye-opener (bere al risveglio). Soglia: ≥ 2.

## Limiti e popolazione

Breve questionario di screening dei problemi con l’alcol, seguito da valutazione clinica. La validazione brasiliana citata ha coinvolto uomini ricoverati in un ospedale psichiatrico; non si deve presumere un rendimento identico in altre popolazioni. La composizione di tale coorte non è una regola universale di esclusione per sesso.

## Riferimenti

- [Ewing JA. Detecting alcoholism: the CAGE questionnaire. JAMA, 1984.](https://doi.org/10.1001/jama.1984.03350140051025)

- [Masur J, Monteiro MG. Validation of the "CAGE" alcoholism screening test in a Brazilian psychiatric inpatient hospital setting. Braz J Med Biol Res, 1983.](https://pubmed.ncbi.nlm.nih.gov/6652293/)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
