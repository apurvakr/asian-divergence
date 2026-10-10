# Eighty years of Asian divergence

An interactive dashboard on how income per head in India, China, Japan, South Korea, Taiwan, Hong Kong and Singapore diverged and converged between 1940 and 2022, with the US as the frontier benchmark. Built for *The Gentle Leviathan*.

**Live page:** enable GitHub Pages for this repository (Settings → Pages → Deploy from branch → `main` / root) and the dashboard is served at `https://<your-username>.github.io/<repo-name>/`.

## What's here

| File | What it is |
|---|---|
| `index.html` | The dashboard. Self-contained: the data is embedded, so it also works when opened straight from disk. Loads d3 v7 from cdnjs. |
| `maddison_gdppc_asia_1938_2022.csv` | The underlying series: country, year, real GDP per capita (2011 international $), rounded to the dollar. |
| `events.json` | The turning points marked on the main chart. |

## Data and caveats

Maddison Project Database 2023 (Bolt and van Zanden), via Our World in Data, licensed CC BY 4.0. Annual data begin in 1950; earlier points are sparse benchmarks, and the pre-1945 figures for Korea and Taiwan are colonial-era reconstructions. Maddison's China series runs higher than some alternative estimates, so China's crossover dates with India are softer than they look.

Citation: Bolt, Jutta and Jan Luiten van Zanden (2024), "Maddison style estimates of the evolution of the world economy: A new 2023 update", *Journal of Economic Surveys*, 1–41.
