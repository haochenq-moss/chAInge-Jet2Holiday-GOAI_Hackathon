# chAInge Jet2Holiday GOAI Hackathon

This repository contains the `chAInge` project prepared for the Jet2holidays GOAI Hackathon.

The source package is currently a lightweight Python 3.11 scaffold. Project demonstrations and supporting presentation material are available in [`docs/`](docs/).

## Requirements

- Python 3.11 or newer
- [`uv`](https://docs.astral.sh/uv/) is recommended for environment and package management

## Getting Started

### Using `uv`

From this directory:

```bash
uv sync
uv run chainge-jet2holiday-goai-hackathon
```

The command currently prints a greeting from the package.

### Using a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -e .
chainge-jet2holiday-goai-hackathon
```

On Windows PowerShell, activate the environment with:

```powershell
.venv\Scripts\Activate.ps1
```

## Project Layout

```text
.
├── docs/                                  # Demos and presentation material
├── src/
│   └── chainge_jet2holiday_goai_hackathon/ # Python package
├── .python-version                        # Project Python version (3.11)
└── pyproject.toml                         # Package metadata and build configuration
```

## Documentation and Demos

The [`docs/`](docs/) directory currently includes:

- [`chAInge_quick_demo.mp4`](docs/chAInge_quick_demo.mp4)
- [`chAInge_full_demo.mp4`](docs/chAInge_full_demo.mp4)
- [`chAInge_project_overview.pdf`](docs/chAInge_project_overview.pdf)
- [`chAInge_slides.pptx`](docs/chAInge_slides.pptx)
- [`chAInge_demo deck.pdf`](docs/chAInge_demo%20deck.pdf)

## Development

The package uses a `src/` layout and is configured through [`pyproject.toml`](pyproject.toml). After making changes, run the package entry point to perform a basic smoke check:

```bash
uv run chainge-jet2holiday-goai-hackathon
```

Tests and additional runtime dependencies have not yet been added to this scaffold.
