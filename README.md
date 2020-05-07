# A data-driven approach to systematically and reproduciably optimize force-field parameters 

<img src="workflow.png" width="1000">

## Features: 
* Efficient adoption of parallism for evaluating objective functions and integraing third-party packages      
* Flexible inclusions of distinct physical properties as reference data  
* Diverse choices of potential functional forms provided by third-party packages 
* Modular design to facilitate the exstensions with user-defined:  
    - objective functions 
    - sampling methods/force-field potential forms
    - optimizers 
    

## Installation: 

* conda install -c conda-forge optimize (not official)

## Software required:

* A compiled MD/MC packages exectuable (LAMMPS is already supported in the package) 

* Slurm Workload Manager (or equivalent) 

* Numpy  

* Python/3.7  

## References: 

[1]: Chan, H., Cherukara, M. J., Narayanan, B., Loeffler, T. D., Benmore, C., Gray, S. K., & Sankaranarayanan, S. K. R. S. (2019). Machine learning coarse grained models for water. Nature Communications, 10(1), 379. https://doi.org/10.1038/s41467-018-08222-6 

[2]: Wang, L.P., Chen, J., & Van Voorhis, T. (2013). Systematic Parametrization of Polarizable Force Fields from Quantum Chemistry Data. Journal of Chemical Theory and Computation, 9(1), 452–460. https://doi.org/10.1021/ct300826t  

[3]: Ercolessi, F., & Adams, J. B. (1994). Interatomic Potentials from First-Principles Calculations: The Force-Matching Method. Europhysics Letters ({EPL}), 26(8), 583–588. https://doi.org/10.1209/0295-5075/26/8/005  

[4]: Sundararaman, S., Huang, L., Ispas, S., & Kob, W. (2018). New optimization scheme to obtain interaction potentials for oxide glasses. Journal of Chemical Physics, 148(19). https://doi.org/10.1063/1.5023707 
