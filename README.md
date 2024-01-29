# conda_env_practice
A repository to practice creating conda environments.

## Dependencies

- `conda` (recommended installation via [Miniconda](https://docs.conda.io/en/latest/miniconda.html)).

## Usage

Create an environment on your laptop with an older version of Python!

1. Clone [this GitHub repository](https://github.com/ttimbers/conda_env_practice/blob/main/README.md).

2. Try to run some antiquated (Python 2.7 and lower compatible) Python code, such as `python -c "print 'Back from the Future'"`. This should fail.

3. In the terminal, navigate to the root of the repository and run: `conda env create --file environment.yml` (note: If you have a M1/M2 Mac, please run this command instead: `CONDA_SUBDIR=osx-64 conda env create --file environment.yml`).

4. Activate the environment by typing `conda activate oldie_but_a_goodie` 

5. Try again to run some antiquated (Python 2.7 and lower compatible) Python code, such as `python -c "print 'Back from the Future'"`. If you activated your environment correctly, this should succeed!
