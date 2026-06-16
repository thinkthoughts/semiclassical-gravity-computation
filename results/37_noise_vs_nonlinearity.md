# 37 Noise vs Nonlinearity

## Purpose
This notebook compares deterministic state-dependent amplification against stochastic fluctuations.

## Reliability summary
- **deterministic_nonlinear** — crossing rate: 1.0; median crossing time: 6.0; mean max distinguishability: 0.9313861596457909
- **linear_baseline** — crossing rate: 0.0; median crossing time: nan; mean max distinguishability: 0.02
- **stochastic_noise** — crossing rate: 0.0; median crossing time: nan; mean max distinguishability: 0.05794184234677349

## Model comparison
- **Linear baseline** — Distinguishability remains near its initial value. No reliable threshold crossing.
- **Deterministic nonlinear amplification** — Distinguishability grows systematically. Reliable threshold crossing supports decision extraction.
- **Stochastic noise comparison** — Distinguishability fluctuates. Fluctuations alone do not provide reliable computational amplification.

## Engineering statement
- **Statement**: Reliable decision extraction requires repeatable threshold crossing.
- **Observation**: Noise can fluctuate without producing systematic amplification.
- **Context**: Nonlinear state-dependent dynamics may amplify distinguishability reliably.
- **Next Step**: Compare toy nonlinear amplification with physically motivated stochastic models.

## Bottom line
Noise is not the same thing as computationally useful amplification. A stochastic process may occasionally increase distinguishability, but reliable computation requires repeatable threshold crossing that can support decision extraction.