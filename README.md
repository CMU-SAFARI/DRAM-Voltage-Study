# Characterization results of modern DRAM devices under reduced-voltage operation

Characterization data collected on 31 DDR3L (low-voltage) SO-DIMMs manufactured between 2015 and 2016. You can find the background and analysis on the data in our SIGMETRICS'17/POMACS'17 paper "Understanding Reduced-Voltage Operation in Modern DRAM Chips: Characterization, Analysis, and Mechanisms". The arxiv version (two-column format) is also avaiable [here](https://arxiv.org/abs/1705.10292).


## characterization_results

This folder contains the data points collected from our experiments.

**dimm_faulty_cachelines_out.csv**

The fraction of cache lines observing at least a one bit of error (i.e., bit flip) in each DIMM across a wide range of voltage levels. Analysis is in Section 4.1 of the paper.


**spatial_locality**

Spatial locality of voltage-induced errors. Analysis is in Section 4.3 of the paper.


**retention_time_profile.csv**

The retention time profile of DDR3L SO-DIMMs under different voltage levels. Analysis is in Section 4.6 of the paper.


## SPICE_circuit_model

This folder contains the SPICE model of a DRAM array. The tool used for simulation is [LTspice](http://www.linear.com/designtools/software/). The analysis is in Section 4.2, and the model description is in Appendix C of the paper.
