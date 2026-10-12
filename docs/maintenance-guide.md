# n8n Nodes Catalog maintenance guide

Pin the snapshot when comparing nodes. A metadata record describes an upstream node; it does not establish that the node is installed, configured or supported on your instance. Preserve n8n attribution.

## Installation and compatibility

Follow the repository README for the supported install method and runtime. Pin the version used in a reproducible example. Keep credentials in your client configuration, outside shared fixtures.

## Verify a change

Record the package or snapshot version, exact input, observation time and actual output. Check a materially different input and a valid neighboring case. Treat expected output as a fixture, not a live measurement.
