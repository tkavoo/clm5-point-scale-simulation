# Creating a script to help run point scale simulation using the docker version of CLM5 escomp/cesm-lab-neon and results visualization
This Jupyter Notebook contains step by step guide on how to run a simple community land model (CLM) point scale simulation at NEON sites, modify parameters and create jobs as well as visualizing the results.

## Getting Started
To use this notebook, You must have docker installed.
Run the following line of code in your terminal once you have successfully installed docker and is running.

docker pull escomp/cesm-lab-neon

Create a folder in your pc where you want your project to be located and remember the path to your folder. Modify the following line of code to match the path of the folder you have just created. This opens up jupyter lab on your browser.

docker run -it --rm -p 9999:8888 -v \PATH:/home/user escomp/cesm-lab-neon


Now you can clone this repository to your local machine in the newly created folder called tutorials:
git clone https://github.com/tkavoo/Visualizations.git

Then, navigate to the `tutorials` directory and open `neon_rs.ipynb` in Jupyter Notebook:
cd tutorials
jupyter notebook neon_rs.ipynb

## Prerequisites
This notebook requires the following Python libraries:

- netCDF4

## Usage

To use the notebook, simply run each cell in order. Each cell contains comments explaining what it does.

## Contributing

If you have suggestions for improving this notebook, please open an issue or a pull request. Contributions are always welcome!

