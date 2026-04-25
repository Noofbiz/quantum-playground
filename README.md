# Quantum Playground

This is a little place where I practice quantum programming.
Don't have much here yet. Check back later for more content.

## Setup

The conda environment is defined in `environment.yml`. If this is the first time
you are using this, you can create the environment with the following command:

```bash
conda env create -file environment.yml
```

Then, you can activate the environment with:

```bash
conda activate quantum-playground
```

Now you can export the enviornment as a jupyter kernel:

```bash
ipython kernel install --user --name=quantum-playground-kernel
```

## Running the code

The code is organized in Jupyter notebooks in the folders within. You can run
the notebooks in your preferred way. Make sure to activate the conda environment
before running the notebooks to ensure that all the dependencies are available.
