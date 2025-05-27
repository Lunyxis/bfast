# bfast

e bfast package provides a highly-efficient parallel implementation for the [Breaks For Additive Season and Trend (BFASTmonitor)](http://bfast.r-forge.r-project.org)_proposed by Verbesselt et al. The implementation is based on [OpenCL](https://www.khronos.org/opencl).  

## Documentation

See the [documentation](http://bfast.readthedocs.org) for details and examples.

## Installation

This package uses [uv](https://github.com/astral-sh/uv) for package management, which is a fast, reliable Python package installer and resolver.

### Install UV

If you don't have UV installed yet, you can install it with:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Or using pip:

```bash
pip install uv
```

### Install the package

#### For development

Clone the repository and install the package in development mode:

```bash
# Clone the repository
git clone git@github.com:Lunyxis/bfast.git
cd bfast

# Create and activate a virtual environment using UV
uv venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install the package in development mode
uv pip install -e .[dev]

# Install classic dependencies
uv pip install -e .

# Running tests
uv pip install pytest
pytest
```

#### For usage

```bash
uv pip install git+https://github.com/Lunyxis/bfast.git
```

## Usage

TODO : update example usage, test, etc.

```python
import bfast

# TODO Add example usage of the bfast package
# Example: Detecting structural changes in a time series
```

<!-- ## How to run the tests
Tests for each file in the `src` directory are contained withing that
source file. In order to run the test, run:

`python file.py`

In order to get the more verbose output, run:

`python file.py --log=INFO`

In order to see the debug information, run:

`python file.py --log=DEBUG`

In order to reproduce the plots, run:

`python plots.py` -->

<!-- ## Building and publishing

Build the package:

```bash
uv pip install build
python -m build
```

Publish to PyPI:

```bash
uv pip install twine
twine upload dist/*
``` -->

## License

Proprietary. For internal use only.
@ 2025 Airbus Defence and Space. All rights reserved.
