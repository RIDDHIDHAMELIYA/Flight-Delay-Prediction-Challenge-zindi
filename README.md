# Flight Delay Prediction Challenge

## Set up your Environment
### macOS type the following commands :
* For installing the virtual environment and the required package you can either follow the commands:

pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
Or ....

* use the Makefile and run make setup or install it manually with the following commands:

make setup
After that active your environment by following commands:

source .venv/bin/activate

### WindowsOS type the following commands :
* Install the virtual environment and the required packages by following commands.

> For PowerShell CLI :

pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install -r requirements.txt

> For Git-bash CLI :

pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
pip install --upgrade pip
pip install -r requirements.txt
**Note:**If you encounter an error when trying to run pip install --upgrade pip, try using the following command:

python.exe -m pip install --upgrade pip
