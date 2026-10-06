<!-- ELUCENIA technical documentation · cage · pt-BR · no clinical/professional/rights approval -->

# Questionário CAGE

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/cage)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### C – Alguma vez o(a) Sr.(a) sentiu que deveria diminuir a quantidade de bebida ou parar de beber?

`c`

### A – As pessoas o(a) aborrecem porque criticam o seu modo de beber?

`a`

### G – O(a) Sr.(a) se sente culpado(a) pela maneira com que costuma beber?

`g`

### E – O(a) Sr.(a) costuma beber pela manhã para diminuir o nervosismo ou a ressaca?

`e`

## Edição do método

CAGE/Ewing 1984:4 perguntasbinárias 0–4, corte≥2; PTMasur Monteiro 1983

## Fórmula documentada

Um ponto por resposta “sim”: Cut down (diminuir), Annoyed (aborrecido com críticas), Guilty (culpa), Eye-opener (beber ao acordar). Ponto de corte: ≥ 2.

## Limites e população

Questionário breve de rastreamento de problemas com álcool, seguido de avaliação clínica. A validação brasileira citada envolveu homens internados em hospital psiquiátrico; seu desempenho não deve ser presumido idêntico em outras populações. A composição dessa coorte não é uma regra universal de exclusão por sexo.

## Referências

- [Ewing JA. Detecting alcoholism: the CAGE questionnaire. JAMA, 1984.](https://doi.org/10.1001/jama.1984.03350140051025)

- [Masur J, Monteiro MG. Validation of the "CAGE" alcoholism screening test in a Brazilian psychiatric inpatient hospital setting. Braz J Med Biol Res, 1983.](https://pubmed.ncbi.nlm.nih.gov/6652293/)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Rastreamento negativo

Um CAGE negativo não exclui uso de risco atual: prefira o AUDIT para medir o consumo.


### 2

Uma resposta positiva: abaixo do ponto de corte

Pergunte sobre quantidade e frequência do consumo (AUDIT).


### 3

Rastreamento positivo (≥ 2): suspeita de abuso ou dependência de álcool

Instrumento de rastreamento: confirme com avaliação clínica.

