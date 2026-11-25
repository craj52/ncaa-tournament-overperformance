# Data source

This project used a combined historical NCAA Tournament dataset containing KenPom efficiency statistics, tournament seeds, and tournament results for 2001–2025 (1,602 team observations).

**The CSV is intentionally not provided** because the underlying KenPom data is subject to redistribution restrictions. Data source: [KenPom](https://kenpom.com/).

To run the analysis with an appropriately obtained copy of the original dataset, save it at:

`data/kenpom_tournament_data.csv`

The expected columns (as interpreted by R with `check.names = TRUE`) are:

`Season`, `Team`, `Wins.0.6.`, `Coach`, `AP.Top.25`, `Top.12`, `X4.`, `AdjOE`, `RankAdjOE`, `AdjDE`, `RankAdjDE`, `Seed`, `Top21_O`, `Top37_D`.

The code and the original generated results are included so the research can be reviewed without the underlying dataset.
