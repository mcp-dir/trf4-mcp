# Ferramentas

Jurisprudência TRF4 expõe 3 ferramentas (todas somente leitura).

### 1. `jurisprudencia_buscar`
**Input**: `termo`, `tipo` (opcional), `tribunais` (opcional), `data_de` (opcional), `data_ate` (opcional), `ordenar` (opcional), `max` (opcional)

Busca jurisprudência (acórdãos, súmulas, orientações jurisprudenciais, temas) por termo ou tese.

### 2. `jurisprudencia_sumulas`
**Input**: `termo`, `max` (opcional)

Busca SÚMULAS (incluindo vinculantes) por termo.

### 3. `jurisprudencia_documento`
**Input**: `id` (opcional), `numeracao` (opcional), `tribunal` (opcional), `ids` (opcional)

Lê o INTEIRO TEOR de uma decisão (texto completo do acórdão, não o resumo).

## Prompts de exemplo

```
Pesquise jurisprudência do TRF4, que responde pela Justiça Federal no Rio Grande do Sul, Santa Catarina e Paraná, direto do seu agente de IA. Matéria previdenciária, tributária federal e responsabilidade da União, com órgão julgador, relator, data, o trecho que casou a busca e o link oficial. A mesma conexão alcança outros 16 tribunais, incluindo STJ e STF, para confrontar o entendimento regional com o superior. Grátis, sem login.
Jurisprudência do TRF4 sobre revisão de benefício previdenciário
Como o TRF4 decide sobre exclusão do ICMS da base do PIS e da COFINS?
Leia o inteiro teor do acórdão que você achou e resuma a tese
```
