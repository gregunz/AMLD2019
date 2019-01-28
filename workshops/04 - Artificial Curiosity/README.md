# Artificial Curiosity: Intrinsic Motivation in Machines too!

This repository contains the code and models for the Artificial Curiosity Visium workshop at AMLD 2019.

## How to run the code on your computer?

### Build a Docker image from this repository
1. Install Docker
    * Windows 10, Mac OS, Linux: find your OS on <https://docs.docker.com/install/#supported-platforms>
    * Windows <10: follow the instructions on <https://docs.docker.com/toolbox/toolbox_install_windows/> to install Docker Toolbox
2. Download this repository
3. Open a terminal and move in the repository
    * Windows 10, Mac OS, Linux: use your favorite terminal application
    * Windows <10: use the Docker Quickstart Terminal installed with Docker Toolbox
4. Build the Docker image: type `docker build -t visium_amld_rl .` (this might take a while)

### Run the image
5. Still from the repository, run the Docker image:
    * Windows Command Line: type `docker run -it -p 8888:8888 -v %cd%:/app visium_amld_rl`
    * Windows PowerShell / Mac OS / Linux: type `docker run -it -p 8888:8888 -v ${PWD}:/app visium_amld_rl`
6. The container will automatically start a Jupyter notebook server
    * Mac OS, Linux: go to <http://localhost:8888>
    * Windows: go to <http://192.168.99.100:8888>

## How to see the notebook without running it?

1. Simply go to <http://thibaultcalvayrac.github.io/AMLD_artificial_curiosity> (this page will be available during the workshop)
