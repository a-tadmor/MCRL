MCRL - Metagenomic Clustering by Reference Library

RELEASE
v3.0.8 

AUTHOR
Arbel D. Tadmor(1,2)

1) TRON - Translational Oncology at the University Medical Center of the Johannes Gutenberg, University Mainz, 55131, Mainz, Germany
2) Department of Biochemistry and Molecular Biophysics, California Institute of Technology, Pasadena, CA 91125, USA

LICENSE AGREENENT 
By using this program you agree to the terms provided in the license agreement (license.txt).

--------------  RUNNING MCRL UNDER WINDOWS --------------
INSTALLATION REQUIREMENTS:
* 64-bit Windows
* Internet connection and administrator privileges
 
INSTALLATION INSTRUCTIONS:
Part I: install "MATLAB Compiler Runtime"
1. Double click the executable MCRL_installer_WIN64.exe
2. Follow instructions to install the "MATLAB Compiler Runtime" (MCR)

Part II: install MCRL
3. Once the "MATLAB Compiler Runtime" is installed, navigate to the "application" folder and double click the executable MCRL.exe
4. Click “Automatic installation (recommended)” 
5. Once the installation of BLAST starts click ‘next’ and accept all of the default entries (note: watch for the prompts by Windows, BLAST and MCRL requiring user response). 
   Once blast is locally installed MCRL will proceed to download and assemble the most recent viral RefSeq database.
6. Once the main interface of MCRL loads you may start using MCRL. 

Installation takes about 20 minutes depending on the computer and internet connection speed.

To produce plots for reference gene networks double click the executable "Plot_networks_installer_WIN64.exe" and follow instructions to install.

--------------  RUNNING MCRL IN MATLAB --------------
INSTALLATION  REQUIREMENTS:
* Matlab 2014a or later 
* Bioinformatics toolbox 
* Parallel Computing toolbox v4.2 or higher (optional) 
* Internet connection and administrator privileges

INSTALLATION INSTRUCTIONS:
1. Extract the compressed sources of MCRL locally 
2. Start up Matlab 
3. Change directories in Matlab to the 'bin' folder  
4. Run MCRL by typing MCRL_EXE in the Matlab command prompt 
5. Click “Automatic installation (recommended)” 
6. Once the installation of BLAST starts click ‘next’ and accept all of the default entries (note: watch for the prompts by Windows, BLAST and MCRL requiring user response). 
   Once blast is locally installed MCRL will proceed to download and assemble the most recent viral RefSeq database.
7. Once the main interface of MCRL loads you may start using MCRL. 

Installation may take 10 to 20 minutes depending on the computer and internet connection speed.

----------------------------------------------------------
TROUBLESHOOTING
1. Do not install MCRL in the "Programs Files" folder or other Windows systems folders

2. If there is a problem downloading the blast software or RefSeq files make sure you have an internet connection and that the firewall is not blocking the ftp port.

3. If there is a problem downloading the blast software, blast v2.2.22+ can be downloaded manually from the NCBI website: ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/2.2.22/, selecting the software version appropriate for your OS. 

Installation instructions for blast can be found here:
ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/2.2.22/user_manual.pdf

Once blast is installed, start MCRL, click “Locate sources on computer” and locate the bin folder of the blast installation.

4. If there is a problem running blast there may be a previous installation of blast from another utility which is interfering with MCRL. In you are running Windows and Windows is installed on the c:\ drive, check the Windows folder for a file called ncbi.ini and temporarily rename it.

----------------------------------------------------------
CITATION
Tadmor & Phillips, MCRL: probing metagenomes for known diversity by clustering reference genes with similar metagenomic signatures (submitted, 2019)