# nf-core/configs: Alliance Canada Configuration

Configuration for running nextflow on the clusters of the Digital Research Alliance of Canada. With the config copied to `~/.nextflow/config` the clusters will be detected automatically.
If you are part of multiple resource allocations the allocation can be set with `export SLURM_ACCOUNT=<def-user>` before you run any nf-core pipeline.
If you run nf-core frequently and always use the same resource allocation, you may find it more convenient to add the `SLURM_ACCOUNT` environment variable to your `~/.bashrc` file.
The file contains configurations for the following clusters: Fir, Narval, Nibi, Rorqual, and Trillium.

For detailed information on running nf-core pipelines on Alliance clusters, please visit the documentation:
https://docs.alliancecan.ca/wiki/Nextflow

If you run into issues, please contact Alliance Support:
https://docs.alliancecan.ca/wiki/Technical_support
