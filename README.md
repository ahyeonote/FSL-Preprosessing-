# FSL-Preprosessing-
# fMRI Preprocessing with FSL and Bash

This repository contains bash scripts for preprocessing fMRI data using FSL (FMRIB Software Library). The provided scripts cover various steps from initial data organisation to cleaning and analysis.

## Introduction to Bash Scripting

In bash, you can obtain subject names from your data directory using the following loop:

```bash
for i in *; do
  echo ${i} >> names.txt
done
