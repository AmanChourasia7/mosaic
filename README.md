<p align="center">
  <!--<a href="https://github.com/YOUR_ORG/MOSAIC/actions/workflows/ci.yml"><img alt="CI" src="https://img.shields.io/github/actions/workflow/status/YOUR_ORG/MOSAIC/ci.yml?branch=main&style=flat-square&logo=github-actions&logoColor=white&label=CI"></a>
  <a href="https://github.com/YOUR_ORG/MOSAIC/actions/workflows/examples-compile.yml"><img alt="examples" src="https://img.shields.io/github/actions/workflow/status/YOUR_ORG/MOSAIC/examples-compile.yml?branch=main&style=flat-square&logo=github-actions&logoColor=white&label=examples"></a>
  <a href="YOUR_DISCORD_INVITE"><img alt="discord" src="https://img.shields.io/discord/YOUR_DISCORD_ID?style=flat-square&logo=discord&logoColor=white&label=discord&color=5865F2"></a>-->
  <br>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.png">
    <img src="assets/banner-light.png" alt="MOSAIC: a common Python workflow to compare SciML/PDE solvers" width="640">
  </picture>
</p>

MOSAIC is a common Python workflow for comparing SciML/PDE solvers.
The workspace combines:

- single-interface solver execution -- different numerical, neural-network, JAX-based, and HPC solvers can be plugged
- common solver interfaces -- run different PDE solvers without rewriting the surrounding analysis pipeline
- standardized metrics -- compare accuracy, convergence, stability, runtime, and scaling consistently
- automated result generation -- produce plots, tables, and reports from the same benchmark configuration
- reproducible comparisons -- keep solver configurations, metrics, and benchmark results consistent across experiments
- scalable workflows -- evaluate solver performance across CPUs, GPUs, and HPC systems
- extensible architecture -- add your own solver and plug it directly into the comparison pipeline
