# Epidemiological Forecasting Engine

Advanced epidemiological forecasting using ensemble ML methods, SEIR compartmental models, and real-time surveillance data integration.

## Architecture

```
epidemiological-forecasting-engine/
  src/           # Core modules
  tests/         # Unit and integration tests
  config/        # Configuration files
  docs/          # Documentation
```

## Modules

- **seir_model**: Core seir model functionality
- **r0_estimator**: Core r0 estimator functionality
- **contact_tracing**: Core contact tracing functionality
- **ensemble_forecast**: Core ensemble forecast functionality
- **nowcasting**: Core nowcasting functionality

## Quick Start

```bash
pip install -r requirements.txt
python -m epidemiological_forecasting_engine.main
```

## Testing

```bash
pytest tests/ -v
```

## License

MIT License - see LICENSE for details.
