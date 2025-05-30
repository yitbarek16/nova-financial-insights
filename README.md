# Nova Financial Insights Analysis

## Project Setup

```bash
git clone https://github.com/yitbarek16/nova-financial-insights.git
cd nova-financial-insights
conda activate Conda
```

## Implement Folder structure

```
mkdir -p .vscode .github/workflows src notebooks tests scripts
touch .vscode/settings.json .gitignore README.md \
      src/__init__.py notebooks/__init__.py notebooks/README.md \
      tests/__init__.py scripts/__init__.py scripts/README.md
```

## Folder Structure

```
├── .vscode/            # IDE settings
├── .github/            # CI/CD workflows
├── data/               # Dataset storage
├── notebooks/          # Jupyter notebooks
├── src/                # Source code
├── tests/              # Unit tests
└── scripts/            # Utility scripts
```