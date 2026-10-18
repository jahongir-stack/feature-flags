# Feature Flags

Deterministic SHA-256 percentage rollout with explicit allow/deny targeting.

**Requires:** Python 3.11 or newer. No external dependencies.

## Tests

```sh
python -m unittest discover -s . -p 'test_core.py' -v
```

`core.py` contains the implementation; `test_core.py` contains examples and tests. GitHub Actions runs the tests on Python 3.11–3.13.

**Limitations:** Educational reference implementation. Production feature-flag platforms also require durable storage, management UI, monitoring and rollout controls.
