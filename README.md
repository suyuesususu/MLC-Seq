# MLC-Seq

### Description
The implementation of MLC-Seq algorithm


### Requirements
1. You must have Python3, Python version 3.5+ is required. (https://www.python.org/downloads/)
2. Clone this repository. This project is downloaded and unzipped. Now the path of the project is ~/Downloads/MLC-Seq-main.
### Environment

1. Create an virtual environment
   Open a terminal window and enter the following command line
```Bash
python3 -m venv <your_virtual_workspace_path>
```
or
```Bash
virtualenv -p python3 <your_virtual_workspace_path>
```
   In MacOS system, to make it simple we creat a "vir_env" as a virtual environment in "Downloads" folder. The command line is
```Bash
python3 -m venv ~/Downloads/vir_env
```
or
```Bash
virtualenv -p python3 ~/Downloads/vir_env
```  
2. Activate the virtual environment on Linux/MacOS
   Following step 1, enter the following command:
```Bash
source <your_virtual_workspace_path>/bin/activate
```
or on Windows(cmd.exe)
```Bash
<your_virtual_workspace_path>\Scripts\activate.bat
```
   In our case, the following command are used to activate the virtual environment(vir_env)
```Bash
source ~/Downloads/vir_env/bin/activate
```
or on Windows(cmd.exe)
```Bash
<your_virtual_workspace_path>\Scripts\activate.bat    
```

3. Install all the required libraries.
   Following step2, first go to the root directory of this project, then use the following command to install all the required libraries
```Bash
pip install -r requirements.txt
```
   In our case, use the following command lines:
```Bash
cd ~/Downloads/MLC-Seq-main
pip install -r requirements.txt
```

4. Run the MLC-Seq-main project.
   Following step 3, enter the following command line:
```Bash
jupyter notebook
```
Now we are in jupyter and all the files in MLC-Seq-main are listed.
"modules" include main tools and algorithms used in the project.
"samples" has 3 folders, they are the deconvoluted results for tRNA-Phe, Glu and Gln.
"examples" has one application (.ipnyb) and two excel sheets. The application of trna_phe_analysis.ipynb presents the data processing using tRNA-Phe as an example. The two excel sheets are the rough data for 5´ and 3´-end used in the application.

