# EuroSys '23 Artifact Evaluation for "Fail through the Cracks: Cross-System Interaction Failures in Modern Cloud Systems"

## Cross-System Interaction Failure Study

### Reproduction of findings and tables

You can view the tables and findings reproduced using Jupyter notebooks here: https://github.com/xlab-uiuc/csi-ae/blob/main/reproduce_study.ipynb

Additionally, if you wish to run the Jupyter notebooks yourself, you may do so here: https://mybinder.org/v2/gh/xlab-uiuc/csi-ae/HEAD
Navigating to this link would bring up an ephemeral Jupyter environment. Once the Jupyter environment is initialized, you can browse to _reproduce_study.ipynb_ and execute it to reproduce all the tables and findings in the paper. The cells on _reproduce_study.ipynb_ should already be executed in the provided binder, but can be re-executed
using the run buttons on the top bar.

### Datasets

1. Analysis of CSI failures open-source systems: https://github.com/xlab-uiuc/csi-ae/blob/main/csi_failure_dataset_open_source_systems.csv
2. Analysis of public-cloud incidents: https://github.com/xlab-uiuc/csi-ae/blob/main/cloud_incidents_gcp_aws_azure.csv

## Cross-System Testing Case Study: Spark-Hive Data Plane

The instructions to reproduce the results in Section 8 can be found in https://github.com/xlab-uiuc/csi-test-ae/ (also configured as a submodule of this repository).
