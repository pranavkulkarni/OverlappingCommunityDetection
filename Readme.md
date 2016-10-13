
Required packages: networkx, numpy

Run command:

python p2.py <edgelist_file_name>
Example:
python p2.py datasets/amazon/amazon.graph.small
Note: the output file takes the name of the input edge list file and appends "output". So please make sure that edge list file is in the above mentioned directory structure. Similarly for other directories like youtube and dblp.

The output file contains identified clusters on each new line. Nodes within a cluster are separated by whitespace and nodes may belong to more than one cluster.

Sample input and output files are included in the zip.
Sample output file: amazon.graph.small_output.txt
