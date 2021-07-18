### BENCHMARKING TEST
The script allows to generate a fixed CPU load for a finite or indefinite time period, for one or more CPU cores.

The script takes in input the desired CPU load and the CPU core on which the load has to be generated. The controller and
the CPU monitor are implemented in two different Threads.

#### Dependencies
For dependencies, you have to look at the requirements.txt file and install what are inside through the command:
`$ pip install -r requirements.txt`


#### How to use the repository

1. clone the repository, type the command bellow: `$ cd benchmarking_test`
2. activate the virtual environment
3. install all the required packages from the command seen in Dependencies

Example usage:
1. Generate 65% load on cores 0, 1 and 5, until the program is interrupted through Ctrl-C:
`python main.py -l 0.65 -c 0 -c 1 -c 5`
   
#### MEMORY STRESS
run the command: `$ python memory_stress.py -m [% of memory to be used]`

### Reference

https://github.com/GaetanoCarlucci/CPULoadGenerator/tree/Python3