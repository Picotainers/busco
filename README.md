# busco
Container image for `busco`.

## Quick Usage
```bash
# Pull the image
docker pull docker.io/picotainers/busco:latest

# Run the tool
docker run --rm docker.io/picotainers/busco:latest --help
```

## Usage with input files
```bash
docker run --rm -v "$(pwd):/data" docker.io/picotainers/busco:latest --help
```
