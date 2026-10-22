# When Reasoning Changes What Is Worth Asking

**Bounded Information Seeking in Humans and Language Models**

## Overview

People playing Mastermind trade informativity for interpretability: they favor queries whose feedback they can interpret, even when other queries are more informative (Cheyette et al., 2025). This project extends that work to ask whether language models show the same trade-off, and whether independent measures of how they process evidence can predict how a reasoning aid changes which questions are worth asking.

The project has three parts:

1. **Human modeling:** reproduce the published behavioral findings and model comparison on the released human data.
2. **Language models:** run language models on the same game positions people saw and on full games, and fit the same human model to their play.
3. **Capacity manipulation:** give a model a structured reasoning aid and test whether the fitted models predict how the aid changes the usefulness of each question.

## Status

Work in progress. Code and results will be added as the project develops.

## References

- Cheyette, S. J., Callaway, F., Bramley, N. R., Nelson, J. D., & Tenenbaum, J. B. (2025). Representational constraints shape human information-seeking. *PsyArXiv*. https://doi.org/10.31234/osf.io/w4b3y. Data: https://osf.io/vjrqu
- Rothe, A., Lake, B. M., & Gureckis, T. M. (2018). Do people ask good questions? *Computational Brain & Behavior, 1*, 69–89.
