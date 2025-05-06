# AWX EE

Custom execution environment for building baremetal ocp clusters.

## Build the image locally

First, [install ansible-builder](https://ansible-builder.readthedocs.io/en/stable/installation/).

Then run the following command from the root of this repo:

```bash
$ ansible-builder build -v3 -t quay.io/cragr/awx-ocp-bm-ee # --container-runtime=docker # Is podman by default
```
