# RetrievalRankAudit

Evaluate ranked retrieval fixtures with hit rate, mean reciprocal rank, recall at K, and per-query regression summaries.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/RetrievalRankAudit.git
cd RetrievalRankAudit
python -m pip install .
```

## Usage

```bash
retrieval-rank-audit --help
```

## Development

```bash
python -m unittest discover -s tests -v
```
