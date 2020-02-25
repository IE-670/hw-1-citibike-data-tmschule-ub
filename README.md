### hw-1-citibike-data-tmschule-ub
----

Timothy Schuler

IE670

### Instatllation Instructions


Clone the repository:

    git clone https://github.com/IE-670/hw-1-citibike-data-tmschule-ub.git

The project requires matplotlib to analyze some of the data.  If you have not installed matplotlib you can do so with pip:

    pip3 install matplotlib
    
### Configuration Details

NOTICE:  This repository does not include any citibike data.  It does require a path to a citibike trip data file. Right now the value is set to look for a file in 

    '/home/tim/development/data/citibike/202001-citibike-tripdata.csv'
    
The user of the notebook should change this to the location of the their tripdata.csv on their own file system. 

### Running the notebook

Change directories to the location of the notebook.

      cd ${your.directory.where.the.notebook.exists}
      
Run the notebook:

      jupyter notebook
      
