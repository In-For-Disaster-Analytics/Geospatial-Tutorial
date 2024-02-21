## Motivation

This is the template for a cookbooks' tutorial. The goal is to provide an environment that can be reproducible and stood up on TACC Systems. 

To update the Template Change the environment.yml and if necessary the requirements.txt

Update this readme with the instructions on how to run your cookbook. 

Once all of your files have been added and updated. You will create a new [docker application ](https://github.com/In-For-Disaster-Analytics/Cookbook-Docker-Template) from the template. 

- This will be loaded into the [cookbook's UI](https://in-for-disaster-analytics.github.io/cookbooks-ui/#/)
- Then shared publicly. 
- You can then contact your portal manager to make the cookbook available on the portal. 
## Authors

William Mobley - wmobley@tacc.utexas.edu

## Contributors

<a href="https://github.com/In-For-Disaster-Analytics/sites-and-stories-nlp/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=In-For-Disaster-Analytics/Cookbook-Tutorial-Template" />
</a>

## Structure

## Foundations

.binder/environment.yml
.binder/requirements.txt
Readme.md

## Running the Cookbook

### Parameters

- **Update Cookbook:** This parameter is used to update the notebooks of the cookbook to the latest version.

- **Update Conda Environment:** This parameter is used to update the conda environment to the latest version.

Note: Both parameters are not applicable on your first run. These options are designed for enhancing subsequent uses.

### Initial Setup

The initial run will install the necessary packages and download the required models. Please be prepared for the initial run to take approximately 15 minutes.

### Queues

Lonestar6 hosts [84 A100 GPU nodes](https://docs.tacc.utexas.edu/hpc/lonestar6/#table2) that are configured identically to the compute nodes with the addition of 3 NVIDIA A100 GPUs. Each A100 GPU has a peak performance of 9.7 TFlops in double precision and 312 TFlops in FP16 precision using the Tensor Cores.

For more information, please see the [Lonestar6 User Guide](https://docs.tacc.utexas.edu/hpc/lonestar6/#table5).

### Allocation

This cookbook requires an allocation on TACC systems. If you do not have an allocation, you can request one [here](https://portal.tacc.utexas.edu/allocations).
