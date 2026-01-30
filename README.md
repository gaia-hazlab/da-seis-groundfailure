# da-seis-groundfailure

A Python project for seismic data analysis and ground failure assessment.

## Installation

### Prerequisites

Install pixi: [https://pixi.sh/dev/installation/](https://pixi.sh/dev/installation/)

### Setup

1. Clone this repository
2. Navigate to the project directory:
   ```bash
   cd da-seis-groundfailure
   ```

3. Install dependencies with pixi:
   ```bash
   pixi install
   ```

4. Activate the environment:
   ```bash
   pixi shell
   ```

## Usage

### Launch Jupyter Lab

```bash
pixi run jupyter lab
```

In VSCode, select the Python kernel called 'default' (with a path `.pixi/envs/default/bin/python`) for notebooks in this repository.

### Notebooks

Example notebooks are located in the `notebooks/` directory.

## Project Structure

```
.
├── README.md
├── pixi.toml          # Package dependencies
└── notebooks/         # Jupyter notebooks
    └── template.ipynb # Template notebook to get started
```

## Dependencies

Main packages included:
- jupyter-lab
- matplotlib
- numpy
- pandas
- scipy
- seaborn

See `pixi.toml` for the complete list of dependencies.
