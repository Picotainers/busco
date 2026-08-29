# busco
Container image for `busco`.

## Quick Usage
```bash
# Pull the image
docker pull docker.io/picotainers/busco:latest

# Run the tool
docker run --rm docker.io/picotainers/busco:latest --help
```

## Usage
```bash
docker run --rm -v "$(pwd):/data" docker.io/picotainers/busco:latest --help
```

## Building
```bash
docker build -t docker.io/picotainers/busco:latest .
```

The Dockerfile pins the canonical upstream BUSCO 6.1.0 release and installs its required Python runtime modules directly from PyPI; it does not use Bioconda.
