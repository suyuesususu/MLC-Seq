# MLC-Seq

### Description
The implementation of MLC-Seq algorithm


### Requirements
1. You must have Python3, Python version 3.5+ is required. Please download the python file and follow the instruction for installation. (https://www.python.org/downloads/)
2. Clone this repository. Click the green button "Code" and click the "Download ZIP" button. Unzip the file.
   In MacOS system, the path of the project is ~/Downloads/MLC-Seq-main. In Windows system, the path of the project is C:\MLC-Seq-main.
### Environment

#### Prepare the environment for Linux/MacOS
1. Open the Terminal.
2. Create an virtual environment by the following command
```Bash
python3 -m venv <your_virtual_workspace_path>
```
To make it simple we can setup the virtual environment "vir_env" in "Downloads", enter the command:
```Bash
python3 -m venv ~/Downloads/vir_env
```
3. Activate the virtual environment
```Bash
source <your_virtual_workspace_path>/bin/activate
```
Using the same case, the command is:
```Bash
source ~/Downloads/vir_env/bin/activate
```
4. Go to the root directory of this project MLC-Seq-mian and install all the required libraries.
```Bash
cd ~/Downloads/MLC-Seq-main
pip install -r requirements.txt
```
#### Prepare the environment for Windows
1. Open the Command Prompt(cmd.exe).
2. Create an virtual environment by the following command
```Bash
python3 -m venv <your_virtual_workspace_path>
```
To make it simple we can setup the virtual environment "vir_env" in C drive, enter the command:
```Bash
python3 -m venv C:\vir_env
```
3. Activate the virtual environment
```Bash
<your_virtual_workspace_path>\Scripts\activate.bat
```
Using the same case, the cammand is:
```Bash
C:\vir_env\Scripts\activate.bat
```
4. Go to the root directory of this project and install all the required libraries.
```Bash
cd C:\MLC-Seq-main
pip install -r requirements.txt
```
### Launch the project
Run the following command to launch the project, the main page of MLC-Seq-main will be presented in your default browser.
```Bash
jupyter notebook
```
Now we are in jupyter and the main page of MLC-Seq is presented in your default browser. We will be processing the data in this window.<br>
"modules" includes main tools and algorithms used in the project.<br>
"samples" has 3 folders, they are the deconvoluted datasets for tRNA-Phe, Glu and Gln.<br>
"examples" has one application (.ipnyb) and two excel sheets. The application of trna_phe_analysis.ipynb presents the data processing using tRNA-Phe as an example. The two excel sheets are the rough data for 5´ and 3´-end used in the application.<br>

