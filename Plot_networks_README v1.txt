MCRL - Metagenomic Clustering by Reference Library

AUTHOR
Arbel D. Tadmor(1,2)

1) TRON - Translational Oncology at the University Medical Center of the Johannes Gutenberg, University Mainz, 55131, Mainz, Germany
2) Department of Biochemistry and Molecular Biophysics, California Institute of Technology, Pasadena, CA 91125, USA

LICENSE AGREENENT 
By using this program you agree to the terms provided in the license agreement (license.txt).


PLOTTING REFERENCE GENE NETWORKS FOR MCRL
-----------------------------------------

To plot reference gene network, first configure the setup file 'config_file_network.txt' found in the "networks" folder of the MCRL installation. 

This configuration file has three parts: 

1. Select between four options for labeling nodes:
   a. all: all nodes are labeled with reference gene IDs
   b. none: no labels are plotted
   c. auto: optimize label plotting to image complexity
   d. epicenter: plot only labels of reported reference genes
2. Enter the name of the “MCRL_table_nr.txt” output file using a full path
3. Enter one or more reported reference genes. 
   A reference gene network will be plotted for each reference gene in this list. 
   These reference genes must be reported reference genes included in the list provided in the MCRL_table_nr.txt output file.

Example of format:
	# Node labels (all/none/epicenter/auto)
	autoW

	# MCRL_table_nr.txt file
	C:\MCRL\FFFFFFFF_BLAST_table_EXAMPLE_MCRL_Table_nr.txt

	# Reported reference gene(s)
	YP_004957306.1
	YP_002290892.1
	YP_009216194.1


Next, install the executable Plot_networks_installer_WIN64.exe.

Then from the command line execute the following command:

>Plot_networks_installer_WIN64.exe <path>\networks\config_file_network.txt

where <path> is the installation path of MCRL.

Figures will be saved to the "output" folder in the MCRL installation path with the appropriate RUN_ID.