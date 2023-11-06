# Bioimage_analysis_practical

This GitHub repository consist of .ipynb files used as introduction to bio image analyis. It consists of the following notebooks:

Notebooks
  1. 00_Introduction_to_bioImages
  2. 01_Segmentation_and_the_Napari_image_viewer

This tutorial assumes you have installed a working version of anaconda on your computer (https://docs.anaconda.com/free/anaconda/install/index.html). Open the anaconda terminal and perform the steps under requirements and installation to start this tutorial.

# requirements and installation
In order to install the necessary packages and start jupyter notebook type in your anaconda terminal:

1. cd /this/cloned or downloaded/github/repo
2. conda env create --name practical --file practical.yml
3. conda activate practical
4. jupyter notebook

# detailed installation instructions
\begin{itemize}
\item anaconda (install from \href{https://anaconda.com}{website}). You can install pycharm and/or spyder, but neither are required for this practical. 
\item image data folder from canvas (find the zip file pertaining to your group, download and unzip)
\end{itemize}

\subsubsection{setting up virtual environment for the practical}
For a clean setup, we will create a new python virtual environment. 
A virtual environment ensures that 
\begin{itemize}
\item we use an appropriate python version
\item all the dependencies (i.e. required software packages) are there
\item the dependencies for this project do not interfere with other software on your machine
\end{itemize}

We will delegate the work of creating/organising the virtual environment to anaconda. 

\subsubsection{navigation to correct folder}
{\bf Under windows}, hit the windows key and type anaconda. You should see 
\begin{verbatim} anaconda prompt \end{verbatim} 
as a choice. Open anaconda prompt. 

You should see a command line interface that looks something like:

\begin{verbatim} (base) C:\Users\YourUserName> _ \end{verbatim}

Use the command line to navigate to the unzipped data folder you downloaded from github. 
There, navigate to the downloaded folder. 
type \begin{verbatim} dir \end{verbatim}
to explore the directory's contents.
You should find a file named \begin{verbatim} practical.yml \end{verbatim}.

{\bf On mac}, navigate to the downloaded folder from github. Right-click on the folder and select {\it open in new terminal window}.
You should see a command line interface that looks something like:

\begin{verbatim} (base) User@user: ~/whereever/you/donwloaded/the/folder/from/github$ _ \end{verbatim}

\subsubsection{creation of environment}
The {\it (base)} in your command line interface tells you that you are in the base environment - we have not created a custom environment yet. Now, create a new environment by typing the following:
\begin{verbatim} conda env create --name practical --file practical.yml \end{verbatim}
This tells anaconda to create a new environment, which is named {\it practical}.

After the environment is created, we need to activate it. Type:
\begin{verbatim} conda activate practical \end{verbatim}
On, windows, your command line should now show 
\begin{verbatim} (RNA_Imaging) C:\The\location\of\your\downloaded\folder> _ \end{verbatim}
 
On mac, you should see:
\begin{verbatim} (RNA_Imaging) User@user: ~C:/The/location/of/your/downloaded/folder$ _ \end{verbatim}
 
Then, open Jupyter Notebooks, by typing:
 
\begin{verbatim} jupyter notebook \end{verbatim}
 
 If all is well, jupyter notebooks should open. Navigate to the notebooks folder and open the first notebook. 
 
# Example dataset
Example dataset is avalaible on zenodo : 10.5281/zenodo.10026857. Please download and unzip the data folder to the current directory where this README.md document resides. 