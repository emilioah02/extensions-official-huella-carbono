# Huella de Carbono — Agromeda

Calculadora oficial de huella de carbono por cultivo. Cubre Scope 1 (emisiones directas), Scope 2 (energía), Scope 3 (insumos) y secuestro por prácticas regenerativas (no-till, cover crops, agroforestería, compost).

Basada en factores IPCC AR6 + EPA + EcoInvent. País configurable para factor de emisión eléctrica.

## Cómo se usa

1. Selecciona la parcela en `/huella-carbono`.
2. Captura inputs del ciclo (rendimiento esperado, fertilización, maquinaria, electricidad, prácticas).
3. El cálculo corre en MILPA Cloud (`carbon_footprint_v1`); el resultado se guarda en el activity log y aparece como widget KPI en el dashboard.

## Knowledge packs incluidos

- `factores-emision.milpa-pack.yaml` — factores de emisión IPCC + EcoInvent.
- `practicas-mitigacion.milpa-pack.yaml` — recetas para reducir huella por sistema productivo.

## License

Propietaria — Agromeda S.A.S. de C.V.
