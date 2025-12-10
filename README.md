# data-237-final-project

# Forgotten Wars: Quantifying the Attention Hierarchy of Global Conflict

**Author:** La'Tahvia Williams  
**Institution:** University of Chicago  
**Course:** DATA 23700 - Data Science for Human Rights  
**Quarter:** Autumn 2025

---

## Project Overview

This research analyzes **884,216 conflict events** from 2020-2025 across **11 countries**, correlating documented violence with Google search volume to answer: **Does public attention follow humanitarian severity, or other factors?**

### Core Finding
**ATTENTION = f(Western Political Salience) NOT f(Human Suffering)**

Correlation ranges from **r = 0.77** (Palestine) to **r = 0.03** (Yemen internal)—a **25-fold difference** independent of death toll, distance, or media access.

### The Yemen Paradox
- **Internal conflict:** 52,235 deaths → r = 0.03
- **Red Sea attacks:** 0 Western deaths → r = 0.24
- **Result:** 8x more attention for threats to commerce than 52,235 human lives

---

## Key Findings

### Attention Hierarchy (5 Tiers)

| Tier | Correlation | Countries | Deaths | Pattern |
|------|-------------|-----------|--------|---------|
| **0** | r > 0.70 | Palestine (0.77), USA (0.75) | 70,366 / 496 | Geopolitical + Domestic |
| **1** | r = 0.30-0.50 | Ukraine (0.40), Myanmar (0.30) | 215,941 / 89,665 | Sudden Shock |
| **2** | r = 0.20-0.30 | Yemen Red Sea (0.24) | 0 | Commercial Threat |
| **3** | r = 0.10-0.20 | Syria (0.16), Pakistan (0.15), Brazil (0.15) | 41,178 / 13,782 / 41,686 | Forgotten Wars |
| **4** | r < 0.10 | India (0.08), Mexico (0.08), Yemen Int (0.03) | 6,660 / 46,812 / 52,235 | Normalized/Forgotten |

### Four Attention Patterns

1. **Sudden Shock** (Ukraine, Myanmar, Palestine) - 3-month half-life, exponential decay
2. **Domestic Movements** (USA) - Sustained through participation (496 deaths → r = 0.75)
3. **Forgotten Wars** (Syria, Yemen) - Complete decoupling despite ongoing deaths
4. **Normalized Violence** (Mexico) - 46,812 deaths framed as "crime" → invisible

---

## Methodology

**Data Sources:**
- ACLED: 884,216 conflict events (2020-2025)
- Google Trends: 44 search terms across 3 tiers

**Analysis:**
- Pearson correlation coefficients
- Monthly aggregation smoothing volatility
- Temporal decay analysis
- Pattern classification

**Tools:** Python, pandas, numpy, scipy, Altair, Chart.js

---


## Implications

**For Humanitarian Organizations:**
1. Prepare for 3-month attention half-life
2. Build reserves during peak engagement
3. Redirect forgotten wars to diplomatic channels
4. Frame strategically (conflict vs crime matters)
5. Leverage participatory engagement

**Academic Contribution:**
- Quantifies "compassion fatigue" (Moeller, 1999)
- Validates "hierarchies of suffering" (Chouliaraki, 2006)
- Confirms accelerating attention dynamics (Lorenz-Spreen et al., 2019)

---

## Key References

- ACLED (2025). *Armed Conflict Location & Event Data*. https://acleddata.com/
- Chouliaraki, L. (2006). *The Spectatorship of Suffering*. Sage.
- Lorenz-Spreen et al. (2019). "Accelerating Collective Attention." *Nature Communications*.
- Moeller, S. D. (1999). *Compassion Fatigue*. Routledge.

---

## Project Stats

| Metric | Value |
|--------|-------|
| Events Analyzed | 884,216 |
| Countries | 11 |
| Time Period | 2020-2025 |
| Search Terms | 44 |
| Correlation Range | 0.03 to 0.77 |
| Notebook Cells | 182 |
| Visualizations | 8 |

---

## Contact

**La'Tahvia Williams**  
University of Chicago  
[GitHub](https://github.com/Tahvia127)

---

## License

Academic project for DATA 23700. Data used under ACLED agreement and Google Trends public API.

**Citation:**
```
Williams, L. (2025). Forgotten Wars: Quantifying the Attention Hierarchy 
of Global Conflict. University of Chicago, DATA 23700.
```

---

**⭐ Star this repo if you find it useful!**

**Last Updated:** December 2025
