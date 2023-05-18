# `\data`

`hadcrut5-global-temperatures-annual.csv`: globally-averaged temperature anomalies from CRU. Columns include:

  - `year`:
  - `annual`: the original temperature anomaly reported by CRU
  - `annual_1850to1900`: the temperature anomaly relative to the preindustrial (1850–1900) average
  - `annual_smoothed`: the result of fitting a LOESS smoother to the `annual_1850to1900` column
