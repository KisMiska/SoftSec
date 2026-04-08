## Running Tests

### Run all tests with pytest:
```bash
pytest test_ciff.py -v
```

### Run tests with coverage report:
```bash
coverage run -m pytest test_ciff.py
coverage report
```

### Generate HTML coverage report:
```bash
coverage run -m pytest test_ciff.py
coverage html
```

## Type Checking
```bash
mypy --config-file mypy.ini src/ciff.py
```