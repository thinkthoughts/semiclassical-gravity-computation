# 17 Nonlinearity

## Purpose

This notebook connects the physics pathway from Schrödinger–Newton-type dynamics to the computational consequences used in arXiv:2606.14806.

## Linear versus nonlinear quantum evolution

- **evolution** — linear: `i∂ψ/∂t = Hψ`; nonlinear: `i∂ψ/∂t = H[ψ]ψ`
- **Hamiltonian** — linear: `H is fixed independently of ψ`; nonlinear: `H depends on ψ`
- **state distinguishability** — linear: `Inner-product structure constrains distinguishability`; nonlinear: `State-dependent evolution can amplify distinctions`
- **computational baseline** — linear: `BQP`; nonlinear: `Can exceed standard BQP in generic nonlinear models`
- **physical role** — linear: `Standard quantum theory`; nonlinear: `Theory feature under investigation`

## Computational consequences

1. **State dependence** — The evolution rule depends on the quantum state being evolved.
2. **Nonlinear evolution** — The map from initial state to later state is not linear.
3. **Enhanced distinguishability** — Small differences between states can be amplified by nonlinear dynamics.
4. **Efficient NP-complete power** — Generic nonlinear quantum models can permit efficient solutions to NP-complete problems.
5. **Physical constraint** — Observed computational limits make this a test of physical plausibility.

## Engineering statement

- **Statement:** Computational consequences should inform physical interpretation.
- **Observation:** Nonlinear quantum evolution changes state distinguishability.
- **Context:** Enhanced distinguishability may permit efficient NP-complete solutions.
- **Next Step:** Determine whether physically realized dynamics remain computationally constrained.

## Bottom line

The significance of nonlinearity is not merely mathematical. Nonlinear state-dependent evolution may alter computational power, making complexity theory relevant to physical theory choice.

## Reading questions

- **23_bao_bouland_jordan** — How does Bao–Bouland–Jordan formalize the connection between nonlinear dynamics and computational power?
- **23_bao_bouland_jordan** — Which computational ingredients are required for the NP-complete consequence?
- **23_bao_bouland_jordan** — Which assumptions drive the paper's complexity-theoretic result?
- **29_quantum_gravity_implications** — How should this computational consequence constrain interpretation of semiclassical gravity?