# News Classification Lab (AG News + Bonus RPP)

**Task 2 — Entrenamiento y evaluación con Transformers (RoBERTa, DeBERTa, ModernBERT).**  
Incluye versión ligera compatible para Colab y Bonus de clasificación de 50 noticias de RPP.

---

## 🎯 Objetivo
- Cargar **AG News** y dividir en **70/15/15**.
- Fine-tuning de **3 modelos** (RoBERTa, DeBERTa-v3-small, ModernBERT-base).
- Evaluación en **test** (una sola vez) con **F1 macro**.
- **Gráfico comparativo** de F1.
- **Bonus**: clasificar 50 noticias de **RPP** en {World, Sports, Business, Sci/Tech}.

---

## 📂 Estructura
- `notebooks/agnews_train_eval.ipynb` — Notebook principal (ligero y con fallback).
- `data/` — Salidas del Bonus (p. ej., `rpp_classified.json`).
- `outputs/` — Métricas y gráficos (`f1_scores.csv`, `metrics.json`, `f1_barplot.png`, `rpp_distribution.png`).

---

## ⚙️ Requisitos
```bash
pip install -r requirements.txt
# News_Classification-lab
Segundo repo
