# jupyter_R_Python
### Download and Install R

Download R from this [website](https://cran.r-project.org/bin/windows/base/) <br>
or <br> 
Direct Download from [here](https://cran.r-project.org/bin/windows/base/R-4.4.2-win.exe)

### Download and Install Rtools

Rtools from [here](https://cran.r-project.org/bin/windows/Rtools/rtools44/files/rtools44-6459-6401.exe) <br>
or <br>
Direct download from [here](https://cran.r-project.org/bin/windows/Rtools/rtools44/files/rtools44-6459-6401.exe)

### Download and Install Python


Download Python from this [website](https://www.python.org/downloads/) <br>
or <br> 
Direct Download from [here](https://www.python.org/ftp/python/3.13.2/python-3.13.2-amd64.exe)

### Intall Jupyter for Python
1. Open terminal
2. `python -m pip install --upgrade pip`
3. `python -m pip install jupyterlab`
4. `python -m pip install jupyter`
5. `Restart`

### Intall Jupyter for R
1. Open R terminal
2. `install.packages('devtools')`
3. `devtools::install_github('IRkernel/IRkernel')`
4. `IRkernel::installspec(user=FALSE)`
5. `Restart`
