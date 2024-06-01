  # Parallel-Processing-Concepts-CSCI-6330-001

## Starting and running application

### Installing Required Software
* Install Python
* Install pip
* Install PySpark
  * ```$pip install pyspark```
* Install FindSpark:
  * ```$pip install findspark```

### Running the Programs Individually
* Serial
  * Navigate to ```./Serial'''
  * ```$python3 ./Project_Serial.py```
* Python Threads
  * Navigate to ```./Python_Threads```
  * ```$python3 ./Project_Python_Threads.py```
* MPI
  * Navigate to ```./MPI```
  * ```$mpirun -n 3 python Project_MPI.py```

### Running the Program as was done in the Expirement
* Navigate to the framework you want to run
  * ```./Serial```, ```./Python\ Threads```, or ```./MPI```
  * Ensure the file has execute permissons
    * ```chmod +x run.sh```
  * Execute the bash script
    * ```./run.sh > {your_file_name_here}.txt```
  * View ```{your_file_name_here}.txt``` to see the results

### View Experiment Results Files
* Navigate to ```./Results```
* View the files
