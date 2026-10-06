# Command Line Interface — ANGULAR_POINT_OF_SALE

**Upstream:** https://github.com/nicedoc/angular-point-of-sale

## Anticloud CLI

```bash
# Install
pip install anticloud-angular-point-of-sale

# Run offline with PAX inference
anticloud-angular-point-of-sale --offline --pax-local

# Run with AIOSS logging
anticloud-angular-point-of-sale --aioss-log ./ledger.jsonl

# Single binary (after build)
./angular_point_of_sale --config config.yaml
```

## Options

| Flag | Description |
| --- | --- |
| `--offline` | Disable all network calls |
| `--pax-local` | Use local PAX inference at 127.0.0.1:11434 |
| `--aioss-log PATH` | Write AIOSS audit chain to PATH |
| `--encrypt` | Enable AES-256 at rest for output files |
| `--gpu` | Force GPU inference |
| `--cpu` | Force CPU inference |
| `--config PATH` | Load configuration from YAML file |
