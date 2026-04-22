# baselines

This directory contains the two baseline implementations used in the experiments reported in the paper, while preserving their original source layouts as much as possible.

- `SGMD22-MBPE`: corresponds to the paper `Efficient Algorithms for Maximal k-Biplex Enumeration` and is referred to as `iTraversal` in the reported experiments.
- `MaximalBiPlex`: corresponds to the paper `Efficient Maximal Biplex Enumerations with Improved Worst-Case Time Guarantee` and is referred to as `BPPivot` in the reported experiments.

To simplify the experimental workflow, some project files and data-loading interfaces in these baseline directories were adapted so that they can run under the build process and prepared input format used in this artifact.

For build and run instructions, please refer to the build files and documentation inside each baseline subdirectory.
