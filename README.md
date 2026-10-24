# EnergyBench

Open leaderboard for energy time-series forecasting: electricity load, solar and wind generation, power prices,
gas & fuel markets and EV charging. Zero-shot time-series foundation models, trained deep networks
(Time-Series-Library) and statistical baselines are scored with one protocol, with a *fresh* track tested on data
published after the models' training cut-off (October 2025 onward).

**Leaderboard:** https://energybench.github.io

This repository holds the static site. `index.html` embeds all results; the same data is in
[`data/results.json`](data/results.json) (per-task scores for every model, model and dataset metadata).
