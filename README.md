# generatoranalysis
Analysis scripts used for beam generator and moller + pion generators
All python files are set up for slurm submission on national clusters (in our case, Beluga), and therefore require proper bash scripts for the submissision to follow through. The bash script will need to specify the account desired, the time required for the job to be completed, the memory allocaiton, and the cpus-per-task that will be used to run the script. Usually, running 4 cpus is enough. Any higher yields the chance the job will take longer to submit. 
