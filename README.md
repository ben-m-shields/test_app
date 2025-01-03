# Skin Dose Calculator
This is the intro to the skin dose calculator software
## Installation
The following includes all steps to install on a Debian/Ubuntu linux operating system.

### Download and Install R
```bash
sudo apt-get update
sudo apt-get upgrade
sudo apt-get -y install r-base
sudo apt-get -y install r-base-dev
```

### Download and Install RStudio
Download the .deb RStudio file for your OS to the /home/username/Downloads folder from the official RStudio website
```bash
sudo apt-get -y install libcurl4-openssl-dev libssl-dev libxml2-dev libudunits2-dev libgdal-dev cargo libfontconfig1-dev libcairo2-dev
sudo apt-get -y install gdebi
sudo gdebi /home/username/Downloads/your_rstudio_file.deb
```

### Install R packages
```bash
sudo chown username /usr/local/lib/R/site-library
R
install.packages("shiny")
q()
n
```

### Clone repository to desktop
```bash
cd /home/Username/Desktop
mkdir app
sudo apt -y install git
git https://github.com/ben-m-shields/test_app.git /home/Username/Desktop/app
```

Launch app.R from rstudio.
