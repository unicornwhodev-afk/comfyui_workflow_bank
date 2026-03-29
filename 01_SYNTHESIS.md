# Synthesis

## Benchmark

<picture>
  <img src="assets/charts/06_catalog_benchmark.svg" alt="Catalog benchmark" width="100%" />
</picture>

## Coverage matrix

<picture>
  <img src="assets/charts/07_coverage_matrix.svg" alt="Coverage matrix" width="100%" />
</picture>

## Key readings

### Domain composition
- **image** porte l'essentiel du volume, avec **81 workflows**
- **video** constitue le second bloc avec **30 workflows**
- **3D** et **workflow audio** restent plus compacts mais spécialisés

### Central technical anchors
- **KSampler** est le nœud le plus central du dépôt
- **VAEDecode** et **CLIPTextEncode** suivent immédiatement derrière
- **`checkpoints/sd_xl_base_1.0.safetensors`** est la dépendance modèle la plus réutilisée

### Maintenance lens
- la maintenance doit commencer par le **socle image**
- les **workflows vidéo** demandent plus d'attention sur les versions
- les familles **3D** et **audio** justifient des cas de test dédiés

## Quick pointers
- Lire le README pour la vue vitrine
- Utiliser `02_WORKFLOWS.md` pour la recherche fonctionnelle
- Utiliser `03_NODES.md` et `04_MODELS.md` pour les audits transverses
