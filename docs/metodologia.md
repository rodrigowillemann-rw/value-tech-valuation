# Metodologia

O modelo usa analise multicriterio para estimar prioridade tecnologica a partir de maturidade, potencial, impacto, aderencia estrategica e riscos.

## Variaveis

- `trl`: maturidade tecnologica
- `potencial_mercado`: atratividade de mercado
- `impacto_estimado`: impacto economico, social ou ambiental esperado
- `aderencia_estrategica`: alinhamento com a estrategia institucional
- `risco_tecnico`: incerteza tecnica
- `risco_regulatorio`: incerteza regulatoria

## Formula

```text
score = trl*8 + potencial_mercado*0,35 + impacto_estimado*0,30 + aderencia_estrategica*0,25 - risco_tecnico*0,15 - risco_regulatorio*0,10
```

## Interpretacao

O score e comparativo. Ele nao substitui valuation financeiro completo, mas apoia priorizacao inicial de tecnologias em portfolios de PD&I.
