# AWX EE

The UPST-customised Execution Environment for AWX.

## Build the image locally

First, [install ansible-builder](https://ansible-builder.readthedocs.io/en/stable/installation/).

Then run the following command from the root of this repo:

```bash
$ ansible-builder build --verbosity 3 --tag ghcr.io/ox-it-infra/upst-awx-ee:latest # --container-runtime=docker # Is podman by default
```

## Build the image automatically

This repository should automatically build the image on commits.
