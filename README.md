# clusterability-index
The algorithms based on the two mathematical programming models (Aref and Neal 2021) for computing the exact value of k-clusterability index and clusterability index of a signed network

These algorithms are written in Python 3.8 based on the two graph optimization models discussed in Aref and Neal (2021).

Binary linear programming models for partitioning signed graphs based on generalized balance theory and computing the exact values of k-clusterability index and clusterability index - Jupyter code written by Samin Aref in 2019

Creative common license: Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)

Using this code for non-commercial purposes is permitted to all given that the following publication is cited:

Aref, S., and Neal, Z.P., "Identifying splinter coalitions in the US House of Representatives by optimally partitioning signed networks based on generalized balance" (2021).

Related datasets:

Neal, Z.P. and Aref, S., "Frustrated Legislators: Replication data and code" Figshare research data repository (2021).

The following steps outline the process for installing the required software on your computer to be able to run the code:

1-Download and install Anaconda (Python 3.8 version) which allows you to run a Jupyter code. It can be downloaded from https://www.anaconda.com/products/individual. Note that you must select your operating system first and download the corresponding installer.

2-Register for an account on https://pages.gurobi.com/registration to get a free academic license for using Gurobi. Note that Gurobi is a commercial software, but it can be registered with a free academic license if the user is affiliated with a recognized degree-granting academic institution. This involves creating an account on Gurobi website to be able to request a free academic license in step 5.

3-Download and install Gurobi Optimizer (Latest version recommended) which can be downloaded from https://www.gurobi.com/downloads/gurobi-optimizer-eula/ after reading and agreeing to Gurobi's End User License Agreement.

4-Install Gurobi into Anaconda. You do this by first adding the Gurobi channel to your Anaconda channels and then installing the Gurobi package from this channel.

From a terminal window issue the following command to add the Gurobi channel to your default search list

conda config --add channels http://conda.anaconda.org/gurobi

Now issue the following command to install the Gurobi package

conda install gurobi

5-Request an academic license from https://www.gurobi.com/downloads/end-user-license-agreement-academic/ and install the license on your computer following the instructions given on Gurobi license page.

Completing these steps is explained in the following links (for version 9.1):

for windows https://www.gurobi.com/documentation/9.1/quickstart_windows/index.html

for Linux https://www.gurobi.com/documentation/9.1/quickstart_linux/index.html

for Mac OSX https://www.gurobi.com/documentation/9.1/quickstart_mac/index.html

After following the instructions above, open Jupyter Notebook which takes you to an environment (a new tab on your browser pops up on your screen) where you can open the main code (which is a file with .ipynb extension).
