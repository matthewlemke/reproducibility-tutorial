# reproducibility-tutorial
FOSS2020 reproducibility exercise

## Clone the github repo
    1  cd /scratch
    2  fd -h
    3  df -h
    4  pwd
    5  git clone https://github.com/matthewlemke/reproducibility-tutorial.git
    6  clear
    7  /opt/conda/bin/conda search -c bioconda snakemake
    8  wget /opt/conda/bin/conda search -c bioconda snakemake
    9  wget /opt/conda/bin/conda search -c bioconda snakemake
   10  wget 
   11  161 packages can be updated.
   12  63 updates are security updates.
   13  *** System restart required ***
   14  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   15  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   16    
   17   ln -s /opt/conda/pkgs/*/bin/* /bin
   18      
   19   ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   20   /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   21  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   22  
   23  /opt/conda/bin/pip install bash_kernel
   24  /opt/conda/bin/pip install ipykernel
   25  /opt/conda/bin/python3 -m bash_kernel.install
   26  clear
   27  /opt/conda/bin/conda
   28  /opt/conda/bin/conda -c bioconda
   29  /opt/conda/bin/conda search -c bioconda
   30  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   31  /opt/conda/bin/conda search -c bioconda snakemake
   32  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   33  ln -s /opt/conda/bin/* /bin
   34  ln -s /opt/conda/lib/* /usr/lib
   35  snakemake --version
   36  sudo apt-get update
   37  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   38  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   39  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
 $(lsb_release -cs) \
 stable"
   40  sudo apt-get update
   41  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   42  docker run hello-world
   43  cd /scratch/reproducibility-tutorial/
   44  history >>README.md
