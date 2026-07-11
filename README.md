# Player Shooting Scout

A Data Science and Football Analytics project focused on player shooting performance.

## Week 1 — Shooting Analysis

Research question:

> Which players generated the most threat from their shots?

### Metrics

- Shots
- Goals
- Total xG
- xG per shot
- Goals minus xG

### Dataset

- Competition: Bundesliga
- Season ID: 281
- Data source: [StatsBomb Open Data](https://github.com/statsbomb/open-data)

### Project Structure

- `notebooks/01_scout_finalizacoes.ipynb`
- `reports/figures/`

### Running the Project

```bash
uv sync
uv run --with jupyter jupyter lab