# 2026-residual-emissions
Evaluate residual emissions "landing zones" in deep mitigation scenarios

## Environment Setup

This project uses Pixi for reproducible environment management. Follow the instructions below to set up your environment and replicate the results.

### Prerequisites

Install Pixi by following the instructions at TODO:

**macOS/Linux:**
```bash
curl -fsSL https://pixi.sh/install.sh | bash
```

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd 2026-residual-emissions
```

2. Install dependencies using Pixi:
```bash
pixi install
```

This will create a reproducible environment with all required dependencies as specified in [pixi.toml](pixi.toml).

### Running the Analysis

Activate the Pixi environment and launch JupyterLab:

```bash
pixi run jupyter lab
```

Alternatively, you can run individual Python scripts within the Pixi environment:

```bash
pixi run python <script-name>.py
```

