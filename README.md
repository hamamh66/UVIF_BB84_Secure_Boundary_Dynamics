# UVIF-BB84 Secure Boundary Dynamics

This repository supports the manuscript:

**UVIF-Guided Resource-Aware Secure Boundary Estimation for BB84-Inspired Finite-Key Quantum Communications**

## Overview

This project provides a reproducible computational framework for studying secure-to-insecure transition dynamics in BB84-inspired finite-key quantum communication systems. The framework combines conventional finite-key/QBER-oriented security assessment with a Unified Variational Intelligence Framework (UVIF) layer that models operational security as a dynamic equilibrium among uncertainty, risk, implementation complexity, leakage burden, resource pressure, and stability reinforcement.

The objective is not to replace composable quantum-security proofs, but to provide an operational intelligence and decision-support layer for analyzing how security margins evolve under disturbance, adversarial pressure, resource variability, and implementation drift.

## Key Features

- BB84-inspired finite-key QBER simulation
- Conventional finite-key boundary estimation
- UVIF operational free-energy scoring
- Secure-to-insecure transition analysis
- Disturbance, adversarial pressure, and drift modeling
- Resource-aware shot-count robustness analysis
- UVIF force decomposition and stability-regime interpretation
- Temporal security-trajectory simulation
- Early-warning indicator generation
- Bootstrap confidence summaries
- Ablation comparison against QBER-only and reduced UVIF variants
- Decision-support regime mapping for operational monitoring

## Repository Structure

```text
.
├── notebooks/
│   └── UVIF_BB84_FiniteKey_Boundary_Dynamics_Array_Targeted_Upgrade.ipynb
├── figures/
│   ├── fig_conventional_vs_uvif_boundary.png
│   ├── fig_uvif_stability_phase_map.png
│   ├── fig_uvif_force_decomposition.png
│   ├── fig_disturbance_response_and_uvif_susceptibility.png
│   ├── fig_shot_count_resource_robustness.png
│   ├── fig_phase_margin_sensitivity.png
│   ├── fig_temporal_security_trajectories.png
│   ├── fig_early_warning_indicator.png
│   └── fig_array_ablation_boundary_comparison.png
├── tables/
│   ├── manuscript_table_boundary_comparison.csv
│   ├── manuscript_table_uvif_force_summary.csv
│   ├── manuscript_table_resource_robustness.csv
│   ├── manuscript_table_phase_margin_summary.csv
│   ├── manuscript_table_temporal_scenarios.csv
│   ├── manuscript_table_array_ablation_boundary_comparison.csv
│   ├── manuscript_table_array_decision_support_regime_actions.csv
│   ├── manuscript_table_array_bootstrap_boundary_confidence.csv
│   ├── manuscript_table_array_resource_sensitivity_summary.csv
│   ├── manuscript_table_array_early_warning_summary.csv
│   └── manuscript_table_array_main_findings.csv
├── outputs/
│   ├── outputs_summary.txt
│   ├── outputs_summary_array_targeted_upgrade.txt
│   ├── run_manifest.json
│   └── study_configuration.json
├── logs/
│   └── run_log.txt
├── LICENSE
└── README.md
```

## Computational Workflow

The notebook follows a reproducible workflow:

1. Configure the BB84-inspired finite-key simulation setting.
2. Generate stochastic QBER trajectories under disturbance, adversarial pressure, and drift.
3. Estimate conventional finite-key security margins.
4. Compute UVIF operational free-energy and stability scores.
5. Estimate secure-to-insecure boundaries.
6. Quantify bootstrap confidence intervals.
7. Evaluate resource sensitivity across shot-count configurations.
8. Generate temporal security trajectories.
9. Extract early-warning indicators.
10. Perform ablation studies and decision-support regime mapping.
11. Save all manuscript-ready tables, figures, logs, and summaries.

## Methodological Positioning

The proposed framework should be interpreted as an operational and computational intelligence layer for finite-key quantum communication analysis. It complements, rather than replaces, formal quantum-security proofs. Its contribution lies in modeling security degradation as a dynamic transition process influenced by multiple operational forces.

## Main Outputs

The notebook generates manuscript-ready figures and tables for conventional-versus-UVIF boundary comparison, stability phase mapping, operational force decomposition, disturbance response, resource robustness, phase-margin sensitivity, temporal trajectories, early-warning indicators, ablation evidence, decision-support regimes, bootstrap confidence, and manuscript-ready findings.

## Requirements

The notebook is designed for Google Colab and standard Python scientific-computing environments.

Recommended packages:

```text
numpy
pandas
matplotlib
scipy
scikit-learn
```

## Reproducibility

All generated outputs are saved automatically to a structured project directory, including figures, tables, logs, configuration files, and output summaries. The workflow uses explicit configuration settings and reproducible simulation parameters to support manuscript validation and future extension.

## Suggested Citation

```bibtex
@misc{Hamam2026UVIFBB84,
  author       = {Habib Hamam},
  title        = {UVIF-BB84 Secure Boundary Dynamics: Resource-Aware Operational Security Estimation for BB84-Inspired Finite-Key Quantum Communications},
  year         = {2026},
  howpublished = {GitHub repository},
  note         = {Reproducible implementation of a UVIF-guided operational-intelligence framework for secure-to-insecure boundary estimation in BB84-inspired finite-key quantum communications}
}
```

## License

This repository is intended for academic and research use. A formal license file should be added before public release.

## Contact

For questions about the framework, manuscript, or reproducibility materials, please contact the corresponding author through the associated publication or repository profile.
